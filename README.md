mpv_351_workaround - solution for #351 issue
https://github.com/mpv-player/mpv/issues/351

cp /usr/share/examples/mpv/input.conf ~/.config/mpv/input.conf.1

change keys in ~/.config/mpv/input.conf.1 as you want, but don't remove lines

you can add your keys into the end of ~/.config/mpv/input.conf.1, it will be override keys above

comment lines will uncommenting automatically

before use should launch ./install script
