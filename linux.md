---
layout: default
title: Linux Installation
---
# Linux Installation Procedure
## getpapers
1. Download npm and node using your package manager.
1. run `npm install --global getpapers` either as root or with sudo enabled

## norma
### With .deb
Install the .deb from [github](https://github.com/ContentMine/norma/releases) if on Debian or Ubuntu.

### Alternate method
We are in the process of preparing rpms.

You can also install manually using a zip file:
{% include norma-from-zip.md %}

---
# Linux Operating Procedure
## getpapers
{% include run-getpapers.md %}

## norma
{% include check-java-generic.md %}
You could either download and install packages on their website or prefereably use your package manager. For example `apt-get` or `yum` etc..
{% include run-norma.md %}

## ami
{% include check-java-generic.md %}
You could either download and install packages on their website or prefereably use your package manager. For example `apt-get` or `yum` etc..
{% include run-ami.md %}