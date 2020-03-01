---
layout: default
---


# hello world

{% assign my_secret_string = "HelloWorld!" | hmac_sha256: "secret_key" %}
My encoded string is: {{ my_secret_string }}