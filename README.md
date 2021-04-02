# Zombie Arena
The Zombie Arena game, which is based on ideas and concepts from [*"Beginning C++ Game Programming" by John Horton*](https://www.packtpub.com/product/beginning-c-game-programming-second-edition/9781838648572).

## Requirements
- C++14
- SFML (x32 version)

## Install Game
- Open Terminal and change the current working directory to the location where you want the cloned directory to be made.
- Download the repository using the [instruction](https://help.github.com/en/github/creating-cloning-and-archiving-repositories/cloning-a-repository).

### How to build in Visual Studio
Before this project will work you'll need to install the [SFML graphics library](https://www.sfml-dev.org/). 

Steps can be found [here](https://www.sfml-dev.org/tutorials/2.5/#getting-started).

After opening the project, go to **"Project -> Properties..."**:
- Select **"All configurations"** in **"Configuration"** section;
- In **"C/C++ -> General -> Additional include directories"** section append the "include" directory of SFML library;
- In **"Linker -> General -> Additional library directories"** section append the "lib" directory of SFML library;
- Select **Debug** in **Configuration** section;
- At the beginning of the **"Linker -> Input -> Additional dependencies"** section append the string:
```bash
sfml-graphics-d.lib;sfml-window-d.lib;sfml-system-d.lib;sfml-network-d.lib;sfml-audio-d.lib;
```

## Gameplay
- `Enter` for start or pause the game.
- Move using `W`, `A`, `S`, `D`.
- Look around using mouse.
- Left mouse button for a shot from a gun.
- Collect items (Health, Ammo). Level up.
- `R` for reload a weapon.
- `Num1` / `Num2` / `Num3` / `Num4` / `Num5` / `Num6` for level up the player at the start of each level
- Fight through Zombie waves.
- Beat your high-score.
- `Esc` for exit from the game.


## Screenshots

<div style="display: flex; align-items: flex-start;">
  <img src="https://github.com/kgoncharova/zombie-arena/blob/master/screenshots/Screenshot1.png" height="200">
  <img src="https://github.com/kgoncharova/zombie-arena/blob/master/screenshots/Screenshot2.png" height="200">
  <img src="https://github.com/kgoncharova/zombie-arena/blob/master/screenshots/Screenshot3.png" height="200">
  <img src="https://github.com/kgoncharova/zombie-arena/blob/master/screenshots/Screenshot4.png" height="200">
  <img src="https://github.com/kgoncharova/zombie-arena/blob/master/screenshots/Screenshot5.png" height="200">
  <img src="https://github.com/kgoncharova/zombie-arena/blob/master/screenshots/Screenshot6.png" height="200">
</div>

## Demo for Windows
Run the included **zombie-arena.exe** file to play.
