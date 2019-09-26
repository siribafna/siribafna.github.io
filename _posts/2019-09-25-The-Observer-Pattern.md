---
layout: post
title: The Observer Pattern
---

The Observer Pattern, one of the many behavioral design patterns that Java consists of, is known for stating and managing communication between an "observable", which is an *object*, and its observers. These objects notifies and updates changes in its state to its observers.

**We can implement this pattern in the following way:**

    public class NewsAgency {
    private String news;
    private List<Channel> channels = new ArrayList<>();
    public void addObserver(Channel channel) {
        this.channels.add(channel);
    }
 
    public void removeObserver(Channel channel) {
        this.channels.remove(channel);
    }
 
    public void setNews(String news) {
        this.news = news;
        for (Channel channel : this.channels) {
            channel.update(this.news);
        }
    }
    }

**Java** uses this pattern through a class called *java.util.Observerable* and an interface called *java.util.Observer*
