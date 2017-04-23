# wonderproxy.com

This repo houses the WonderProxy website, associated scripts that make
everything work, and the WonderProxy API. It also holds the WonderAPI
docs source as a [git submodule](https://git-scm.com/docs/git-submodule).

## Contents

- [Initial Setup](#initial-setup) (Prereqs and Installation)
- [Day-to-Day Work](#day-to-day)
  - [Starting Work on a Ticket](#starting-work-on-a-ticket)
  - [CSS Updates](#css)
  - [PHP Updates](#php)
  - [JS Updates](#javascript)
  - [E-mail Template Updates](#e-mail-templating)
  - [API Docs Updates](#modifying-api-documentation)
- [Building for Prod](#build-wonderproxycom-for-production)
- [Styleguide Dev](#developing-the-styleguide)

## Initial Setup

WonderProxy uses [Compass](http://compass-style.org/) to compile our
CSS,
[PHP_CodeSniffer](https://github.com/squizlabs/PHP_CodeSniffer/) to
check our coding style against a standard, and   
[Grunt](http://gruntjs.com) to automate compilation and minification.