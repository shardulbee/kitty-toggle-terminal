# kitty-toggle-terminal

This [kitten](https://sw.kovidgoyal.net/kitty/kittens_intro/) allows you to toggle between/launch a terminal window below an instance of `nvim` running in Kitty.

## Installation

Copy the `toggle_terminal.py` file below by whatever means to your Kitty config directory. This is usually `$XDG_CONFIG_HOME/kitty`. Then, add the following to your `kitty.conf`:

```conf
map ctrl+` kitten toggle_terminal.py
```

You can choose whatever hotkey you'd like following the `map` keyword in your configuration.
