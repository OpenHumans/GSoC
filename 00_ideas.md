---
layout: page
title: Project Ideas
permalink: /ideas/
---

# Google Summer of Code 2018 Project ideas

The details of each of our project ideas are listed below, including potential
mentors. Interested students should join [#gsoc channel on our Slack](http://slackin.openhumans.org) and announce their interest.

See the [main Open Humans Google Summer of Code page](../) for more information about the GSoC
program and additional ways to get in touch with us.


#### Quick links

* Table of Contents
{:toc}

## Project Ideas

### Writing a stand-alone project admin backend
*Open Humans* is a modular eco system in which users can start their own projects
that can request data from users or put new data into the accounts of users.
These interactions are done largely through APIs. But for many basic administrative
works a graphical user interface would be good to have. Such a GUI
should be a stand-alone Django application that interfaces with the existing
Open Humans API methods. You can find
[more details in the corresponding GitHub issue](https://github.com/OpenHumans/open-humans/issues/690).

This project requires rudimentary skills in web application design and ideally some familiarity with Django/Python.
Students will learn how to interface with APIs and how build modular web applications. This project can be mentored by
[Mad](https://github.com/madprime) and/or [Bastian](https://github.com/gedankenstuecke).

### Add new data sources
Members of *Open Humans* can connect data and upload data from external resources into their
accounts to share this data with other projects, research studies and individuals. Many of these
data imports are community curated. We are looking for students who are interested in contributing
new data sources. Write a data importer for your favorite sleep tracking, diet logging or
social media application.

Some data import ideas we had so far:
* RescueTime
* Google location history through Google Takeout
* Personal Facebook feed

These projects require rudimentary skills in web application design to connect to *Open Humans*.
Students will learn how to interface with the APIs of their data source as well as the Open Humans API. Additionally
students will become more familiar with building decentralized applications. This project can be mentored by
[Mad](https://github.com/madprime) and/or [Bastian](https://github.com/gedankenstuecke).


**Feel free to propose your own entirely new idea.**
