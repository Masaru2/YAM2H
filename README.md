# YAM2H - Yet another Mother 2 Hack

(Unlike nothing ever done before) This project aims to make Earthbound the closest as possible to Mother 2,
but unlike the countless "Restoration projects"

## Origin

Back in September 2019, I tried to port the Maternalbound Redux script to older versions of Maternalbound and shared it
to Shadowone333 as some kind of response of Redux changing a lot of things in terms of gameplay and graphics.
This leaded up to basically nothing.

5 or 6 years later, in October 2025, I discovered that CoolGuyBrendyn shared its source code
for his hack "Mother 2: Perfect Edition" and started working on it for the "funnies"
digging out the stuff I did back in 2019, starting this project.

## Features

* Graphics, Tilesets and Names reverted to how they were in Mother 2

* Ported the script from Maternalbound Redux, albeit with some changes

* Translated Debug Mode (Ported from Maternalbound Redux)

* Restored the CAST secuence changing colors depending of the flavor you chose like in Mother 2

* Added "Clyde Mandelin" name in the credits

## Script changes from Maternalbound Redux

* "Dalaam" is now called "Ranma" like in Mother 2

* "Scarabia" is now called "Scarabi" like in Mother 2

* "Tendas" are now called "Gumi" like in Mother 2

* Fixed various grammar mistakes in the monkey languages

* A punk now says "Hello!" instead of "Oh yeah?" which is a known localization mistake in Earthbound

## Screenshots

![YAM2H_000](Screenshots/YAM2H_000.png)
![YAM2H_001](Screenshots/YAM2H_001.png)
![YAM2H_002](Screenshots/YAM2H_002.png)
![YAM2H_003](Screenshots/YAM2H_003.png)
![YAM2H_004](Screenshots/YAM2H_004.png)
![YAM2H_005](Screenshots/YAM2H_005.png)
![YAM2H_006](Screenshots/YAM2H_006.png)

## Known Issues

* The title screen is not 1:1 to the japanese version of Mother 2.
This is because the title screen in Earthbound is handled in such a different way than it does in Mother 2

## Where do I download this hack?

Download the patches from the [Release](https://github.com/Masaru2/YAM2H/releases) page.

## How to patch

It has to be patched through the following rom:

`Database match: EarthBound (USA)`

`Database: No-Intro: Super Nintendo Entertainment System (v. 20210222-050638)`

`File/ROM SHA-1: D67A8EF36EF616BC39306AA1B486E1BD3047815A`

`File/ROM CRC32: DC9BB451`

## Building

It can be compiled through the tool [Coilsnake 4.2](https://pk-hack.github.io/CoilSnake/).

## Special Thanks

Clyde Mandelin/Tomato - For making the Legends of Localization Page and Book for Earthbound/Mother 2

CoolGuyBrendyn - For the source code of "Mother 2: Perfect Edition" which served as a base for the project

ShadowOne333 - For creating Maternalbound Redux which this project takes a lot of it

Phoenixbound - For the ASM code that leaded me to restore the flavor colors in the CAST secuence