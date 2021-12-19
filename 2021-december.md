# 4 cool new projects to try in COPR for July 2021

[Copr][copr] is a build-system for anyone in the Fedora community. It
hosts thousands of projects for various purposes and audiences. Some
of them should never be installed by anyone, some are already being
transitioned to the official Fedora Linux repositories. Copr gives you
the opporunity to install 3rd party software that is not available in
Fedora Linux repositories, try nightly versions of your dependencies,
use patched builds of your favorite tools to support some non-standard
use-case, and to just experiment freely.

If you don't know [how to enable a repository][copr-docs-enable] or if
you are concerned about whether
[is it safe to use Copr][copr-docs-security], please consult the
[project documentation][copr-docs].

This article takes a closer look at some interesting projects that
recently landed in Copr.


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
34, 35, and Fedora Rawhide. To install it, use these commands:

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

![Google Chat in Pidgin][purple-googlechat-img]

### Installation instructions

The [repo][purple-googlechat-copr] currently provides
_purple-googlechat_ for Fedora 34, 35, and Fedora Rawhide. To install
it, use these commands:

```
sudo dnf copr enable praiskup/purple-googlechat
sudo dnf install purple-googlechat
```


## Git-insight
[Git-insight][git-insight] renders colorful graphs for git repository
statistics. The output is comparable to what GitHub shows on the
Insights tab but in the command-line and not limited to any git
forge. It allows you to easily see the top contributors for a
repository, the most frequently updated files, commits in each branch,
all time trends, and more.

![Git-insight][git-insight-img]

### Installation instructions

The [repo][git-insight-copr] currently provides
_git-insight_ for Fedora 34, 35, and Fedora Rawhide. To install
it, use these commands:

```
sudo dnf copr enable avimehenwal/git-insight
sudo dnf install git-insight
```


## Nightly buids

This time we have something completely different but well representing
one of the main Copr use-cases. That is development (or nightly)
versions of packages, that are normally in the official Fedora Linux
repositories. This may be interesting if you want to try the most
recent version of some software to see if a particular bug was fixed
or that a new feature behaves as expected. Also, for software
developers it may be useful to test their software against the most
up-to-date dependencies

Many projects builds their nightly versions in Copr, namely
[Dnf][dnf-copr], [Mock][mock-copr], [Firefox][firefox-copr],
[PipeWire][pipewire-copr], [FreeCAD][freecad-copr],
[KiCad][kicad-copr], [AwesomeWM][awesomewm-copr],
[Noevim][neovim-copr], [MicroShift][microshift-copr], and many, many more.


![Nightly builds][nightly-builds]


[copr]: https://copr.fedorainfracloud.org/
[copr-docs]: https://docs.pagure.org/copr.copr/user_documentation.html
[copr-docs-enable]: https://docs.pagure.org/copr.copr/user_documentation.html#how-to-enable-copr-repository
[copr-docs-security]: https://docs.pagure.org/copr.copr/user_documentation.html#is-it-safe-to-use-copr


[glow]: https://github.com/charmbracelet/glow
[glow-copr]: https://copr.fedorainfracloud.org/coprs/keefle/glow/
[glow-img]: img/glow.png
[charm-cloud]: https://www.charm.sh/


[purple-googlechat]: https://github.com/EionRobb/purple-googlechat
[purple-googlechat-copr]: https://copr.fedorainfracloud.org/coprs/praiskup/purple-googlechat/
[purple-googlechat-img]: img/purple-googlechat.png
[pidgin]: https://pidgin.im/
[purple]: https://developer.pidgin.im/wiki/WhatIsLibpurple


[git-insight]: https://github.com/avimehenwal/git-insight
[git-insight-copr]: https://copr.fedorainfracloud.org/coprs/avimehenwal/git-insight
[git-insight-img]: img/git-insight.png


[dnf-copr]: https://copr.fedorainfracloud.org/coprs/rpmsoftwaremanagement/dnf-nightly/
[mock-copr]: https://copr.fedorainfracloud.org/coprs/g/mock/mock/
[firefox-copr]: https://copr.fedorainfracloud.org/coprs/proletarius101/firefox-nightly/
[pipewire-copr]: https://copr.fedorainfracloud.org/coprs/mfrey/pipewire-nightly/
[freecad-copr]: https://copr.fedorainfracloud.org/coprs/g/freecad/nightly/
[kicad-copr]: https://copr.fedorainfracloud.org/coprs/bearzeng/kicad-nightly/
[awesomewm-copr]: https://copr.fedorainfracloud.org/coprs/jcrd/awesome-nightly/
[neovim-copr]:  https://copr.fedorainfracloud.org/coprs/agriffis/neovim-nightly/
[microshift-copr]: https://copr.fedorainfracloud.org/coprs/g/redhat-et/microshift-nightly/
