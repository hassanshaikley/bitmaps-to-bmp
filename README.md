# bitmaps-to-bmp

I use this to create my own custom pixelated fonts out of bitmaps

## How to run

`make`

`(cat header.txt ; ./font-gen) > [filename].bdf`


This generator uses the upper case fonts for the lowercase ones as well.

## How to edit the outputted font

1. Modify the .h file, which consists of several bitmaps

2. Compile

3. Run `(cat header.txt ; ./font-gen) > [filename].bdf`
