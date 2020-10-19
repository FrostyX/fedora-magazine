# 4 cool new projects to try in COPR for October 2020

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


## Dialect

[Dialect][dialect] is an application for text translation based on
Google Translate. It remembers your translation history and supports
features such as automatic language detection and text to speech. The
user interface is minimalistic and mimics the Google Translate tool
itself, so it is really easy to use.

![Dialect][dialect-img]

### Installation instructions

The [repo][dialect-copr] currently provides Dialect for Fedora 33 and Fedora
Rawhide. To install it, use these commands:

```
sudo dnf copr enable lyessaadi/dialect
sudo dnf install dialect
```


## GitHub CLI
[gh][gh] is an official GitHub command-line client. It provides fast
access and full control over your project issues, pull requests, and
releases right in the terminal. Issues (and everything else) can also
be easily viewed in the web browser for a more standard user interface
or sharing with others.

![GitHub CLI][gh-img]

### Installation instructions

The [repo][gh-copr] currently provides `gh` for Fedora 33 and Fedora
Rawhide. To install it, use these commands:

```
sudo dnf copr enable jdoss/github-cli
sudo dnf install github-cli
```


## Glide
[Glide][glide] is a minimalistic media player based on GStreamer. It
can play both local and remote files in any multimedia format
supported by GStreamer itself. If you are in a need of a multiplatform
media player with a simple user interface, you might give Glide a try.

![Glide][glide-img]

### Installation instructions

The [repo][glide-copr] currently provides Glide for Fedora 32, 33, and
Rawhide. To install it, use these commands:

```
sudo dnf copr enable atim/glide-rs
sudo dnf install glide-rs
```


## Vim ALE

[ALE][vim-ale] is a plugin for Vim text editor, providing syntax and
semantic error checking. It also brings support for fixing code and
many other IDE-like features such as TAB-completion, jumping to
definitions, finding references, viewing documentation, etc.

![Vim ALE][vim-ale-img]

### Installation instructions

The [repo][vim-ale-copr] currently provides `vim-ale` for Fedora 31,
32, 33, and Rawhide, as well as for EPEL8. To install it, use these
commands:

```
sudo dnf copr enable praiskup/vim-ale
sudo dnf install vim-ale
```




[copr]: https://copr.fedorainfracloud.org/
[copr-docs]: https://docs.pagure.org/copr.copr/user_documentation.html

[dialect]: https://github.com/gi-lom/dialect
[dialect-copr]: https://copr.fedorainfracloud.org/coprs/lyessaadi/dialect/
[dialect-img]: img/dialect.png

[gh]: https://github.com/cli/cli
[gh-copr]: https://copr.fedorainfracloud.org/coprs/jdoss/github-cli/
[gh-img]: img/github-cli.png

[glide]: https://github.com/philn/glide
[glide-copr]: https://copr.fedorainfracloud.org/coprs/atim/glide-rs/
[glide-img]: img/glide.png

[vim-ale]: https://github.com/dense-analysis/ale
[vim-ale-copr]: https://copr.fedorainfracloud.org/coprs/praiskup/vim-ale/
[vim-ale-img]: img/vim-ale.png
