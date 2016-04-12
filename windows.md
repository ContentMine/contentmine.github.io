---
layout: default
title: Windows Installation
---
# Windows Installation Procedure

## getpapers
1. Download Node.Js from [here](https://nodejs.org/en/download/).
1. Open the windows command prompt by pressing Win-R and typing ```cmd```
1. type npm install --global getpapers

## norma

{% include check-java-generic.md %}

### Using chocolatey
The preferred installation method is using chocolatey:

{% include install-chocolatey.md %}

```choco install norma -s  https://www.myget.org/F/contentmine/api/v2 -y```

### Alternate method from zip

There are binary installers available from these sources
{% include norma-from-zip.md %}

## ami

{% include check-java-generic.md %}

### Using chocolatey
The preferred installation method is using chocolatey:

{% include install-chocolatey.md %}

```choco install ami -s  https://www.myget.org/F/contentmine/api/v2 -y```

### Alternate method from zip

There are binary installers available from these sources

{% include ami-from-zip.md %}

---

# Windows Operating Procedure

## getpapers
{% include run-getpapers.md %}

## norma
{% include run-norma.md %}

## ami
{% include run-ami.md %}
