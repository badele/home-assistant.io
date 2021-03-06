---
layout: page
title: "Logitech Squeezebox support"
description: "Instructions how to integrate a Logitech Squeezebox into Home Assistant."
date: 2015-08-09 11:00
sidebar: false
comments: false
sharing: true
footer: true
---

<img src='/images/supported_brands/logitech.png' class='brand pull-right' />
The squeezebox platform allows you to control a [Logitech Squeezebox](https://en.wikipedia.org/wiki/Squeezebox_%28network_music_player%29) multimedia system from Home Assistant.

To add your Squeezebox to your installation, add the following to your `configuration.yaml` file:

```
# Example configuration.yaml entry
media_player:
  platform: squeezebox
  host: 192.168.1.21
  port: 9090
  username: USERNAME
  password: PASSWORD
```

Configuration variables:

- **host** *Required*: The host name or address of the Logitech Media Server.
- **port** *Optional*: Telnet port to Logitech Media Server, default 9090.
- **username** *Optional*: The username, if password protection is enabled.
- **password** *Optional*: The password, if password protection is enabled.
