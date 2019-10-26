st - simple terminal
====================

This is a clone of [suckless.org](https://st.suckless.org/) terminal client **st** with my customizations.

## Customizations

 - [xresources](https://st.suckless.org/patches/xresources/)
 - [vertcenter](https://st.suckless.org/patches/vertcenter/)
 - [scrollback](https://st.suckless.org/patches/scrollback/)

## How it was done

	cd src
	patch < ../patches/st-xresources-20190105-3be4cf1.diff
	patch < ../patches/st-vertcenter-20180320-6ac8c8a.diff
	patch < ../patches/st-scrollback-20190331-21367a0.diff
	patch < ../patches/st-scrollback-mouse-0.8.2.diff

## Installation

Read `README` in `src` folder
