# macos-setup

## ⌨️ Keyboard

- ~~birman~~ [agp layout](keyboard-agp.bundle)

## 🖥️ Software

- Raycast for best spotlight magic with plugins
- Raycast with hotkeys for clipboard management
  - Used Paste before
  - (or https://github.com/p0deje/Maccy if you need free)
  - PastePal?
- Raycast for window movement
  - used Shiftit before
- Reveal
- ~~Visual Studio Code~~ neovim
- 1Password
- Telegram
- Slack
- [tldraw](tldraw.com) for drawing
  - or FigJam

## 🔨 Xcode

[Downloader](https://github.com/vineetchoudhary/Downloader-for-Apple-Developers)

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


#### 🧮 theme: 
- [Charmed](https://github.com/CypherPoet/charmed-dark-xcode-theme)

## 💻 Terminal

[dotfiles repo with config](https://github.com/AgapovOne/dotfiles)

~~iTerm~~
[kitty](https://sw.kovidgoyal.net/kitty/quickstart/)

### 🐟 fish

- inspiration [awsm.fish](https://github.com/jorgebucaran/awsm.fish.git)
- [.config/fish](https://github.com/AgapovOne/macos-setup/tree/main/fish) contents

- [bat - cat alternative](https://github.com/sharkdp/bat)
- [tldr - man alternative](https://tldr.sh)
- [zoxide - z jump](https://github.com/ajeetdsouza/zoxide)

<details>
<summary>should try myself</summary>

- curl -> [httpie](https://github.com/httpie/httpie)?
- cat -> [bat](https://github.com/sharkdp/bat)?
- diff -> [delta](https://github.com/dandavison/delta)
- [jq](https://github.com/jqlang/jq)

inspiration: [habr article](https://habr.com/ru/company/redmadrobot/blog/538446/)

</details>

### 💻 neovim!

[current config](https://github.com/AgapovOne/lazyvim) is modified [lazyvim](https://www.lazyvim.org/)
