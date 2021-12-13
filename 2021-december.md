# 4 cool new projects to try in COPR for July 2021

Copr is a build-system available for everybody in the Fedora
community. It hosts thousands of projects of various purpose and
quality, so keep that in mind when enabling a Copr repository.

People use Copr as a step towards getting their package into the
official repositories TODO



~~COPR is a [collection][copr] of personal repositories for software
that isn’t carried in Fedora. Some software doesn’t conform to
standards that allow easy packaging. Or it may not meet other Fedora
standards, despite being free and open-source. COPR can offer these
projects outside the Fedora set of packages. Software in COPR isn’t
supported by Fedora infrastructure or signed by the project. However,
it can be a neat way to try new or experimental software.~~

~~This article presents a few new and interesting projects in COPR. If
you’re new to using COPR, see the [COPR User Documentation][copr-docs]
for how to get started.~~



## Glow
[Glow][glow] is a markdown reader for your command-line. It
automatically discovers markdown files in git projects and
subdirectories but it is also possible to specify path to a local file
or an online URL when starting the program. Glow also provides
integration with the [Charm Cloud][charm-cloud] and allows to _stash_
files into your privete, end-to-end encrypted collection.

![Glow][glow-img]

### Installation instructions

The [repo][glow-copr] currently provides Glow for Fedora
33, 34, 35, and Fedora Rawhide. To install it, use these commands:

```
sudo dnf copr enable keefle/glow
sudo dnf install glow
```


## Purple-googlechat
Are you required to use Google Chat but you dislike the web-based
interface? The [purple-googlechat][purple-googlechat] plugin for
[Pidgin][pidgin] and many other chat programs might save you.


[Purple][purple] is a library for connecting into IM networks, and
this [purple-googlechat][purple-googlechat] plugin provides support
for Google Chat in your favorite chat program.

TODO Image

### Installation instructions

The [repo][purple-googlechat-copr] currently provides
_purple-googlechat_ for Fedora 34, 35, and Fedora Rawhide. To install
it, use these commands:

```
sudo dnf copr enable praiskup/purple-googlechat
sudo dnf install purple-googlechat
```


## TODO project 3


## TODO project 4



[copr]: https://copr.fedorainfracloud.org/
[copr-docs]: https://docs.pagure.org/copr.copr/user_documentation.html


[glow]: https://github.com/charmbracelet/glow
[glow-copr]: https://copr.fedorainfracloud.org/coprs/keefle/glow/
[glow-img]: img/glow.png
[charm-cloud]: https://www.charm.sh/


[purple-googlechat]: https://github.com/EionRobb/purple-googlechat
[purple-googlechat-copr]: https://copr.fedorainfracloud.org/coprs/praiskup/purple-googlechat/
[purple-googlechat-img]: #
[pidgin]: https://pidgin.im/
[purple]: https://developer.pidgin.im/wiki/WhatIsLibpurple
