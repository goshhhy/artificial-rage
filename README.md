# Scifi FPS 

WIP

## Howto compile for different platforms

WIP. These notes are just for myself for now.

* Compile raylib for your platform from source

* Copy the libraylib.a into lib\PLATFORM (for example lib\win)

* Copy the following to include:
    * raylib.h
    * raymath.h

Make sure CMake builds the game for your platform. Right now it's setup for windows only
