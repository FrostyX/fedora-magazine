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

TODO

![Blanket][blanket-img]

### Installation instructions

The [repo][dialect-copr] currently provides Blanket for Fedora 32
and 33. To install it, use these commands:

```
sudo dnf copr enable tuxino/blanket
sudo dnf install blanket
```


## k9s

TODO

![k9s][k9s-img]

### Installation instructions

The [repo][k9s-copr] currently provides `k9s` for Fedora 32, 33, and
Fedora Rawhide, EPEL 7, 8, Centos Stream, and others. To install it,
use these commands:

```
sudo dnf copr enable luminoso/k9s/
sudo dnf install k9s
```




## rhbzquery

TODO

![rhbzquery][rhbzquery-img]

### Installation instructions

The [repo][rhbzquery-copr] currently provides `rhbzquery` for Fedora
32, 33, and Fedora Rawhide. To install it, use these commands:

```
sudo dnf copr enable petersen/rhbzquery
sudo dnf install rhbzquery
```





## solarized

TODO

![solarized][solarized-img]

### Installation instructions

The [repo][solarized-copr] currently provides SolArc theme for Fedora
33, Fedora Rawhide, EPEL 7, 8 and Centos Stream. To install it, use
these commands:

```
sudo dnf copr enable krouma/solarized
sudo dnf install solarc-theme
```

TODO Use gnome-tweak-tool for changing the theme







## gping

TODO

![gping][gping-img]

### Installation instructions

The [repo][dialect-copr] currently provides gping for Fedora 32, 33,
and Fedora Rawhide. As well as for EPEL 7 and 8. To install it, use these commands:

```
sudo dnf copr enable atim/gping
sudo dnf install gping
```



[blanket]: https://github.com/rafaelmardojai/blanket
[blanket-copr]: https://copr.fedorainfracloud.org/coprs/tuxino/blanket/
[blanket-img]: img/blanket.png

[k9s]: https://k9scli.io/
[k9s-copr]: https://copr.fedorainfracloud.org/coprs/luminoso/k9s/
[k9s-img]: img/k9s.png

[rhbzquery]: https://github.com/juhp/rhbzquery
[rhbzquery-copr]: https://copr.fedorainfracloud.org/coprs/petersen/rhbzquery/
[rhbzquery-img]: img/rhbzquery.png

[solarized]: https://github.com/krouma/solarc-theme
[solarized-copr]: https://copr.fedorainfracloud.org/coprs/krouma/solarized/
[solarized-img]: img/solarized.png

[gping]: https://github.com/orf/gping
[gping-copr]: https://copr.fedorainfracloud.org/coprs/atim/gping
[gping-img]: img/gping.png
