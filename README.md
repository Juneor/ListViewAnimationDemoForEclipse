# ListViewAnimationDemoForEclipse

Based on ListViewAnimation repository, target Lollipop and for Eclipse ADT, all libraries in source

Credits go to below repositories:

- [nhaarman/ListViewAnimations][1]
- [JakeWharton/NineOldAndroids][2]

## Why

Official ListViewAnimation repository provides gradle based projects for Android Studio, and this is for Eclipse ADT for old time sake.

These projects are tested in Eclipse Luna with ADT, target build API 21.

## How to use

Just clone this repository and use your Eclipse to import them all.

### Depedences:

- lib-core
	- appcompat_v7
- lib-core-slh
	- appcompat_v7
	- lib-core
	- lib-stickylistheaders
- lib-manipulation
	- appcompat_v7
	- lib-core
- lib-stickylistheaders
	- appcompat_v7
- ListViewAnimationDemo
	- appcompat_v7
	- lib-core
	- lib-core-slh
	- lib-manipulation
	- lib-stickylistheaders

### The Demo App

The Demo App is actually from [the example of ListViewAnimations][3], which exellently demostrated how great ListViewAnimations is.

![][4]

[1]: https://github.com/nhaarman/ListViewAnimations
[2]: https://github.com/JakeWharton/NineOldAndroids/downloads
[3]: https://github.com/nhaarman/ListViewAnimations/tree/master/example
[4]: https://raw.githubusercontent.com/nhaarman/ListViewAnimations/gh-pages/images/dynamiclistview.gif