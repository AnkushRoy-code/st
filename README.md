This repo was initially a fork of [this](https://github.com/siduck/st.git)
repo, but it was unmantained, had a lotta bugs (like
https://github.com/siduck/st/issues/68 or delete key not working) and also had
features I didn't want. I started from scratch after that and made. Looks
absolutely amazing imho. I am open to suggestions too. Feel free to use it for
your own.

## Install

```
git clone https://github.com/AnkushRoy-code/st.git
cd st
(change the compiler if you cant use c99 to compile: sed -i 's/^#\ CC\ =\ c99/CC=gcc/' config.mk)
sudo make install
```

## Fonts

- Install JetbrainsMono Mono Nerd Font or any nerd font from [here](https://www.nerdfonts.com/font-downloads)

## Patches:

I here have the patches Siduck/st had and what I have left in this repo.

- Ligatures
- scrollback
- ~Clipboard~ (Works natively)
- ~Alpha(Transparency)~ (I have picom)
- ~Boxdraw~ (Native one looks good)
- ~patch_column ( doesnt cut text while resizing)~ (IDK what it did anyway)
- ~font2~ (same as above)
- ~right click paste~ (Never used this feature, so it has to go)
- st desktop entry
- ~newterm~ (Never used this feature either)
- ~anygeometry~ (IDK)
- ~dynamic-cursor-color~ (Too distracting)
- ~xresources~ (I like catppuccin)
- ~sync patch ( Better draw timing to reduce flicker/tearing and improve animation smoothness )~ (Will implement later if I feel the need to)
- ~live reload ( change colors/fonts on the fly )~ (Nope I like catppuccin)
  and more...
  <br>

## Default Keybindings<br>

<pre>
ctrl + shift + c        Copy  <br>
ctrl + shift + v        Paste <br>

(Zoom)
alt  + comma            Zoom in <br>
alt  + .                Zoom out <br>
alt  + g                Reset Zoom<br>

shift + pg-down         scroll down
shift + pg-up           scroll up
</pre>

you can change all of these in config.h
<br>

## Last Section
As you can see I copied the whole readme from siduck/st too and kept relevant
parts. I will add screenshots later. I have made this for my needs and stripped
away a lot of things I don't use. If you want them add them yourself (GFIY).
