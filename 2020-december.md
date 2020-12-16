# 4 cool new projects to try in COPR for December 2020

COPR is a [collection][copr] of personal repositories for software
that isn’t carried in Fedora. Some software doesn’t conform to
standards that allow easy packaging. Or it may not meet other Fedora
standards, despite being free and open-source. COPR can offer these
projects outside the Fedora set of packages. Software in COPR isn’t
supported by Fedora infrastructure or signed by the project. However,
it can be a neat way to try new or experimental software.

This article presents a few new and interesting projects in COPR. If
you’re new to using COPR, see the [COPR User Documentation][copr-docs]
for how to get started.


## Blanket

[Blanket][blanket] is an application for playing background sounds,
which may potentially improve your focus and increase your
productivity. Alternatively, it may help you relax and fall asleep
in a noisy environment. No matter what time it is or where you are,
Blanket allows you to wake up while birds are chirping, work
surrounded by friendly coffee shop chatter or distant city traffic,
and then sleep like a log next to a fireplace while it is raining
outside. Other popular choices for background sounds such as pink and
white noise are also available.

![Blanket][blanket-img]

### Installation instructions

The [repo][blanket-copr] currently provides Blanket for Fedora 32
and 33. To install it, use these commands:

```
sudo dnf copr enable tuxino/blanket
sudo dnf install blanket
```


## k9s

[k9s][k9s] is a command-line tool for managing Kubernetes clusters. It
allows you to list and interact with running pods, read their logs,
dig through used resources, and overall make the Kubernetes life
easier. With its extensibility through plugins and customizable UI,
k9s is welcoming to power-users.

![k9s][k9s-img]

For [many more previews][k9s-previews], please see the [project
page][k9s].

### Installation instructions

The [repo][k9s-copr] currently provides `k9s` for Fedora 32, 33, and
Fedora Rawhide, EPEL 7, 8, Centos Stream, and others. To install it,
use these commands:

```
sudo dnf copr enable luminoso/k9s
sudo dnf install k9s
```


## rhbzquery

[rhbzquery][rhbzquery] is a simple tool for querying the Fedora
Bugzilla instance. It provides an interface for specifying the search
query but it doesn't list results in the command-line. Instead,
`rhbzquery` generates a Bugzilla URL and opens it in a web browser.

![rhbzquery][rhbzquery-img]

### Installation instructions

The [repo][rhbzquery-copr] currently provides `rhbzquery` for Fedora
32, 33, and Fedora Rawhide. To install it, use these commands:

```
sudo dnf copr enable petersen/rhbzquery
sudo dnf install rhbzquery
```


## SolArc theme

[krouma/solarized][solarc-project] project provides [SolArc][solarc]
theme for GTK, xfwm, gnome-shell, cinnamon, and metacity. SolArc is a
flat theme with transparent elements based on the
[solarized][solarized] color palette by [Ethan
Schoonover][altercation] and [Arc theme][arc-theme].

![SolArc][solarc-img]

### Installation instructions

The [repo][solarized-copr] currently provides SolArc theme for Fedora
33, Fedora Rawhide, EPEL 7, 8, and Centos Stream. To install it, use
these commands:

```
sudo dnf copr enable krouma/solarized
sudo dnf install solarc-theme
```

After installing the theme, use [GNOME Tweaks][tweaks] to apply it.


## gping

[gping][gping] is a more visually intriguing alternative to the
standard `ping` command, as it shows results in a graph. It is also
possible to ping multiple hosts at the same time to easily compare
the times of their responses.

![gping][gping-img]

### Installation instructions

The [repo][gping-copr] currently provides gping for Fedora 32, 33,
and Fedora Rawhide. As well as for EPEL 7 and 8. To install it, use these commands:

```
sudo dnf copr enable atim/gping
sudo dnf install gping
```



[copr]: https://copr.fedorainfracloud.org/
[copr-docs]: https://docs.pagure.org/copr.copr/user_documentation.html

[blanket]: https://github.com/rafaelmardojai/blanket
[blanket-copr]: https://copr.fedorainfracloud.org/coprs/tuxino/blanket/
[blanket-img]: img/blanket.png

[k9s]: https://k9scli.io/
[k9s-copr]: https://copr.fedorainfracloud.org/coprs/luminoso/k9s/
[k9s-previews]: https://k9scli.io/#-previews
[k9s-img]: img/k9s.png

[rhbzquery]: https://github.com/juhp/rhbzquery
[rhbzquery-copr]: https://copr.fedorainfracloud.org/coprs/petersen/rhbzquery/
[rhbzquery-img]: img/rhbzquery.png

[solarc]: https://github.com/krouma/solarc-theme
[solarc-copr]: https://copr.fedorainfracloud.org/coprs/krouma/solarized/
[altercation]: https://github.com/altercation
[arc-theme]: https://github.com/jnsh/arc-theme
[solarized]: https://ethanschoonover.com/solarized/
[tweaks]: https://fedoramagazine.org/tweaking-the-look-of-fedora-workstation-with-themes/
[solarc-img]: img/solarized.png

[gping]: https://github.com/orf/gping
[gping-copr]: https://copr.fedorainfracloud.org/coprs/atim/gping
[gping-img]: img/gping.png
