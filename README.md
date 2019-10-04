# Josh's Custom Keyboard Layout

Karabiner configuration for modifications to the Colemak layout that I use.

I used Dvorak for one year before switching to Colemak. There are some Dvorak mappings that I like for programming, so I modded my layout to include them.

These modifications add the best Dvorak key mappings to Colemak. Mostly these are keys used in programming that Dvorak puts closer to the home row, with the Capslock key as a modifier to activate them. Semicolon and colon are reversed, because I don't use semicolons.

Use with a QWERTY coded keyboard, and the system keyboard set to Colemak.

## Remappings

![](layout/keyboard-layout.png)

Generated on [http://www.keyboard-layout-editor.com](http://www.keyboard-layout-editor.com). The file `layout/keyboard-layout.json` contains the mappings for that site.

## Koolertron Setup

1. Remap Caps Lock to Fn2 on Koolertron in the Koolertron setup app in Windows. Save this to the default profile.
2. Remap `keypad_num_lock` to `fn` in Simple Modifications.
3. Set System Keyboard to Colemak.

## Anne Pro 2 Setup

1. Open ObinsKit.
2. Import `AnnePro2/AnnePro2.json`.
3. Set System Keyboard to Colemak.
  
## Karabiner Setup

1. Install [Karabiner](https://pqrs.org/osx/karabiner/index.html).
2. `mkdir  -p ~/.config/karabiner/assets/complex_modifications`
3. `cp Karabiner/* ~/.config/karabiner/assets/complex_modifications/`
4. Open Karabiner. Go to "Complex Modifications", click "Add rule".
5. Add all the rules.


