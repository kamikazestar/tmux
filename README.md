# tmux-config

Tmux configuration.

Here's how configuration looks like:
![Tmux console screenshot](/images/tmux-config-screenshot.png)

## Key binding

<kbd>Ctrl</kbd> + <kbd>a</kbd> - Preffix key combination.\
<kbd>Ctrl</kbd>+ <kbd>a</kbd> <kbd>c</kbd> - Create new pane.\
<kbd>Ctrl</kbd> + <kbd>a</kbd> <kbd>n</kbd> - Switch to next pane.\
<kbd>Ctrl</kbd> + <kbd>a</kbd> <kbd>p</kbd> - Switch to previous pane.\
<kbd>Ctrl</kbd> + <kbd>w</kbd> - Kill current pane.\
<kbd>Ctrl</kbd> + <kbd>a</kbd> <kbd>r</kbd> - Reload tmux configuration.\
<kbd>Ctrl</kbd> + <kbd>a</kbd> <kbd>-</kbd>  - Split pane horizontally.\
<kbd>Ctrl</kbd> + <kbd>a</kbd> <kbd>|</kbd> - Split pane vertically.\
<kbd>Ctrl</kbd> + <kbd>left</kbd> - Resize pane to the left by 10.\
<kbd>Ctrl</kbd> + <kbd>right</kbd> - Resize pane to the right by 10.\
<kbd>Ctrl</kbd> + <kbd>up</kbd> - Resize pane to the up by 10.\
<kbd>Ctrl</kbd> + <kbd>down</kbd> - Resize pane to the down by 10.\
<kbd>Shift</kbd> + <kbd>left</kbd> - Resize pane to the left by 2.\
<kbd>Shift</kbd> + <kbd>right</kbd> - Resize pane to the right by 2.\
<kbd>Shift</kbd> + <kbd>up</kbd> - Resize pane to the up by 2.\
<kbd>Shift</kbd> + <kbd>down</kbd> - Resize pane to the down by 2.

## Inspiration

My main inspiration to create this configuration was stream one of the AWS developer advocate [Darko Mesaros](https://github.com/darko-mesaros).
Recording from that session can be find [here](https://www.youtube.com/watch?v=kPnYFsXml-I).

There are some slight changes to initial configuration proposed in stream which apply to username and hostname diplayed on the bar.
To have current username and hostname during SSH sessions, I'd used
[tmux-config-screenshot](https://github.com/soyuka/tmux-current-pane-hostname)
plugin.

## License
This code is distributed on [MIT License](/LICENSE).
