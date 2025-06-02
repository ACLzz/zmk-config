# ZMK Corne Config
This is my version of zmk config for corne. </br>
I've ordered my corne on keebd, so there are no additional pin for nice!view display and pretty defined acrylic case. Anyone with similar setup could find my config helpful, because I got some issues on my way.
![IRL image](/resources/real-phootage.jpg)

## LEDs and nice!view
Build supports LEDs and nice!view at the same time (CS pin must be soldered on nice!nano's 107 pin).

## 3D-printed ergonomic addon
I like my acrylic case, but I also want to be able to regulate angle of my splits. I didn't find any solution on popular printing platforms, other than print the whole plastic case (ew), so I made my own. You can find it in code tree as `corne-addon.3mf`.</br>
Soon I will add it to makerworld as well. For assembly you need two short M4 screws / bolts and two long. Glue gun would be a plus, to glue heads of the long screws, to prevent them from scratching desk and slipping. Don't overtighten bolts which pushing against the case, because model can snap easily.

## Helpful tools I use
- [Keymap editor](https://nickcoutsos.github.io/keymap-editor) - can fetch your keymap from public repo and automaticaly update it.
- [Keymap visualization](https://github.com/caksoylar/keymap-drawer) - automated visualization script written on python that works with github actions.
- [Practice](https://www.keybr.com) - website to practice your new keymap.
- [Racing](https://data.typeracer.com) - website to race against other players, have a nice mode for programmers to practice special characters.
- [Keyboard checker](https://keyboard-test.space/) - website to check if all of the buttons works correctly.

## TODO
- Add custom nice!view widgets.
- Add layers for programming on Go, Rust and C.

## Layers
![layers image](/resources/corne.svg)
