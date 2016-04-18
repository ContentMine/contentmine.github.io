---
layout: default
title: Linux Installation
---
# Linux Installation Procedure

## getpapers
Download npm and node using your package manager.

> On Ubuntu and Debian npm come packaged with the `nodejs` package. You must also install `nodejs-legacy` to get the executable named `node`.

run `npm install --global getpapers` either as root or with sudo enabled

You can check it has worked by moving on to the 'Operating Procedure' below.

## norma

### With .deb
Install the .deb from [github](https://github.com/ContentMine/norma/releases) if on Debian or Ubuntu.

> this is done by downloading to a place of your chosing and running `dpkg -i <path to .deb>`

### Alternate method
We are in the process of preparing rpms.

You can also install manually using a zip file:
{% include norma-from-zip.md %}

## ami

### With .deb
Install the .deb from [github](https://github.com/ContentMine/ami/releases) if on Debian or Ubuntu.

> this is done by downloading to a place of your chosing and running `dpkg -i <path to .deb>`

### Alternate method
We are in the process of preparing rpms.

You can also install manually using a zip file:
{% include ami-from-zip.md %}

---

# Linux Operating Procedure

## getpapers
{% include run-getpapers.md %}

## norma
{% include check-java-generic.md %}
You could either download and install packages on their website or preferably use your package manager. For example `apt-get` or `yum` etc..
{% include run-norma.md %}

## ami
{% include check-java-generic.md %}
You could either download and install packages on their website or preferably use your package manager. For example `apt-get` or `yum` etc..
{% include run-ami.md %}
