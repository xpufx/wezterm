# CopyMode 'MoveToEndOfLineContent'

*Since: 20220624-141144-bd1b7c5d*

Moves the CopyMode cursor position to the last non-space cell in the current
line.

```lua
local wezterm = require 'wezterm'
local act = wezterm.action

return {
  key_tables = {
    copy_mode = {
      {
        key = '$',
        mods = 'NONE',
        action = act.CopyMode 'MoveToEndOfLineContent',
      },
    },
  },
}
```


