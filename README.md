### Hi there

I am a software engineer, and I've been contributing to open source projects for 20+ years.
My open source repositories include:
- [WebCalendar](https://github.com/craigk5n/webcalendar): PHP 8 LAMP multi-user calendar with a long history of support.
  I have had many code contributions to WebCalendar over the years and can only claim to have authored about half the code.
  There are also over [30 translations](https://github.com/craigk5n/webcalendar/tree/master/translations).
- [Cliquetool](https://github.com/craigk5n/cliquetool): Multi-purpose tool written in Go for finding cliques within a graph,
  building dense groups from the cliques and generating reports on the results.
- [ilibgo](https://github.com/craigk5n/ilibgo): Golang library for reading, writing, and manipulating images with API loosely
  based on [X11 API](https://x.org/releases/current/doc/libX11/libX11/libX11.html) and utilizing any
  [X11 BDF font](https://x.org/releases/X11R7.7/doc/xorg-docs/fonts/fonts.html) for writing text.
  This is a Go port of my C library (listed below).

And older stuff that is not really maintained anymore:
- [Java Calendar Tools](https://github.com/craigk5n/javacaltools): Java library for parsing and generating
  iCalendar ([RFC 2445](https://www.rfc-editor.org/rfc/rfc2445.html)) data
- [k5nCal](https://github.com/craigk5n/k5ncal): Desktop calendar application written in Java
- [GTimer](https://github.com/craigk5n/gtimer): Linux GTK application for timing how much time you spend on various projects
- [Ilib](https://github.com/craigk5n/ilib): C library for reading, writing, and manipulating images with API loosely
  based on [X11 API](https://x.org/releases/current/doc/libX11/libX11/libX11.html) and utilizing any
  [X11 BDF font](https://x.org/releases/X11R7.7/doc/xorg-docs/fonts/fonts.html) for writing text

Other projects/repos I have contributed to:
- [CVE services](https://github.com/craigk5n/cve-services): I've contributed to the REST API
  for MITRE's CVE project while I worked at MITRE.  My [primary contributions](https://github.com/CVEProject/cve-services/pulls?q=author%3Acraigk5n)
  have related to containerizing the NodeJS app.  (I also set up the CI/CD pipeline in AWS CodePipeline, but that's
  not on GitHub.)

I'm currently working on:
- I have updated WebCalendar's UI to use Bootstrap and jQuery.  It was previously using some very old custom HTML/CSS
  and a mix of JS tools (Prototype.js and others).  This work is now in the main branch and part of the v1.9.X releases.
  I also rewrote the web-based installer and updated everything for PHP 8.
- Teaching myself Golang.  My first Go code on Github was the [cliquetool](https://github.com/craigk5n/cliquetool)
  project.  The project deals with 
  [cliques](https://en.wikipedia.org/wiki/Clique_problem) in
  a sparsely populated undirected graph based on some work I did years ago in C.
  My example data set includes a list of NCAA basketball games from a single season.
  The goal was to determine the conference affiliations for all teams based on
  the list of games.  (Note that in college basketball, each team within a conference generally plays
  each other team at least once.  This is not true in college football where teams often play a
  subset of the other teams within their conference.)

You can look me up on:
- [LinkedIn](https://www.linkedin.com/in/cknudsen/)
- [kn5.us](https://www.k5n.us)

Reach me at:
- craig AT k5n.us

Interesting facts:
- My first open source contribution was a system menubar for HP-UX, SunOS, AIX and OSF/1 that I released
  in 1995 called xapplaunch (still online [here](https://distro.ibiblio.org/amigolinux/download/XApps/xapplaunch-1.1afx/)) by placing the source code on a public FTP server.
  Note that the term "open source" was not established until
  [a few years later in 1998](https://opensource.org/faq).
