# 4 cool new projects to try in COPR for March 2023

[Copr][copr] is a build-system for anyone in the Fedora community. It
hosts thousands of projects for various purposes and audiences. Some
of them should never be installed by anyone, some are already being
transitioned to the official Fedora Linux repositories, and the rest
is somewhere in between. Copr gives you the opportunity to install 3rd
party software that is not available in Fedora Linux repositories, try
nightly versions of your dependencies, use patched builds of your
favorite tools to support some non-standard use-cases, and just
experiment freely.

If you don't know [how to enable a repository][copr-docs-enable] or if
you are concerned about whether
[is it safe to use Copr][copr-docs-security], please consult the
[project documentation][copr-docs].

This article takes a closer look at interesting projects that recently
landed in Copr.


## Sticky

TODO

Please don't use it for passwords

![Sticky][sticky-img]

### Installation instructions

The [repo][sticky-copr] currently provides Sticky for Fedora
36, 37, 38, and Fedora Rawhide. To install it, use these commands:

```
sudo dnf copr enable a-random-linux-lover/sticky
sudo dnf install sticky
```


## Webapp-manager

TODO

![webapp-manager][webapp-manager-img]

### Installation instructions

The [repo][webapp-manager-copr] currently provides webapp-manager for
Fedora 36, 37, 38, and Fedora Rawhide. To install it, use these
commands:

```
sudo dnf copr enable kylegospo/webapp-manager
sudo dnf install webapp-manager
```


## Umoria

TODO

![Umoria][umoria-img]

### Installation instructions

The [repo][umoria-copr] currently provides Umoria for Fedora
36, 37, 38, and Fedora Rawhide. To install it, use these commands:

```
sudo dnf copr enable whitehara/umoria
sudo dnf install umoria
```


## PyCharm

TODO

![pycharm][pycharm-img]

### Installation instructions

The [repo][pycharm-copr] currently provides PyCharm for
Fedora 36, 37, 38, Fedora Rawhide, EPEL 7, 8, and 9. To install it,
use these commands:

```
sudo dnf copr enable phracek/PyCharm
sudo dnf install pycharm-community
```



[copr]: https://copr.fedorainfracloud.org/
[copr-docs]: https://docs.pagure.org/copr.copr/user_documentation.html
[copr-docs-enable]: https://docs.pagure.org/copr.copr/how_to_enable_repo.html#how-to-enable-repo
[copr-docs-security]: https://docs.pagure.org/copr.copr/user_documentation.html#is-it-safe-to-use-copr


[sticky]: https://github.com/linuxmint/sticky
[sticky-copr]: https://copr.fedorainfracloud.org/coprs/a-random-linux-lover/sticky/
[sticky-img]: img/sticky.png


[webapp-manager]: https://github.com/KyleGospo/webapp-manager
[webapp-manager-copr]: https://copr.fedorainfracloud.org/coprs/kylegospo/webapp-manager/
[webapp-manager-img]: img/webapp-manager.png


[umoria]: https://umoria.org/
[umoria-copr]: https://copr.fedorainfracloud.org/coprs/whitehara/umoria/
[umoria-img]: img/umoria.png


[pycharm]: https://www.jetbrains.com/pycharm/
[pycharm-copr]: https://copr.fedorainfracloud.org/coprs/phracek/PyCharm/
[pycharm-img]: img/pycharm.png
