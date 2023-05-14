# temp-resolution

Script to set a temporary screen resolution and prevent the resolution from changing while games are running.

The primary use case is to automatically switch to lower resolution when streaming games with [Sunshine](https://github.com/LizardByte/Sunshine).

## Usage

`temp-resolution set 1920x1080` to set a temporary screen resolution.

`temp-resolution undo` to revert resolution changes.

`temp-resolution lock <lock name>` to prevent changing screen resolution with the above commands.

`temp-resolution unlock <lock name>` to allow resolution changes.

`temp-res-lock <lock name> <program>` to lock while a program is running and unlock when the program quits.

`temp-resolution help` to show all options.
