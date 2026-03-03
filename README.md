

# make-xfce-style




## Home

| Link | GitHub |
| ---- | ------ |
| [make-xfce-style](https://samwhelp.github.io/make-xfce-style/) | [GitHub](https://github.com/samwhelp/make-xfce-style) |




## Subject

* [Usage](#usage)
* [Option](#option)
* [Link](#link)




## Usage


### Quick Start

> How to download [make-xfce-style.sh](https://github.com/samwhelp/make-xfce-style/blob/main/make-xfce-style.sh) and run [it](https://raw.githubusercontent.com/samwhelp/make-xfce-style/refs/heads/main/make-xfce-style.sh).


* run

``` sh
bash <(curl -L https://raw.githubusercontent.com/samwhelp/make-xfce-style/refs/heads/main/make-xfce-style.sh)
```


* or run

``` sh
bash <(wget -q https://raw.githubusercontent.com/samwhelp/make-xfce-style/refs/heads/main/make-xfce-style.sh -O - )
```


* or run

``` sh
bash -c "$(curl -fsSL https://raw.githubusercontent.com/samwhelp/make-xfce-style/refs/heads/main/make-xfce-style.sh || wget -q https://raw.githubusercontent.com/samwhelp/make-xfce-style/refs/heads/main/make-xfce-style.sh -O - )"
```


* or run

``` sh
bash -c "$(wget -q https://raw.githubusercontent.com/samwhelp/make-xfce-style/refs/heads/main/make-xfce-style.sh -O - || curl -fsSL https://raw.githubusercontent.com/samwhelp/make-xfce-style/refs/heads/main/make-xfce-style.sh)"
```


### Basic

> default

``` sh
./make-xfce-style.sh
```


> Option: [REF_MASTER_DISTRO](#option--ref_master_distro)

* execute local script

``` sh
REF_MASTER_DISTRO=archlinux ./make-xfce-style.sh
```

* execute remote script

``` sh
REF_MASTER_DISTRO=archlinux bash <(curl -L https://raw.githubusercontent.com/samwhelp/make-xfce-style/refs/heads/main/make-xfce-style.sh)
```


> Option: [REF_MASTER_STYLE](#option--ref_master_style)

* execute local script

``` sh
REF_MASTER_STYLE=vimix ./make-xfce-style.sh
```

* execute remote script

``` sh
REF_MASTER_STYLE=vimix bash <(curl -L https://raw.githubusercontent.com/samwhelp/make-xfce-style/refs/heads/main/make-xfce-style.sh)
```




## Option


### Option / REF_MASTER_DISTRO

| REF_MASTER_DISTRO   |
| ------------------- |
| `debian` (default)  |
| `ubuntu`            |
| `fedora`            |
| `archlinux`         |
| `voidlinux`         |

> We can use `REF_MASTER_DISTRO=any` to skip the step of installing required packages.


### Option / REF_MASTER_STYLE

| REF_MASTER_STYLE    |
| ------------------- |
| `jasper` (default)  |
| `graphite`          |
| `fluent`            |
| `colloid`           |
| `vimix`             |
| `orchis`            |
| `layan`             |
| `lavanda`           |
| `qogir`             |




## Link

| Link | GitHub |
| ---- | ------ |
| [Xfce Adjustment](https://samwhelp.github.io/xfce-adjustment/) | [GitHub](https://github.com/samwhelp/xfce-adjustment) |




## Related Projects

| Link | GitHub |
| ---- | ------ |
| [make-gnome-shell-layout-wincity](https://samwhelp.github.io/make-gnome-shell-layout-wincity/) | [GitHub](https://github.com/samwhelp/make-gnome-shell-layout-wincity) |
| [make-gnome-shell-layout-maccity](https://samwhelp.github.io/make-gnome-shell-layout-maccity/) | [GitHub](https://github.com/samwhelp/make-gnome-shell-layout-maccity) |


| Link |
| ---- |
| [demo-style-select](https://github.com/samwhelp/note-about-menu-applet/tree/gh-pages/_demo/prototype/menu-applet/demo-application/demo-style-select) |




## Samwhelp

* [GitHub](https://github.com/samwhelp)
