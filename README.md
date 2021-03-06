![Blacksmith icon](https://i.imgur.com/F3nfeLe.png)

# Blacksmith
A program for viewing, extracting, and converting (textures, 3D models, and sounds) from Assassin's Creed: Odyssey, Assassin's Creed: Origins, and Steep. It is in early stages, and this repo will be updated constantly with additional support.

> **Note**: Blacksmith is NOT a repacker.

>> **Another note**: Blacksmith supports ALL VERSIONS (past, latest, and future versions) of each game

>>> **Last note**: Blacksmith *DOES NOT CONDONE PIRACY*. The program assumes that you have access to the games' files.

----

***Check the [Current Support section](https://github.com/theawesomecoder61/Blacksmith/blob/master/CHANGELOG.md#current-support) to see what is supported.***

----

### Remember ARchive_neXt?
Blacksmith tries to serve as a successor to ARchive_neXt, since development has seemingly ceased, and it does not support the two latest Assassin's Creed games or Steep. I designed the functionality of Blacksmith to be identical to that of ARchive_neXt.

![Version 1.3.1](https://i.imgur.com/0qQpFHP.png)
![Version 1.4](https://i.imgur.com/t0XB38m.png)
![Version 1.3.1](https://i.imgur.com/wLcQ1qf.png)
![Version 1.3.1](https://i.imgur.com/nj28fQv.png)

## Supported Games
PC versions of:
- Assassin's Creed: Odyssey
- Assassin's Creed: Origins
- Steep

## Functionality
- The main features are viewing and extraction of:
  - .forge files
  - 3D models
    - conversion to: .obj
    - planned: .dae, .smd, .stl
  - textures
    - conversion to: .bmp, .dds, .png, .tga
  - sounds
    - conversion to: .ogg
- Also:
  - extraction of sounds and soundbanks from .pck files
  - creation of filelists from .forge files
  - extraction of all entries from .forge files

## First Time Setup
1. Download the latest version from below.
2. Upon opening Blacksmith, click `Settings` and set the Game Paths and Temporary Path.

## Usage
1. After setting the game paths, click the plus icon next to a game (on the left) to see all of the game's files.
2. Click the plus icon next to a .forge and wait to see all of the .forge's entries.
3. Click the plus icon next to a .forge entry to see all subentries.
> Doing this will extract and decompress that entry. The result is a `.acod`, `.acor`, or `.stp` file found in the Temporary Path with the same name.

> If there is a `Texture Map` or `Mesh` subentry, Blacksmith will try to load these in one of the Viewers.

## Downloads
[Found here.](https://github.com/theawesomecoder61/Blacksmith/releases)

## Changelog
[View the changelog here.](https://github.com/theawesomecoder61/Blacksmith/blob/master/Changelog.md)

## Research
Are you curious about the file structures of these games and my discoveries? Check out the [Wiki](https://github.com/theawesomecoder61/Blacksmith/wiki).

## Building
You will need:
- Visual Studio 2017
- .NET Framework 4.6

(built on Windows 10 Home 64-bit)

## Forum Thread/Discussion
[Blacksmith on Xentax](http://forum.xentax.com/viewtopic.php?f=10&t=19324&p=147450)

## License
Blacksmith is licensed under the MIT License.

## Third-Party Software
- ini-parser
- libzstd
- lzo
- oodle
- OodleSharp
- OpenTK
- texconv
- ww2ogg
- Zstandard.Net

Blacksmith icon by Krisada from the Noun Project
