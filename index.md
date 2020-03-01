---
layout: default
---


# hello world

{% assign my_secret_string = "hello!" | sha1 %}
My encoded string is: {{ my_secret_string }}