kali-custom
===========

### Usage

```bash
curl -s https://raw.githubusercontent.com/chris-m-powell/kali-build/master/deploy.sh | sudo bash -s -- [<options>]
```
### Options

| Options | Argument                                          |
|:-------:|:--------------------------------------------------|
| -u      | Name of local Kali user                           |
| -t      | Comma-delimited list of tags (defaults to 'all')  |
| -h      | displays usage options                            |

### Supported tags 

| Tag         | Description                                                 |
|:-----------:|:------------------------------------------------------------|
| all         | Apply all custom configurations                             |
| alacritty   | Fast, cross-platform, OpenGL terminal emulator              |
| compton     | Compositor for X                                            |
| discord     | VoIP, instant messaging, and digital distribution platform  |
| gotop       | System activity monitoring tool                             | 
| mpd         | Server-side daemon for audio playback                       |
| misc-tools  | Assortment of misc packages available in Kali repo          |
| neofetch    | Fast, highly customizable system info script                |
| neovim      | Refactor of Vim, focused on extensibility and usability     |
| ncmpcpp     | Terminal-based MPD client to control audio playback         |
| qutebrowser | Keyboard-driven, vim-like browser based on PyQt5            |
| ranger      | Terminal-based, visual file manager inspired by Vim         |
| tty-clock   | Simple terminal clock                                       |
| virtualbox  | x86 virtualization solution                                 |
