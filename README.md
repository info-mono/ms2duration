<h1 align="center"><code>ms2duration</code></h1>
<p align="center">Milliseconds to duration converter</p>
<p align="center"><a href="https://github.com/info-mono/ms2duration/blob/main/LICENSE"><img src="https://img.shields.io/github/license/info-mono/ms2duration?labelColor=383838&color=585858&style=for-the-badge" alt="License: GPL-3.0"></a> <a href="https://gist.github.com/NNBnh/9ef453aba3efce26046e0d3119dab5a7#development-completed"><img src="https://img.shields.io/badge/development-completed-%23585858.svg?labelColor=383838&style=for-the-badge&logoColor=FFFFFF" alt="Development completed"></a></p>

## 💡 About
`ms2duration` is a tool to convert milliseconds to a full durations represent a length of time written in [`portable sh`](https://github.com/dylanaraps/pure-sh-bible) inspired by [Nushell's duration data type](https://www.nushell.sh/book/types_of_data.html#duration) and [Starship's Command duration module](https://starship.rs/config/#command-duration).

## 🚀 Setup
### 🧾 Dependencies
- [Unix commands](https://en.wikipedia.org/wiki/List_of_Unix_commands) to process

### 📥 Installation
#### 🔧 Manually
Option 1: using `curl`
```sh
curl https://raw.githubusercontent.com/info-mono/ms2duration/main/bin/ms2duration > ~/.local/bin/ms2duration
chmod +x ~/.local/bin/ms2duration
```

Option 2: using `git`
```sh
git clone https://github.com/info-mono/ms2duration.git ~/.local/share/ms2duration
ln -s ~/.local/share/ms2duration/bin/ms2duration ~/.local/bin/ms2duration
```

#### 📦 Package manager
For [`bpkg`](https://github.com/bpkg/bpkg) user:
```sh
bpkg install info-mono/ms2duration
```

For [Basher](https://github.com/bpkg/bpkg) user:
```sh
basher install info-mono/ms2duration
```

> *If you can and want to port ms2duration to other package managers, feel free to do so.*

## ⌨️ Usage
Run 'ms2duration' in the terminal:
```sh
ms2duration MILLISECONDS
```

## 💌 Credits
Special thanks to:
- [**Nushell**](https://www.nushell.sh) by [it's contributors](https://github.com/nushell/nushell/graphs/contributors)
- [**Starship**](https://starship.rs) by [it's contributors](https://github.com/starship/starship/graphs/contributors)

<br><br><br><br>

---

> <h1 align="center">Made with ❤️ by <a href="https://github.com/info-mono"><code>@info-mono</code></a></h1>
>
> <p align="center"><a href="https://www.buymeacoffee.com/nnbnh"><img src="https://img.shields.io/badge/buy_me_a_coffee%20-%23F7CA88.svg?logo=buy-me-a-coffee&logoColor=333333&style=for-the-badge" alt="Buy Me a Coffee"></a></p>
