Open Source Knitting
=================

On this page you find an overview of [FOSSASIA][fossasia] Open Source Knitting Projects and you start to [get involved][how-to-contribute]. You can also can [get in touch with us :)][get-in-touch] and check out other [projects][related-work] working on Open Source knitting.

- [Knitting Projects][project-list]
  - [kniteditor][kniteditor]
  - [knittingpattern][knittingpattern]
  - [AYABInterface][AYABInterface]
  - [circle-knitting][circle-knitting]
- [How to Contribute][how-to-contribute]
- [Related Work][related-work]
- [Outdated Projects][outdated-projects]

Knitting Projects
-------------------------

### kniteditor

The Knit Editor is an editor for the knit exchange format. It allows [creating digital knit works][knittingpattern] from images and knitting it with several knitting machines. This kniteditor is developed together with [All Yarns Are Beautiful][ayab]. You can [download the releases][kniteditor-releases] and install them.

**Read about the project:**

- [blog post about this project][kniteditor-blog-overview].

**Repository:** [GitHub][kniteditor-repo]

**Tutorials:**[Videos on YouTube][tutorial-videos]

**Contribute:**
[![Issues Ready to Work on][kniteditor-waffle-badge]][kniteditor-waffle]
[![Read the Documentation][kniteditor-rtd-badge]][kniteditor-rtd]
[![Travis Build Status][kniteditor-travis-badge]][kniteditor-travis]
[![AppVeyor Build Status][kniteditor-appveyor-badge]][kniteditor-appveyor]
[![Code Climate][kniteditor-codeclimate-badge]][kniteditor-codeclimate]
[![Test Coverage][kniteditor-test-coverage-badge]][kniteditor-test-coverage]
[![Code Issue Count][kniteditor-issue-count-badge]][kniteditor-issue-count]
[![Code Health][kniteditor-landscape-badge]][kniteditor-landscape]
[![Python Package Index Version][kniteditor-pypi-badge]][kniteditor-pypi]

**Related Projects:** [knittingpattern][knittingpattern], [AYABInterface][AYABInterface]

--

### knittingpattern

The `knittingpattern` is a Python library for an exchange format for knit work.
It allows specifying how to knit a particular piece of work.

**Read about the project:**

- [blog post about this project][knittingpattern-blog-conversion].

**Repository:** [GitHub][knittingpattern-repo]

**Tutorial:** [Videos on YouTube][tutorial-videos]

**Contribute:**
[![Issues Ready to Work on][knittingpattern-waffle-badge]][knittingpattern-waffle]
[![Read the Documentation][knittingpattern-rtd-badge]][knittingpattern-rtd]
[![Travis Build Status][knittingpattern-travis-badge]][knittingpattern-travis]
[![AppVeyor Build Status][knittingpattern-appveyor-badge]][knittingpattern-appveyor]
[![Code Climate][knittingpattern-codeclimate-badge]][knittingpattern-codeclimate]
[![Test Coverage][knittingpattern-test-coverage-badge]][knittingpattern-test-coverage]
[![Code Issue Count][knittingpattern-issue-count-badge]][knittingpattern-issue-count]
[![Code Health][knittingpattern-landscape-badge]][knittingpattern-landscape]
[![Python Package Index Version][knittingpattern-pypi-badge]][knittingpattern-pypi]

**Related Projects:** [AYABInterface][AYABInterface], [kniteditor][kniteditor]

---

### AYABInterface [![View on Github][github-logo]][AYABInterface-repo]

The `AYABInterface` is used by the [Knit Editor][kniteditor] to
convert [knittingpatterns][knittingpattern] into machine instructions.
It can be used standalone without these other projects. You can

**Read about the project:**

- [blog post about this project][AYABInterface-blog]
- [The new AYABInterface module][AYABInterface-blog-new-module]

**Repository:** [GitHub][AYABInterface-repo]

**Tutorial:** [Tutorial Videos][tutorial-videos],

**Contribute:**
[![Issues Ready to Work on][AYABInterface-waffle-badge]][AYABInterface-waffle]
[![Read the Documentation][AYABInterface-rtd-badge]][AYABInterface-rtd]
[![Travis Build Status][AYABInterface-travis-badge]][AYABInterface-travis]
[![AppVeyor Build Status][AYABInterface-appveyor-badge]][AYABInterface-appveyor]
[![Code Climate][AYABInterface-codeclimate-badge]][AYABInterface-codeclimate]
[![Test Coverage][AYABInterface-test-coverage-badge]][AYABInterface-test-coverage]
[![Code Issue Count][AYABInterface-issue-count-badge]][AYABInterface-issue-count]
[![Code Health][AYABInterface-landscape-badge]][AYABInterface-landscape]
[![Python Package Index Version][AYABInterface-pypi-badge]][AYABInterface-pypi]
[![Python Package Index Downloads][AYABInterface-pypi-downloads-badge]][AYABInterface-pypi-downloads]

**Related Projects:** [knittingpattern][knittingpattern], [kniteditor][kniteditor]

---

### circle-knitting [![View on Github][github-logo]][circle-knitting-repo]

The goal of this project is to develop a knitting machine that is entirely made from plastic. An enhanced model can include a micro PC that can control the machine using our Open Source knitting software. This project can enable people to print out a plastic on a 3D printer. 
This project implements the idea to code a circular knitting machine. 

**Repository:** [GitHub][circle-knitting-repo]

**Contribute:**
[![Issues Ready to Work on][circle-knitting-waffle-badge]][circle-knitting-waffle]

---

How to Contribute
-----------------

**Translate**

A majority of people on earth do not speak English. By translating software, you make it accessible to thousands of people. You can add translations to these projects:

- [kniteditor][kniteditor]
  - [A video on how to translate][kniteditor-translate-video]
  - [Blogpost about localization implementation][kniteditor-blog-kivy-revelations]

**Improve Metrics**

Improving code metrics requires coding but not the understanding of how the code works. You learn how to set up this specific environment, fix some code and while doing this, you read it and get familiar with it. When your pull request is merged, you have contributed to the health of the project. Some of the repositories have code metrics like code coverage and code quality. They can be improved easily. E.g. in [this example][improve-metrics-example] you can find this error:

     	        bbox = list(map(lambda f: f*zoom, layout.bounding_box))
	    missing whitespace around arithmetic operator

This can fix this by adding spaces around the operator. 

**Solve Issues**

All the projects have "issues" attached to them. They show bugs and feature requests. A solved issue improves the life of somebody on earth. When solving the issue, you are introduced to the development process of the project and learn how to adapt the project to your needs. Issues can be found in the issue tracker of github. The badge above links to the overview of all listed projects. If you find an issue which interests you, please comment that you would like to work on it. This way, you get help and it is not done twice. Code should be documented and tested. Consider trying out [documentation driven development][ddd], [Test-First][test-first] and [test-driven development][tdd].


---

Related Work
------------

This section contains links and related projets and work in the field of knitting. Other overview sites are listed here. The objective is to ease exploring the network of people and projects.

- [Community Connections](https://github.com/AllYarnsAreBeautiful/ayab-desktop/wiki/Community-Connections)
- [Blogpost about Designaknit](http://blog.fossasia.org/designaknit/)


---

Get in Touch
------------

[FOSSASIA][fossasia] has a [Slack][slack] to chat in the community. You can use the main channel or **#knitting**. You can contact me directly. I started this site. You can find me on [github][github-niccokunzmann] and [Slack][slack] under the name "niccokunzmann". 

There is a [mailing list for knitting applications][mailing-list] such as [these listed][project-list]. You can also join the [FOSSASIA mailing list][fossasia-mailing-list].

You can comment on issues and through these reach the developers directly. We have a Gitter chat which you can join: [![Join the chat at https://gitter.im/fashiontec/knitapps][gitter-svg]][gitter]

---

Outdated Projects
-----------------

These projects are a bit older, obsolete or not maintained any more.

### knitpat

`knitpat` contains a pattern definition format for knit work.
It is the predecessor of the [`knittingpattern`][knittingpattern] library.

### knitserver

Knitserver is a [Knitlib][knitlib] client that provides REST API endpoints for knitting machine software and control.
Knitserver is designed to interact with [Knitweb][knitweb]. Repository: [GitHub][knitserver-repo]

### knitweb

[`knitweb`][knitweb-repo] is an app frontend and backend that works together with the [`knitlib`][knitlib] server and uses the [`knitpat`][knitpat] format. Repository: [GitHub][knitweb-repo]

### knitlib

Knitlib is a library designed to support the operation of varied knitting machines, mechanisms, and hacks. Knitlib is based on projects like [AYAB][ayab], PDD, and KnitterStream to control knitting machines. Knitlib features a plugin system for knitting machines and implements an API to control machines' operation, knitting jobs and knitting patterns. The software is based on Python. There also is a Web API. Among the primary tasks is to develop plugins based on this solution to add support for more machines. Repository: [GitHub][knitlib-repo]

---


To edit [website][this-site] or [add new entries][knitting.fossasia.org-edit] visit the [Repository][knitting.fossasia.org-repo]











[top]: #knitting-projects
[project-list]: #list-of-knitting-projects
[outdated-projects]: #outdated-projects
[this-site]: https://knitting.fossasia.org
[ayab]: http://ayab-knitting.com/
[related-work]: #related-work
[fossasia]: https://fossasia.org
[mailing-list]: https://groups.google.com/forum/#!forum/knitapps
[how-to-contribute]: #how-to-contribute
[translate]: #translate
[improve-metrics]: #improve-metrics
[improve-metrics-example]: https://landscape.io/github/fossasia/knittingpattern/187/messages/style
[ddd]: http://niccokunzmann.github.io/blog/2016-06-10/Documentation-Driven-Development
[test-first]: http://www.extremeprogramming.org/rules/testfirst.html
[tdd]: https://en.wikipedia.org/wiki/Test-driven_development
[get-in-touch]: #get-in-touch
[solve-issues]: #solve-issues
[links]: #links
[slack]: http://fossasia-slack.herokuapp.com/
[fossasia-mailing-list]: https://groups.google.com/forum/#!forum/fossasia
[labs]: http://labs.fossasia.org/
[tutorial-videos]: https://www.youtube.com/playlist?list=PL_bQhtrnWFA8skye4GpQ2Y8kEHxLwQKHY
[github-niccokunzmann]: https://github.com/niccokunzmann
[beginners]: #for-beginners
[git-guide]: https://rogerdudler.github.io/git-guide/index.html
[try-github]: https://try.github.io
[vcs]: https://en.wikipedia.org/wiki/Version_control
[gitter-svg]: https://badges.gitter.im/Join%20Chat.svg
[gitter]: https://gitter.im/fashiontec/knitapps?utm_source=badge&utm_medium=badge&utm_campaign=pr-badge&utm_content=badge


[kniteditor]: #kniteditor-
[kniteditor-repo]: https://github.com/fossasia/kniteditor
[kniteditor-waffle]: http://waffle.io/fossasia/kniteditor
[kniteditor-waffle-badge]: https://badge.waffle.io/fossasia/kniteditor.svg?label=ready&title=Ready "Issues Ready to Work on"
[kniteditor-travis]: https://travis-ci.org/fossasia/kniteditor
[kniteditor-travis-badge]: https://travis-ci.org/fossasia/kniteditor.svg "Travis Build Status"
[kniteditor-appveyor]: https://ci.appveyor.com/project/AllYarnsAreBeautiful/kniteditor
[kniteditor-appveyor-badge]: https://ci.appveyor.com/api/projects/status/yildjtxp8an3vejx?svg=true "AppVeyor Build Status"
[kniteditor-codeclimate]: https://codeclimate.com/github/fossasia/kniteditor
[kniteditor-codeclimate-badge]: https://codeclimate.com/github/fossasia/kniteditor/badges/gpa.svg "Code Climate"
[kniteditor-test-coverage]: https://codeclimate.com/github/fossasia/kniteditor/coverage
[kniteditor-test-coverage-badge]: https://codeclimate.com/github/fossasia/kniteditor/badges/coverage.svg "Test Coverage"
[kniteditor-issue-count]: https://codeclimate.com/github/fossasia/kniteditor
[kniteditor-issue-count-badge]: https://codeclimate.com/github/fossasia/kniteditor/badges/issue_count.svg "Code Issue Count"
[kniteditor-pypi]: https://pypi.python.org/pypi/kniteditor
[kniteditor-pypi-badge]: https://badge.fury.io/py/kniteditor.svg "Python Package Index Version"
[kniteditor-pypi-downloads]: https://pypi.python.org/pypi/kniteditor#downloads
[kniteditor-pypi-downloads-badge]: https://img.shields.io/pypi/dm/kniteditor.svg "Python Package Index Downloads"
[kniteditor-rtd]: https://kniteditor.readthedocs.org
[kniteditor-rtd-badge]: https://readthedocs.org/projects/kniteditor/badge/?version=latest "Read the Documentation"
[kniteditor-landscape]: https://landscape.io/github/fossasia/kniteditor/master
[kniteditor-landscape-badge]: https://landscape.io/github/fossasia/kniteditor/master/landscape.svg?style=flat "Code Health"
[kniteditor-releases]: https://github.com/fossasia/kniteditor/releases
[kniteditor-translate-video]: https://www.youtube.com/watch?v=9M4y_dUpoeg
[kniteditor-blog-overview]: http://blog.fossasia.org/knit-editor-package-overview/
[kniteditor-blog-kivy-revelations]: http://blog.fossasia.org/awesome-kivy-revelations/



[knittingpattern]: #knittingpattern-
[knittingpattern-repo]: https://github.com/fossasia/knittingpattern
[knittingpattern-waffle]: http://waffle.io/fossasia/knittingpattern
[knittingpattern-waffle-badge]: https://badge.waffle.io/fossasia/knittingpattern.svg?label=ready&title=Ready "Stories in Ready"
[knittingpattern-travis]: https://travis-ci.org/fossasia/knittingpattern
[knittingpattern-travis-badge]: https://travis-ci.org/fossasia/knittingpattern.svg "Travis Build Status"
[knittingpattern-appveyor]: https://ci.appveyor.com/project/AllYarnsAreBeautiful/knittingpattern
[knittingpattern-appveyor-badge]: https://ci.appveyor.com/api/projects/status/c1983ovsc8thlhvi?svg=true "AppVeyor Build Status"
[knittingpattern-codeclimate]: https://codeclimate.com/github/fossasia/knittingpattern
[knittingpattern-codeclimate-badge]: https://codeclimate.com/github/fossasia/knittingpattern/badges/gpa.svg "Code Climate"
[knittingpattern-test-coverage]: https://codeclimate.com/github/fossasia/knittingpattern/coverage
[knittingpattern-test-coverage-badge]: https://codeclimate.com/github/fossasia/knittingpattern/badges/coverage.svg "Test Coverage"
[knittingpattern-issue-count]: https://codeclimate.com/github/fossasia/knittingpattern
[knittingpattern-issue-count-badge]: https://codeclimate.com/github/fossasia/knittingpattern/badges/issue_count.svg "Code Issue Count"
[knittingpattern-pypi]: https://pypi.python.org/pypi/knittingpattern
[knittingpattern-pypi-badge]: https://badge.fury.io/py/knittingpattern.svg "Python Package Index Version"
[knittingpattern-pypi-downloads]: https://pypi.python.org/pypi/knittingpattern#downloads
[knittingpattern-pypi-downloads-badge]: https://img.shields.io/pypi/dm/knittingpattern.svg "Python Package Index Downloads"
[knittingpattern-rtd]: https://knittingpattern.readthedocs.org
[knittingpattern-rtd-badge]: https://readthedocs.org/projects/knittingpattern/badge/?version=latest "Read the Documentation"
[knittingpattern-landscape]: https://landscape.io/github/fossasia/knittingpattern/master
[knittingpattern-landscape-badge]: https://landscape.io/github/fossasia/knittingpattern/master/landscape.svg?style=flat "Code Health"
[knittingpattern-blog-conversion]: http://blog.fossasia.org/knitting-pattern-conversion/


[AYABInterface]: #ayabinterface-
[AYABInterface-repo]: https://github.com/fossasia/AYABInterface
[AYABInterface-waffle]: http://waffle.io/fossasia/AYABInterface
[AYABInterface-waffle-badge]: https://badge.waffle.io/fossasia/AYABInterface.svg?label=ready&title=Ready "Stories in Ready"
[AYABInterface-travis]: https://travis-ci.org/fossasia/AYABInterface
[AYABInterface-travis-badge]: https://travis-ci.org/fossasia/AYABInterface.svg "Travis Build Status"
[AYABInterface-appveyor]: https://ci.appveyor.com/project/AllYarnsAreBeautiful/AYABInterface
[AYABInterface-appveyor-badge]: https://ci.appveyor.com/api/projects/status/a6yhbt0rqvb212s7?svg=true "AppVeyor Build Status"
[AYABInterface-codeclimate]: https://codeclimate.com/github/fossasia/AYABInterface
[AYABInterface-codeclimate-badge]: https://codeclimate.com/github/fossasia/AYABInterface/badges/gpa.svg "Code Climate"
[AYABInterface-test-coverage]: https://codeclimate.com/github/fossasia/AYABInterface/coverage
[AYABInterface-test-coverage-badge]: https://codeclimate.com/github/fossasia/AYABInterface/badges/coverage.svg "Test Coverage"
[AYABInterface-issue-count]: https://codeclimate.com/github/fossasia/AYABInterface
[AYABInterface-issue-count-badge]: https://codeclimate.com/github/fossasia/AYABInterface/badges/issue_count.svg "Code Issue Count"
[AYABInterface-pypi]: https://pypi.python.org/pypi/AYABInterface
[AYABInterface-pypi-badge]: https://badge.fury.io/py/AYABInterface.svg "Python Package Index Version"
[AYABInterface-pypi-downloads]: https://pypi.python.org/pypi/AYABInterface#downloads
[AYABInterface-pypi-downloads-badge]: https://img.shields.io/pypi/dm/AYABInterface.svg "Python Package Index Downloads"
[AYABInterface-rtd]: https://AYABInterface.readthedocs.org
[AYABInterface-rtd-badge]: https://readthedocs.org/projects/AYABInterface/badge/?version=latest "Read the Documentation"
[AYABInterface-landscape]: https://landscape.io/github/fossasia/AYABInterface/master
[AYABInterface-landscape-badge]: https://landscape.io/github/fossasia/AYABInterface/master/landscape.svg?style=flat "Code Health"
[AYABInterface-blog]: http://blog.fossasia.org/ayabinterface-a-python-module-for-the-ayab-shield/
[AYABInterface-blog-new-module]: http://blog.fossasia.org/the-new-ayabinterface-module/


[knitting.fossasia.org]: #knittingfossasiaorg-
[knitting.fossasia.org-repo]: https://github.com/fossasia/knitting.fossasia.org
[knitting.fossasia.org-waffle]: http://waffle.io/fossasia/knitting.fossasia.org
[knitting.fossasia.org-waffle-badge]: https://badge.waffle.io/fossasia/knitting.fossasia.org.svg?label=ready&title=Ready "Stories in Ready"
[knitting.fossasia.org-edit]: https://github.com/fossasia/knitting.fossasia.org/edit/gh-pages/README.md
[knitting.fossasia.org-blogpost]: http://blog.fossasia.org/new-landing-page-for-fossasia-knitting-projects/


[knitweb]: #knitweb-
[knitweb-repo]: https://github.com/fossasia/knitweb
[knitweb-waffle]: http://waffle.io/fossasia/knitweb
[knitweb-waffle-badge]: https://badge.waffle.io/fossasia/knitweb.svg?label=ready&title=Ready "Stories in Ready"
[knitweb-travis]: https://travis-ci.org/fossasia/knitweb
[knitweb-travis-badge]: https://travis-ci.org/fossasia/knitweb.svg "Travis Build Status"
[knitweb-blog-functionality]: http://blog.fossasia.org/author/sameera1234/
[knitweb-blog-localization]: http://blog.fossasia.org/knitweb-localization/



[circle-knitting]: #circle-knitting-
[circle-knitting-repo]: https://github.com/fossasia/circle-knitting
[circle-knitting-waffle]: http://waffle.io/fossasia/circle-knitting
[circle-knitting-waffle-badge]: https://badge.waffle.io/fossasia/circle-knitting.svg?label=ready&title=Ready "Stories in Ready"
[circle-knitting-website]: https://fashiontec.wordpress.com/



[knitlib]: #knitlib-
[knitlib-repo]: https://github.com/fossasia/knitlib
[knitlib-waffle]: http://waffle.io/fossasia/knitlib
[knitlib-waffle-badge]: https://badge.waffle.io/fossasia/knitlib.svg?label=ready&title=Ready "Stories in Ready"
[knitlib-travis]: https://travis-ci.org/fossasia/knitlib
[knitlib-travis-badge]: https://travis-ci.org/fossasia/knitlib.svg "Travis Build Status"
[knitlib-rtd]: https://knitlib.readthedocs.org
[knitlib-rtd-badge]: https://readthedocs.org/projects/knitlib/badge/?version=latest "Read the Documentation"
[knitlib-blog-exception-handler]: http://blog.fossasia.org/exception-handler-in-knitlib/
[knitlib-blog-machine-abstraction]: http://blog.fossasia.org/knitting-machine-abstractions-for-knitlib/
[knitlib-blog-importance-testcases]: http://blog.fossasia.org/importance-of-the-test-cases-for-the-knitlib/



[knitserver]: #knitserver-
[knitserver-repo]: https://github.com/fossasia/knitserver
[knitserver-waffle]: http://waffle.io/fossasia/knitserver
[knitserver-waffle-badge]: https://badge.waffle.io/fossasia/knitserver.svg?label=ready&title=Ready "Stories in Ready"



[knitapps]: #knitapps-
[knitapps-repo]: https://github.com/fossasia/knitapps
[knitapps-waffle]: http://waffle.io/fossasia/knitapps
[knitapps-waffle-badge]: https://badge.waffle.io/fossasia/knitapps.svg?label=ready&title=Ready "Stories in Ready"



[knitpat]: #knitpat-
[knitpat-repo]: https://github.com/fossasia/knitpat
[knitpat-waffle]: http://waffle.io/fossasia/knitpat
[knitpat-waffle-badge]: https://badge.waffle.io/fossasia/knitpat.svg?label=ready&title=Ready "Stories in Ready"



[ayab-apparat]: #ayab-apparat-
[ayab-apparat-fork]: https://github.com/allyarnsarebeautiful/ayab-desktop
[ayab-apparat-repo]: https://bitbucket.org/chris007de/ayab-apparat
[ayab-apparat-waffle]: http://waffle.io/allyarnsarebeautiful/ayab-apparat
[ayab-apparat-waffle-badge]: https://badge.waffle.io/allyarnsarebeautiful/ayab-apparat.svg?label=ready&title=Ready "Stories in Ready"


[github-logo]: images/GitHub.png "View on Github"
