# mq-patrol
A static-html "wiki" built using [Hugo](https://gohugo.io/), and hosted on Github-Pages.

This website was originally generated via a CMS, but has since been converted to static files for easy hosting. This repo was initially created with Hugo version 0.16, but has since been minimally updated to suit Hugo version 0.21. Thus, if you are looking over the Hugo relevant code, some of the setup may no longer be relevant.

* The `master` branch contains all the "source" files needed by Hugo. The websites "config" can be found in the `archetypes`, `layouts`, and `static` folders. The user-authored pages and attachments are located in the `content` folder.
* Hugo is then configured to publish the stand-alone website to the `.gh-pages` folder, which can then be uploaded to a separate `gh-pages` branch for hosting via Github-Pages.

FYI, the website in question is a wiki for the [160 Nissan Patrol](https://en.wikipedia.org/wiki/Nissan_Patrol#160) produced from 1980 to ~1988, and it can be viewed at [MQ-Patrol.com](http://www.mq-patrol.com/)
