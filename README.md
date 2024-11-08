# macos-setup

## ⌨️ Keyboard

~~[birman](https://ilyabirman.net/typography-layout/)~~ - keyboard layout for useful characters on `option` layer

[agp layout](keyboard-agp.bundle) - my additions to birman layout.

<details><summary>What I changed</summary>

My keyboard has no F1-F12 keys, so I had to add `~` (tilde) and `` ` `` (backtick) symbols myself.

Also I changed `№` symbol to `#` for md headers in russian layout

</details>

## 🖥️ Software

**[Raycast](https://www.raycast.com/hey/08c2e9c0)** - GOAT for spotlight magic with plugins

Raycast with hotkeys for clipboard management

<details><summary>Alternatives considered</summary>
  - ~~used [Paste](https://pasteapp.io/) before~~
  - ~~(or https://github.com/p0deje/Maccy if you need free)~~
  - ~~PastePal?~~
</details>

Raycast for window movement. `cmd+option+ctrl+arrows` to move windows around

<details><summary>alternatives</summary>

[Shiftit](https://github.com/fikovnik/ShiftIt) - used before Raycast
[Rectangle](https://rectangleapp.com/) - never used

</details>

[Reveal](https://revealapp.com/) - proper UI debug for iOS with live edit and accessibility inspection

Misc Software:

- 1Password
- Telegram
- Slack
- [tldraw](tldraw.com) for drawing
  - or FigJam

## 🔨 Xcode

[Xcodes app](https://www.xcodes.app/) to manage Xcode versions. Uses aria2 to make download 4+ times faster

🔌 plugins:

#### Sort imports or anything else

[xcsort](https://apps.apple.com/ru/app/xcsort/id1153337296?l=en&mt=12) + <kbd>Shift+CMD+6</kbd>

#### Convert one line to multiline

~~[Multiliner](https://github.com/aheze/Multiliner) + <kbd>Shift+CMD+X</kbd>~~

[xcode-multi-line-func](https://github.com/angeria/xcode-multi-line-func) + <kbd>Shift+CMD+X</kbd>

<details><summary>Почему xcode-multi-line-func лучше чем Multiliner</summary>

```swift
// input
CGRect(origin: .zero, size: CGSize(width: flagIconSize, height: flagIconSize))

// Multiliner result
CGRect(
  origin: .zero,
  size: CGSize(width: flagIconSize, // why?
  height: flagIconSize)
)

// xcode-multi-line-func result
CGRect(
  origin: .zero,
  size: CGSize(width: flagIconSize, height: flagIconSize) // what I wanted!
)
```

</details>

Xcode theme is [Charmed](https://github.com/CypherPoet/charmed-dark-xcode-theme)

## 💻 Terminal

[dotfiles repo with config](https://github.com/AgapovOne/dotfiles)

[kitty](https://sw.kovidgoyal.net/kitty/quickstart/)

<details><summary>alternatives</summary>

- iterm2 is slow
- waiting for ghostty

</details>

zsh!

<details><summary>Why zsh?</summary>

used 🐟 fish before, but sharing functions and workflow with colleagues is easier with zsh

fish still better for interactions.

</details>

current [.zshrc](https://github.com/AgapovOne/dotfiles/blob/main/dot_zshrc)

- [bat - cat alternative](https://github.com/sharkdp/bat)
- [tldr - man alternative](https://tldr.sh)
- [zoxide - z jump](https://github.com/ajeetdsouza/zoxide)
- [vhs](https://github.com/charmbracelet/vhs)(beautiful) or [asciinema](https://github.com/asciinema/asciinema)(lightweight) for gif recording

<details>
<summary>should try myself</summary>

- curl -> [httpie](https://github.com/httpie/httpie)?
- cat -> [bat](https://github.com/sharkdp/bat)?
- diff -> [delta](https://github.com/dandavison/delta)
- [jq](https://github.com/jqlang/jq) -> [fx](https://github.com/antonmedv/fx)

inspiration: [habr article](https://habr.com/ru/company/redmadrobot/blog/538446/)

</details>

## 💻 Code Editor

[Zed editor](https://zed.dev)!

AI + speed + minimalism

vim plugins!

<details><summary>History. Why not neovim or vscode?</summary>

VS Code

// TODO: Story about Ruby env, bloated plugin system.

Previously used neovim and liked it.

// TODO: Story about Python env & ugly Markdown plugins

[config](https://github.com/AgapovOne/lazyvim) was a modified version of [lazyvim](https://www.lazyvim.org/)

</details>
