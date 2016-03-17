---
layout: default
title: Mac OS X Installation
---
# Mac OS X Installation Procedure
## getpapers
1. Download npm and node using brew. See: [brew](http://brew.sh/)
    `brew install node`
1. run `npm install --global getpapers` either as root or with sudo enabled

## norma
{% include norma-from-zip.md %}

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