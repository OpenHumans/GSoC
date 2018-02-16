---
layout: page
title: Project Ideas
permalink: /ideas/
---

# Open Humans Outreachy 2018 Project ideas

The details of each of our project ideas are listed below, including potential
mentors. Interested students should join [#outreachy channel on our Slack](http://slackin.openhumans.org) and announce their interest.

See the [main Open Humans Outreachy page](../) for more information about the Outreachy
program and additional ways to get in touch with us.

#### Quick links

* Table of Contents
{:toc}

## Contributing: General tips

All our projects involve working with open source web apps &ndash; probably
Django, and running on Heroku. (This is what our team has the most expertise
in!) We have templates and example Django projects to help you get started.

**Django tutorial:** If you're new to Django, we recommend you do the [Django tutorial](https://docs.djangoproject.com/en/2.0/intro/tutorial01/) first, to
get a feel for Django project development.

**Python development with pipenv:** [Pipenv](http://pipenv.readthedocs.io/en/latest/)
is now the officially recommended packaging tool for Python development. We
recommend you install and use this, and we're working on transitioning our own
projects to this.

Pipenv will help you create and manage virtual environments that provide the
package dependencies of a project. When developing on your own machine, you
should be installing dependencies for a particular project within a virtual
environment – not globally.

If you develop against a project that has a `requirements.txt` but no `Pipfile` yet 
you can use `pipenv install -r requirements.txt` to generate the `Pipfile` and install
the dependencies.

## Project Ideas

**Note:** We have proposed both "data source" and "data exploration" projects. These
are not exclusive categories! One project could propose to both add *and*
analyze data! (If you'd like inspiration, check out the
[Twitter Archive Analyzer](http://www.twarxiv.org), which adds Twitter archive
data to Open Humans *and* analyzes it.)

-----

### Add new data sources
Members of *Open Humans* can [connect data and upload data from external resources](https://www.openhumans.org/add-data/)
into their accounts to share this data with other projects, research studies and individuals. Many of these
data imports are community curated. We are looking for students who are interested in contributing
new data sources. Write a data importer for your favorite sleep tracking, diet logging or
social media application.

Some data import ideas we had so far:
* RescueTime
* Google location history through Google Takeout
* Personal Facebook feed
* your personal idea!

These projects require rudimentary skills in web application design to connect to *Open Humans*.
Students will learn how to interface with the APIs of their data source as well as the Open Humans API. Additionally
students will become more familiar with building decentralized applications. This project can be mentored by
[Mad](https://github.com/madprime) and/or [Bastian](https://github.com/gedankenstuecke).

#### Contributing

Outreachy requires applicants to demonstrate skill and interest by making
one or more contributions to the project they're interested in.

To do so for this project, we ask you to try doing one or more of the following:

* Get one or both of these template "data source" projects running.
    * [oh_data_uploader](https://github.com/gedankenstuecke/oh_data_uploader)<br>
    Deposits a file uploaded by the user to their Open Humans account. Intended for simple
    addition of files as sources, designed to be easy to get working with minimal technical understanding of the underlying web app.
    * [oh-data-source-template](https://github.com/OpenHumans/oh-data-source-template)<br>
     Deposits a "lorem ipsum" text file to the user's Open Humans account. Intended to be a starter for a full data source integration, using celery for asynchronous processing
     (e.g. to run jobs that collate data from APIs).
* Share some code relevant to the data source your interested in adding (e.g. an example of pulling data the relevant API, or an example of scrubbing sensitive data from an uploaded file)
* Modify one of the template projects to improve it for other users.
* Modify one of the template projects to add some of the data source you're interested in.

-----

### Add Data Exploration projects
Members of *Open Humans* can use the different data sets they have connected to their account in various
data exploration tools. We are looking for students who are interested in contributing
new data exploration tools that access a member's data sets to generate interesting insights.
These can be in form of data visualization/analysis or generating derived new data sets.

Some data explorations ideas we had so far:
* Genetic ancestry interpretation
* Use time stamped GPS data & step counts to analyse how weather influences activity
* your personal idea!

These projects require rudimentary skills in web application design to connect to *Open Humans*.
Students will learn how to interface with the APIs of Open Humans. Additionally
students will become more familiar with building decentralized applications. This project can be mentored by
[Mad](https://github.com/madprime) and/or [Bastian](https://github.com/gedankenstuecke).

#### Contributing

Outreachy requires applicants to demonstrate skill and interest by making
one or more contributions to the project they're interested in.

To do so for this project, we ask you to try doing some or all of the following:

* [Create a project](https://www.openhumans.org/direct-sharing/projects/manage/)
in Open Humans that requests access to a data source you're interested in
analyzing. (In Slack, you can ask if anyone will join and share
their data with you!)
* [Follow this guide](https://github.com/OpenHumans/open-humans/wiki/Downloading-data-shared-with-your-project) to retrieve the data shared with you.
* Share "rough draft" code that produces a simple analysis of this data

-----

### Writing a stand-alone project admin backend
*Open Humans* is a modular eco system in which users can start their own projects
that can request data from users or put new data into the accounts of users.
These interactions are done largely through APIs. But for many basic administrative
works a graphical user interface would be good to have. Such a GUI
should be a stand-alone Django application that interfaces with the existing
Open Humans API methods. You can find
[more details in a corresponding GitHub issue](https://github.com/OpenHumans/open-humans/issues/690).

This project requires rudimentary skills in web application design and ideally some familiarity with Django/Python.
Students will learn how to interface with APIs and how build modular web applications. This project can be mentored by
[Mad](https://github.com/madprime) and/or [Bastian](https://github.com/gedankenstuecke).

#### Contributing

Outreachy requires applicants to demonstrate skill and interest by making
one or more contributions to the project they're interested in.

To do so for this project, we ask you to try setting up and contributing to this
bare-bones starting point for a project admin backend: [https://github.com/OpenHumans/oh-proj-management](https://github.com/OpenHumans/oh-proj-management)


**Feel free to propose your own entirely new idea by being in touch with us.**
