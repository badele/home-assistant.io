---
layout: page
title: "Developers"
description: "Home Assistant developer information. Everything to get you started"
date: 2014-12-21 13:32
sidebar: false
comments: false
sharing: true
footer: true
---

Home Assistant is build from the ground-up to be easily extensible by other developers using
components. It uses [Python 3](https://www.python.org/) for the backend and
[Polymer (Webcomponents)](https://www.polymer-project.org/) for the frontend.

Home Assistant is open-source and MIT licensed. The source can be found here:

 - [home-assistant](https://github.com/balloob/home-assistant) - Python server-backend
 - [home-assistant-js](https://github.com/balloob/home-assistant-js) - javascript-backend powering the client
 - [home-assistant-polymer](https://github.com/balloob/home-assistant-polymer) - Polymer UI

### {% linkable_title Starting development %}

You will need to setup a development environment if you want to start developing a new feature or
component for Home Assistant perform theses steps

```bash
cd your_root_folder_project
git clone https://github.com/balloob/home-assistant.git
cd your_root_folder_project/home-assistant
script/setup
```

After following these steps, running `hass` will invoke your local installation.

### {% linkable_title Submitting improvements %}

Improvements to Home Assistant should be submitted one feature at a time using Github pull
requests.

 1. Go to [the Home Assistant repository](https://github.com/balloob/home-assistant)
    and click fork in the top right.
 2. Follow steps in the previous section but with your forked repository.
 3. Create a new branch to hold your changes<br>
    `git checkout -b some-feature`
 4. Make the changes you want
 5. Commit the changes<br>
    `git add .`<br>
    `git commit -m "Added some-feature"`
 6. Push your commited changes back to your fork on Github<br>
    `git push origin HEAD`
 7. Follow [these steps](https://help.github.com/articles/creating-a-pull-request/) to create your
    pull request.

### {% linkable_title Further reading %}

<ul>
  <li><a href="{{ root_url }}/developers/architecture.html">
    Home Assistant Architecture
  </a></li>
  <li><a href="{{ root_url}}/developers/frontend.html">Frontend development</a></li>
  <li><a href="{{ root_url}}/developers/creating_components.html">
    Creating a custom component
  </a></li>
  <li><a href="{{ root_url}}/developers/add_new_platform.html">
    Adding support for a new platform
  </a></li>
  <li><a href="{{ root_url }}/developers/api.html">Rest API</a></li>
  <li><a href="{{ root_url }}/developers/website.html">Website </a></li>
</ul>
