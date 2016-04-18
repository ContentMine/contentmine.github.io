---
layout: default
title: Mac OS X Installation
---
# Mac OS X Installation Procedure

## getpapers

### Installing Node

{% include node-from-nvm.md %}

To quote the NVM instructions:

> On OSX, if you get `nvm: command not found` after running the install script, your system may not have a [.bash_profile file] where the command is set up. Simple create one with touch ~/.bash_profile and run the install script again.

#### Alternative method using brew
Download npm and node using brew. See: [brew](http://brew.sh/)
    `brew install node`

### Install Getpapers

run `npm install getpapers` either as root or with sudo enabled

## norma
{% include norma-from-zip.md %}

## ami
{% include ami-from-zip.md %}

---

# Mac OS X Operating Procedure

## getpapers
{% include run-getpapers.md %}

## norma

{% include check-java-generic.md %}
{% include mac-install-java.md %}
{% include run-norma.md %}

## ami

{% include check-java-generic.md %}
{% include mac-install-java.md %}
{% include run-ami.md %}
