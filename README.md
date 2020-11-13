# Josh's Custom Keyboard Layout

Karabiner configuration for modifications to the [Halmak layout](https://github.com/MadRabbit/halmak) that I use.

I used Dvorak for one year before switching to Colemak. There are some Dvorak mappings that I like for programming, so I modded my layout to include them. I then switched to Halmak in 2019, and have used it for over a year - and love it. Here is an article I wrote about it: "[In Search of the Ultimate Keyboard Layout](https://joshwulf.com/blog/2019/11/ultimate-keyboard/)".

These modifications add the best Dvorak key mappings to Halmak. Mostly these are keys used in programming that Dvorak puts closer to the home row, with the Capslock key as a modifier to activate them. Semicolon and colon are reversed, because I don't use semicolons.

Use with a QWERTY coded keyboard, and the system keyboard set to Halmak.

## Koolertron Setup

1. Remap Caps Lock to Fn2 on Koolertron in the Koolertron setup app in Windows. Save this to the default profile.
2. Remap `keypad_num_lock` to `fn` in Simple Modifications in Karabiner.
3. Set System Keyboard to Halmak.

## Anne Pro 2 Setup

1. Open ObinsKit.
2. Import `AnnePro2/AnnePro2.json`.
3. Set System Keyboard to Halmak.

## Karabiner Setup

1. Install [Karabiner](https://pqrs.org/osx/karabiner/index.html).
2. `mkdir -p ~/.config/karabiner/assets/complex_modifications`
3. `cp Karabiner/* ~/.config/karabiner/assets/complex_modifications/`
4. Open Karabiner. Go to "Complex Modifications", click "Add rule".
5. Add the rules you want.
6. In "Simple Modifications", map `caps_lock` and `keypad_num_lock` to `fn`.
