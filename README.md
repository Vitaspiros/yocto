# Yocto
A very simple and small (less than 350 lines of code!) text editor on C as a command-line tool (CLI command line interface). more on the [wiki](https://github.com/ikozyris/yocto/wiki)

Still under development.
## How to use for linux:
Ctrl+Alt+T and type:
```
sudo apt install gcc -y 
gcc -o text-editor Downloads/Text-editor*.c -lncurses
./text-editor
```
## For windows:
([acording to this guide](https://docs.microsoft.com/en-us/cpp/build/walkthrough-compile-a-c-program-on-the-command-line?view=msvc-170))
Open cmd and type:
```
cl Downloads\Text-editor.c
Text-editor
```

OR:

Open Code::Blocks

Ctrl+O  and locate the file

and click build and run


### License

Copyright (C) 2022  ikozyris<br>
Copyright (C) 2022  gkozyris

This program is free software: you can redistribute it and/or modify
it under the terms of the GNU General Public License as published by
the Free Software Foundation, either version 3 of the License, or
(at your option) any later version.

This program is distributed in the hope that it will be useful,
but WITHOUT ANY WARRANTY; without even the implied warranty of
MERCHANTABILITY or FITNESS FOR A PARTICULAR PURPOSE.  See the
GNU General Public License for more details.

You should have received a copy of the GNU General Public License
along with this program.  If not, see <https://www.gnu.org/licenses/>.

