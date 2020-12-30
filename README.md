# ⚜️ lily58-keymap
Customised QMK Keymap for Lily58 Pro.

## 🔗 Links
- [Lily58](https://github.com/kata0510/Lily58)
- [QMK Firmware](https://github.com/qmk/qmk_firmware)

## 📦 Usage
1. Clone QMK Firmware using Git.
1. In `keyboards/lily58/keymaps` directory, add this repository as a submodule:
   ```console
   $ git submodule add https://github.com/siketyan/lily58-keymap.git siketyan
   ```
1. Back to the root directory of QMK Firmware.
1. Compile the keymap using QMK CLI or something you like!
   ```console
   $ qmk compile -kb lily58 -km siketyan
   ```

## 🗾 Keymap
### QWERTY
```
,-----------------------------------------.                    ,-----------------------------------------.
| ESC  |   1  |   2  |   3  |   4  |   5  |                    |   6  |   7  |   8  |   9  |   0  |  `   |
|------+------+------+------+------+------|                    |------+------+------+------+------+------|
| Tab  |   Q  |   W  |   E  |   R  |   T  |                    |   Y  |   U  |   I  |   O  |   P  |  -   |
|------+------+------+------+------+------|                    |------+------+------+------+------+------|
|LCTRL |   A  |   S  |   D  |   F  |   G  |-------.    ,-------|   H  |   J  |   K  |   L  |   ;  |  '   |
|------+------+------+------+------+------|   [   |    |    ]  |------+------+------+------+------+------|
|LShift|   Z  |   X  |   C  |   V  |   B  |-------|    |-------|   N  |   M  |   ,  |   .  |   /  | Del  |
`-----------------------------------------/       /     \      \-----------------------------------------'
                  | LAlt | LGUI |LOWER | /Space  /       \Enter \  |RAISE |BackSP| RAlt |
                  |      |      |      |/       /         \      \ |      |      |      |
                  `----------------------------'           '------''--------------------'

 ```
 
### LOWER
```
,-----------------------------------------.                    ,-----------------------------------------.
|      | F11  | F12  | F13  | F14  | F15  |                    | F16  | F17  | F18  | F19  | F20  |      |
|------+------+------+------+------+------|                    |------+------+------+------+------+------|
|      |  F1  |  F2  |  F3  |  F4  |  F5  |                    |  F6  |  F7  |  F8  |  F9  | F10  |      |
|------+------+------+------+------+------|                    |------+------+------+------+------+------|
|      |   !  |   @  |   #  |   $  |   %  |-------.    ,-------|   ^  |   &  |   *  |   (  |   )  |      |
|------+------+------+------+------+------|   <   |    |    >  |------+------+------+------+------+------|
|      |      |      |      |      |      |-------|    |-------|   _  |   +  |   {  |   }  |   |  |      |
`-----------------------------------------/       /     \      \-----------------------------------------'
                  | LAlt | LGUI |LOWER | /Space  /       \Enter \  |RAISE |BackSP| RAlt |
                  |      |      |      |/       /         \      \ |      |      |      |
                  `----------------------------'           '------''--------------------'
```

### RAISE
```
,-----------------------------------------.                    ,-----------------------------------------.
|      |      |      |      |      |      |                    |      | Mute | Vol- | Vol+ | PScr |      |
|------+------+------+------+------+------|                    |------+------+------+------+------+------|
|      |   1  |   2  |   3  |   4  |   5  |                    |      | Home | PgDn | PgUp | End  |      |
|------+------+------+------+------+------|                    |------+------+------+------+------+------|
|      |   6  |   7  |   8  |   9  |   0  |-------.    ,-------|      | Left | Down |  Up  |Right |      |
|------+------+------+------+------+------|   (   |    |    )  |------+------+------+------+------+------|
|      |      |      |      |      |      |-------|    |-------|      |   +  |   -  |   =  |   \  |      |
`-----------------------------------------/       /     \      \-----------------------------------------'
                  | LAlt | LGUI |LOWER | /Space  /       \Enter \  |RAISE |BackSP| RAlt |
                  |      |      |      |/       /         \      \ |      |      |      |
                   `----------------------------'           '------''--------------------'
```
