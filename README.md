# Keyboard

This repo is built as a custom animation on the Nullbitsco Nibble keyboard.

Huge shoutout to @tokolist who helped me decipher a lot of code. My code is heavily inspired by their optimization of JBaguley's Corne keyboard build

The bulbasaur sprites are sourced from the pokencyclopedia.info. Flipped the sprites to face left to right. They were traced in pixilart and output as a .png
The ground and sky were custom drawn to include clouds drifting in the background. Also done in pixilart

After having all the images, they were put into image2cpp and output as bytes read vertically, split by the rows to represent the 4 pages on the OLED and then rendered programatically together

The mask is drawn around the bulbasaur sprites as a means to give it a permament barrier, but also to read in whether or not the sprite frame should show or the sky/ground frame should show. The background is output as white in image2cpp and the bulbasaur sprite is all black to create the barrier/mask

# Useful Links
https://github.com/tokolist/nibble_tidbit/blob/main/nibble_tidbit/keymaps/fancy/keymap.c <br>
https://javl.github.io/image2cpp/ <br>
https://www.pokencyclopedia.info/en/index.php?id=sprites/001 <br>
https://www.pixilart.com/ <br>
