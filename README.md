# mac_frogpad

My own configuration of the one-handed keyboard [FrogPad](http://frogpad.com/) using the default keyboard

- **NOTE**: _Only working on left hand configuration for now_
- No capital letters available yet
  - See [Future Improvements](#differences-and-future-improvements) for more details
- Go to http://frogpad.com/ for:
  - Right hand configuration
  - Windows "qwerty-frog"
  - Mac "qwerty-frog" for earlier macOS versions (10.11 and below)
  - Training game for practice!

## Inspired by

- Clark Mercer: https://github.com/clarkm
- https://clarkm.com/frogpad-left.json
- https://clarkm.com/frogpad-right.json

### Downloads here:

- <karabiner://karabiner/assets/complex_modifications/import?url=https://clarkm.com/frogpad-right.json>
- <karabiner://karabiner/assets/complex_modifications/import?url=https://clarkm.com/frogpad-left.json>

## System requirements

- MacOS 10.12 (Sierra) and above

## To install:

1. Download and install the app Karabiner-Elements (currently v12.1.0 as of 8/23/2018): https://pqrs.org/osx/karabiner/

2. Download and import keymap by going to this link and opening it with Karabiner-Elements: <karabiner://karabiner/assets/complex_modifications/import?url=https://raw.githubusercontent.com/stevenmchoi/my_frogpad/master/frogpad-left-v2.json>

3. In Karabiner-Elements, go to "Preferences" > "Profiles" tab > "Add profile", name the profile, and click "Select".

4. "Complex Modifications" tab > "Add rule", and enable "Frogpad left v2".

## Keymap (Left Hand)

- For "Primary" keys, simply type as normal with left hand.
- To activate "Secondary" keys, hold down (spacebar) while typing.
  - (right-ctrl) key also works as well.

| Default    | Primary        | Secondary                       |
| ---------- | -------------- | ------------------------------- |
| (spacebar) | (spacebar)     | N/A                             |
| q          | p              | j                               |
| w          | w              | m                               |
| e          | r              | b                               |
| r          | a              | ' (quote)                       |
| t          | f              | (tab)                           |
| a          | d              | v                               |
| s          | t              | c                               |
| d          | h              | l                               |
| f          | e              | z                               |
| g          | o              | q                               |
| z          | y              | x                               |
| x          | s              | g                               |
| c          | n              | k                               |
| v          | i              | (backspace or delete backwards) |
| b          | u              | (delete forward)                |
| (left-cmd) | N/A            | , (comma)                       |
| (left-alt) | (return/enter) | . (period)                      |

## Hardware Example

![alt text](./docs/mac_frogpad.jpg "Mac Frogpad keyboard (left hand)")

![alt text](./docs/windows_Frogpad_keyboard.jpg "Windows Frogpad keyboard (left hand)")

### Differences and Future Improvements (subject to change)

- The "i" and "u" keys as "Secondary" keys are normally the "App" (right-click menu) and "Cmd" keys, respectively, but the "Number" modifier hasn't yet been implemented, and the "backspace" and "delete" were much more useful, so Clark has v1 mapped to those as well.

- (left-shift) for "Shift"

  - For capital letters

- "Shift Lock" = (spacebar) + (left-shift)

  - Capitalize next letter without holding down (left-shift)
  - "CapsLock" = "Number" (left-cmd) + (left-shift)

- "Symbol", "SymbolLock", and "Symbol Hold"

  - hold down, tap once, and tap twice, respectively
  - "SymbolLock" for next keypress only

- Make room for "Number" (left-cmd) modifier key

  - (left-ctrl) = "Enter" and "." (period)
  - (left-alt) = "Symbol/SymbolLock" modifiers and "," (comma)

- "Number" (left-cmd)

  - Tap once = "NumLock" holding
  - \* 7 8 9 -
  - / 4 5 6 +
  - 0 1 2 3 .
  - Turns off while "Symbol" is user and turns back on afterwards

- Function keys

  - Hold down "Number" modifier (left-cmd or right-cmd)
  - Arrow keys
  - BkSpc and Delete
    - Make room for "App" and "Cmd" keys
  - PgUp, PgDn, Pause, Home, etc.
  - Alt and Ctrl modifiers wait for next keystroke

- "Cmd" key = (spacebar) + "u"

  - Tap once for next keystroke
  - aka "GUI"/"Windows" key

## Other Resources

- https://www.youtube.com/watch?v=TmzYovAMHE4
- http://www.frogpad.com/FrogPad/Support.html
- http://www.frogpad.com/FPInfo-SoftFrog.html
