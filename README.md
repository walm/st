st - simple terminal
====================

This is a clone of [suckless.org](https://st.suckless.org/) terminal client **st** with my customizations.

## Customizations

 - [xresources](https://st.suckless.org/patches/xresources/)
 - [vertcenter](https://st.suckless.org/patches/vertcenter/)

## Installation

	cd src
	patch < ../patches/st-xresources-20190105-3be4cf1.diff
	patch < ../patches/st-vertcenter-20180320-6ac8c8a.diff
	make clean install

More details read `README` in `src` folder
