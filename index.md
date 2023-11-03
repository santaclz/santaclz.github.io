---
layout: home
title: santaclz's blog
---

<div class="home">
    <h1>Welcome to santaclz's blog!</h1>
    <p>
        Here, you'll find posts focusing on system internals, reverse engineering, and exploitation.
        Feel free to explore and connect via 
        <a href="https://twitter.com/santaclzz" target="_blank">Twitter</a> or 
        <a href="https://github.com/santaclz" target="_blank">GitHub</a>.
    </p>

    <div class="posts-list">
        {% for post in site.posts %}
            <h2 class="post-title">
                <a href="{{ post.url }}">{{ post.title }}</a>
            </h2>
        {% endfor %}
    </div>
</div>

<style>
    .home {
        text-align: center;
        padding: 50px;
    }

    .posts-list {
        margin-top: 50px;
    }

    .post-title {
        font-size: 24px;
    }

    .post-meta {
        font-size: 18px;
        color: #888;
    }
</style>
