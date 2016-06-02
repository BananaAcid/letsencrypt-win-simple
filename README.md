# letsencrypt-win-simple
A Simple ACME Client for Windows + modifications

# Notable changes

Difference to creators branch:
- Added several plugins suggested to be used in master branch
- modified SAN plugin to take a comma seperated list of multiple targets (first one will be the main target which will work if SAN is not supported by client) 

# What is SAN

One Certificate for hosting multiple domain names on a single IP address

# NOTE:

Sometimes, the default web.config will case problems. Use the included alternative (or remove it).


# Overview

This is a ACME windows CLI client built in native .net and aims to be as simple as possible to use.

It's built on top of the [.net ACME protocol library](https://github.com/ebekker/ACMESharp).

# Wiki

Please head to the [Wiki](https://github.com/Lone-Coder/letsencrypt-win-simple/wiki) to learn more.

# Support

If you run into trouble please open an issue at https://github.com/Lone-Coder/letsencrypt-win-simple/issues

Please check to see if your issue is covered in the [Wiki](https://github.com/Lone-Coder/letsencrypt-win-simple/wiki) before you create a new issue.

If you ran the app and you got an error when it tried to Authorize your site take a look [here](https://github.com/Lone-Coder/letsencrypt-win-simple/wiki/web.config).

# Web.Config Pull Requests

If you submit a pull request that changes the included web.config file and it does not work on stock IIS 7.5 +, it will not be merged in. Instead add a section to the [WIki page](https://github.com/Lone-Coder/letsencrypt-win-simple/wiki/web.config) with your changes.
