# 4 cool new projects to try in COPR for March 2021

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


## DroidCam
We are living through confusing times being isolated at our homes and
the majority of our interactions with friends and coworkers takes
place on some video conference platform. Don't waste your money for an
overpriced webcam if you carry one in your pocket already.
[DroidCam][droidcam] lets you pair your phone with a computer and use
it as a dedicated webcam. The connection can be done through USB cable
or over WiFi. Droidcam provides remote control of the camera and
allows zooming, using autofocus, toggling the LED ligth and other neat
features.

![DroidCam][droidcam-img]

### Installation instructions

The [repo][droidcam-copr] currently provides DroidCam for Fedora 33.
To install it, use these commands:

```
sudo dnf copr enable meeuw/droidcam
sudo dnf install droidcam
```


## Gemini clients
Have you ever wondered what would internet browsing experience would
be if World Wide Web went an entirely different route and didn't adopt
CSS and client-side scripting? [Gemini][gemini] is a modern
alternative to the HTTPS protocol albeit it doesn't aim to replace
it. The [stenstorp/gemini][gemini-copr] Copr project provides clients
for browsing Gemini _websites_, namely [Castor][castor],
[Dragonstone][dragonstone], [Kristall][kristall], and [Lagrange][lagrange].

![Castor][gemini-img]

### Installation instructions

The [repo][gemini-copr] currently provides Gemini clients for Fedora
32, 33, 34, and Fedora Rawhide. As well as for EPEL 7 and 8, and
CentOS Stream. To install it, use these commands:

```
sudo dnf copr enable stenstorp/gemini
sudo dnf install castor
sudo dnf install dragonstone
sudo dnf install kristall
sudo dnf install lagrange
```


## Ly

[Ly][ly] is a lightweight TUI (ncurses-like) login manager for Linux
and BSD. Theoretically it should support all X desktop environments
and window managers and many of them [were tested][ly-support]). Ly
also provides a basic wayland support (Sway works very
well). Somewhere in the configuration, there is an easter egg option
to enable the famous [PSX DOOM fire][psx-doom-fire] animation in the
background.

![Ly][ly-img]

### Installation instructions

The [repo][ly-copr] currently provides Ly for Fedora 32, 33, and
Fedora Rawhide. To install it, use these commands:

```
sudo dnf copr enable dhalucario/ly
sudo dnf install ly
```

Before setting up Ly to be your system login screen, run _ly_ comamnd
in the terminal to make sure it works properly. Then proceed with
disabling your current login manager and enabling Ly instead.

```
sudo systemctl disable gdm
sudo systemctl enable ly
```

Finally, restart your computer for the changes to take an effect.


## AWS CLI v2

TODO

![aws-cli-2][aws-cli-img]

### Installation instructions

The [repo][aws-cli-copr] currently provides Ly for Fedora 32, 33, 34, and
Fedora Rawhide. To install it, use these commands:

```
sudo dnf copr enable spot/aws-cli-2
sudo dnf install aws-cli-2
```





[copr]: https://copr.fedorainfracloud.org/
[copr-docs]: https://docs.pagure.org/copr.copr/user_documentation.html

[droidcam]: https://www.dev47apps.com/
[droidcam-copr]: https://copr.fedorainfracloud.org/coprs/meeuw/droidcam/builds/
[droidcam-img]: img/droidcam.png

[gemini]: https://gemini.circumlunar.space/
[gemini-copr]: https://copr.fedorainfracloud.org/coprs/stenstorp/gemini/
[gemini-img]: img/gemini.png
[castor]: https://git.sr.ht/~julienxx/castor
[dragonstone]: https://gitlab.com/baschdel/dragonstone
[kristall]: https://kristall.random-projects.net/
[lagrange]: https://github.com/skyjake/lagrange

[ly]: https://github.com/nullgemm/ly
[ly-copr]: https://copr.fedorainfracloud.org/coprs/dhalucario/ly/
[ly-img]: img/ly.png
[ly-support]: https://github.com/nullgemm/ly#support
[psx-doom-fire]: https://fabiensanglard.net/doom_fire_psx/index.html

[aws-cli]: https://aws.amazon.com/blogs/developer/aws-cli-v2-is-now-generally-available/
[aws-cli-copr]: https://copr.fedorainfracloud.org/coprs/spot/aws-cli-2/
[aws-cli-img]: img/aws-cli-2.png
