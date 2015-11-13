---
layout: page
title: Home
---

Pretty Swift is a learning resource to help beginning programmers get started with iOS development. The project has three goals.

1. Teach the basics of iOS app development, including Swift, Cocoa Touch, and Xcode using a constructionist approach: learning by doing exercises and problem-based learning.
2. Equip students to make the conceptual leap from following a set of prescribed steps in a tutorial to building their own app from scratch.
3. Help students learn how to learn about iOS development topics so they can continue advancing their knowledge on their own after they finish working through the Pretty Swift materials.

This course is a roadmap for beginning iOS developers.

## Table of Contents

<ol>
{% for article in site.data.lessons %}
  <li>
    <a href="{{ site.lessonurl }}/{{ article.url }}">
      {{ article.title }}
    </a>
  </li>
{% endfor %}
</ol>
