# ![byobu](https://launchpadlibrarian.net/39290721/byobu_64.png) byobu-howto

[Byobu](http://byobu.co/byobu.wav) is a light, powerful, text-based window manager based on [GNU Screen](http://www.gnu.org/software/screen/). Using Byobu, you can quickly create and move between different windows over a single SSH connection or TTY terminal, monitor dozens of important statistics about your system, detach and reattach to sessions later while your programs continue to run in the background. 
## Basic key bindings

* Move to pane  [Shift] + Left/Right/UP/Down arrow
* Zoom into/out of a pane  [Shift] + F11

* Scroll back through this window's history  [Alt] + Pageup
* Scroll forward through this window's history  [Alt] + Pagedown

* Kill window   [Ctrl] + a  k

## List "convenient keybindings"

You can:
```
cat /usr/share/doc/byobu/help.tmux.txt
```

```
Byobu is a suite of enhancements to tmux, as a command line
tool providing live system status, dynamic window management,
and some convenient keybindings:

  F1                             * Used by X11 *
    Shift-F1                     Display this help
  F2                             Create a new window
    Shift-F2                     Create a horizontal split
    Ctrl-F2                      Create a vertical split
    Ctrl-Shift-F2                Create a new session
  F3/F4                          Move focus among windows
    Alt-Left/Right               Move focus among windows
    Alt-Up/Down                  Move focus among sessions
    Shift-Left/Right/Up/Down     Move focus among splits
    Shift-F3/F4                  Move focus among splits
    Ctrl-F3/F4                   Move a split
    Ctrl-Shift-F3/F4             Move a window
    Shift-Alt-Left/Right/Up/Down Resize a split
  F5                             Reload profile, refresh status
    Alt-F5                       Toggle UTF-8 support, refresh status
    Shift-F5                     Toggle through status lines
    Ctrl-F5                      Reconnect ssh/gpg/dbus sockets
    Ctrl-Shift-F5                Change status bar's color randomly
  F6                             Detach session and then logout
    Shift-F6                     Detach session and do not logout
    Alt-F6                       Detach all clients but yourself
    Ctrl-F6                      Kill split in focus
  F7                             Enter scrollback history
    Alt-PageUp/PageDown          Enter and move through scrollback
    Shift-F7                     Save history to $BYOBU_RUN_DIR/printscreen
  F8                             Rename the current window
    Ctrl-F8                      Rename the current session
    Shift-F8                     Toggle through split arrangements
    Alt-Shift-F8                 Restore a split-pane layout
    Ctrl-Shift-F8                Save the current split-pane layout
  F9                             Launch byobu-config window
    Ctrl-F9                      Enter command and run in all windows
    Shift-F9                     Enter command and run in all splits
    Alt-F9                       Toggle sending keyboard input to all splits
  F10                            * Used by X11 *
  F11                            * Used by X11 *
    Alt-F11                      Expand split to a full window
    Shift-F11                    Zoom into a split, zoom out of a split
    Ctrl-F11                     Join window into a vertical split
  F12                            Escape sequence
    Shift-F12                    Toggle on/off Byobu's keybindings
    Alt-F12                      Toggle on/off Byobu's mouse support
    Ctrl-Shift-F12               Mondrian squares
/usr/share/doc/byobu/help.tmux.txt (END)
```

[Thanks to Dustin Kirkland](https://askubuntu.com/users/4733/dustin-kirkland)


## Key bindings links

[Byobu ubuntu documentation](https://help.ubuntu.com/community/Byobu/#Key_Bindings)


[Screen 5.1 Default Key Bindings](https://www.gnu.org/software/screen/manual/html_node/Default-Key-Bindings.html)


[Byobu Keybindings Cheat Sheet by mikemikk](https://www.cheatography.com/mikemikk/cheat-sheets/byobu-keybindings/)
