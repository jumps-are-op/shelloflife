# shelloflife  *life in your terminal*
press `?` after running `shelloflife` for help.

# Preview

https://user-images.githubusercontent.com/91761043/226355694-0b50e812-f199-4428-b0e3-23cce51292c7.mp4


# QWERTY
This program is meant for [workman](https://workmanlayout.org) users.

To use this as a QWERTY user you need to change this
```sh
: "${CONFIG_KEY_left:=y}${CONFIG_KEY_down:=n}" \
 "${CONFIG_KEY_up:=e}${CONFIG_KEY_right:=o}" \
```
into this
```sh
: "${CONFIG_KEY_left:=h}${CONFIG_KEY_down:=j}" \
 "${CONFIG_KEY_up:=k}${CONFIG_KEY_right:=l}" \
```
to make vim-like keybindings.

Note: Arrow keys also works.

# DO NOT READ THE CODE
IT'S JUST A BIG PIECE OF SPAGHETTI CODE,
IT'S **NOT** MEANT TO BE READ, IT'S ONLY FOR SPEED NOT READABILITY.
