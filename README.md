# micro_redox

A family of 40% choc keyboards(34 keys) inspired by the Microdox and Ferris keyboards. 

 - The **micro_redox_split** is a pro-micro powered reversible split that does not require diodes.
 - The **micro_redox_semi_spit** is an integrated mcu semi split with usb-c and a rotary encoder.

Both boards can use either hot-swap sockets or the switches can be soldered directly to the pcb.

## Inspiration and differences

The Microdox(36 key MX spaced split) from Boardsource is a great keyboard. It was my first choc board, and after trying out a few keymaps, I realized I didn't need the outer thumb keys. In my experience, those keys are difficult to reach and do not serve a purpose on the keymap I've settled on.   
The Ferris(34 key choc spaced split) is another great keyboard. I like the look of the Ferris but a couple things made it uncomfortable for me to use:

* the thumb cluster is too close to the alphas 
* the pinky stagger is aggressive 

For the micro_redox family, I have kept the column stagger from the Microdox, made it choc spaced, and removed the outter thumb keys. I have also kept the distance between the homing keys and the thumb keys because I find it comfortable. Finally, I rotated the innermost thumb key which means that only 1u keycaps will fit there.  
For the split, I've also used a reversible pro-micro footprint so that both of them can face the same way i.e. component side down. It's a cleaner look.

## Libraries

These libraries that help me move fast. I may not actually be using them in this project, but adding them to keyboard projects is a habit. The are all added as git submodules so make sure you pull them down after you pull the repo.  
My thanks to the authors for sharing.

- [Keebio-components](https://github.com/keebio/keebio-components)
  - [@keebio](https://github.com/keebio)
- [Keebio-parts.pretty](https://github.com/keebio/Keebio-Parts.pretty)
  - [@keebio](https://github.com/keebio)
- [keyswtiches.pretty](https://github.com/daprice/keyswitches.pretty)
  - [@daprice](https://github.com/daprice)
- [random-keyboard-parts.pretty](https://github.com/ai03-2725/random-keyboard-parts.pretty)
  - [@ai03-2725](https://github.com/ai03-2725)
- [https://github.com/foostan/kbd](https://github.com/foostan/kbd)
  - [@foostan](https://github.com/foostan)
- [Customizable Rotary Encoder Knob](https://www.thingiverse.com/thing:2797118)
  - [tsw](https://www.thingiverse.com/tsw/designs)
