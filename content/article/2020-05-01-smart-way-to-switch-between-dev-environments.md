---
layout: post
title: "A Smart way to switch between dev environments."
tags:
date: 2020-05-01
modified: 2020-05-01
description: As part of the web production workflow, I currently have various environments. To validate a page between live and staging
image: "https://static.scube.co/shovan.uk/blog/2020/smart-way-to-switch-between-dev-environments.png"

---
As part of the web production workflow, I currently have various environments. To validate a page between live and staging requires one manually change the URL path from www. to staging. .

I am looking to simplify this process, reduce human error and automate where possible. I found [Domain Switcher](https://chrome.google.com/webstore/detail/domain-switcher/lbehdhpgigdlinfkidifkbhjnaglfojc){:target="_blank"} chrome extension that does does what I need.

**Environment breakdown**

* Live Environment: **www.**website.com
* Staging Environment: **staging.**website.com
* Dev Environment: **dev.**website.com
* QA Environment: **qa.**website.com
* Local Environment: **local.**website.com

**Extension Setup**
Install [Domain Switcher](https://chrome.google.com/webstore/detail/domain-switcher/lbehdhpgigdlinfkidifkbhjnaglfojc){:target="_blank"} extension on your chrome browser

Once installed, click on options.

![Once installed click on options](https://static.scube.co/shovan.uk/blog/2020/domain-switcher-setup.gif "Once installed click on options ")

Add your dev environments to the list.

![Development Environments](https://static.scube.co/shovan.uk/blog/2020/website-environment.gif "Add your dev environments to the list ")

Now go the website **website.com** and click on the Domain Switcher extension, you will see options for the different environments in the dropdown.

![Development Environments](https://static.scube.co/shovan.uk/blog/2020/environment-switcher.gif "Add your dev environments to the list ")
