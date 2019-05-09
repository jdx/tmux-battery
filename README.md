tmux-battery
============

Shows battery charge level inside tmux status.

![screenshot.png](screenshot.png)

Installation
============

Add the following to `~/.tmux.conf`

```
set -g status-right '#(tmux-battery)'
```
