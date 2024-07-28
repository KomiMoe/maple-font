# When will V7 become stable?

It is almost stable now.

As a side project during my weekends, I will release a new beta version to fix the bugs reported or encountered in my daily coding within 1-2 weeks, and do some work on the new website and build tools.

If everything goes well, the stable version will be released later this year.

# Maple Font (WIP)

Open source monospace & nerd font with round corner and ligatures.

Base on `Jetbrains Mono` and **much "Opinioned"**

![](https://github.com/subframe7536/maple-font/assets/78338239/19383849-6be1-4cfc-9b34-7b33fc047ecf)

- generated by [CodeImg](https://github.com/subframe7536/vscode-codeimg)
- Theme: [Maple](https://github.com/subframe7536/vscode-theme-maple)

## Features

- Round corner
- New shape of `@ $ % & Q a` and cursive italic `f i j k l x y`
- Large amount of ligatures
  - equal variants: `==` / `===` / `!=` / `!==` / `>=` / `<=`...
  - arrow variants: `->` / `=>` / `-->` / `==>` / `<->` / `<=>`...
  - xml variants: `</` / `/>` / `<>` / `</>` / `<!--`...
  - flow variants: `|>` / `||>` / `|||>` / `|||>` / `>=>` / `=>>`...
  - same characters: `++` / `--` / `&&` / `||` / `!!` / `??` / `..` / `::` / `########`...
  - plain text tag: `[TODO]` / `todo))` / `[FIXME]` / `fixme))`
    - for logger: `[TRACE]` / `[DEBUG]` / `[INFO]` / `[WARN]` / `[ERROR]` / `[FATAL]`
- Font features
  - zero: dot style `0`
  - cv01: Classic `@` / `$` / `&` / `Q` / `=>` / `->`
  - cv02: Alternative `a` (with top alarm)
  - cv03: Alternative `i` (without bottom left bar)
  - cv04: Alternative `l` (with bottom left bar) and `1` (without bottom bar)
  - cv98: Full width `…`(ellipsis) and `—`(emdash) support for Maple Mono NF CN
  - cv99: Traditional punctuations support for Maple Mono NF CN
  - ss01: Non-cursive italic style `f l i j x y`
  - ss02: Disable ligautures on equals like `==` / `!=` / `<=`
  - ss03: Ignore cases on all tags
  - ss04: Disable ligatures on `__`, `#__`, `***`

## Build

### Browser

WIP

### Local

clone the repo and run in your local machine.

```shell
git clone https://github.com/subframe7536/maple-font --depth 1 -b variable
pip install foundrytools-cli
python build.py
```

You can change config in `config.json`

Make sure you have `python3` and `pip` installed

- for custom `font-patcher` args, `font-forge` (and maybe `python3-fontforge` as well) is needed
- for `Ubuntu` or `Debian`, maybe `python-is-python3` is needed as well

```shell
pip install foundrytools-cli
python build.py
```

If you have trouble to install the dependencies, just create a new Github codespace on `variable` branch and run the commands there

## credit

- [Jetbrains Mono](https://github.com/JetBrains/JetBrainsMono)
- [Roboto Mono](https://github.com/googlefonts/RobotoMono)
- [Fira Code](https://github.com/tonsky/FiraCode)
- [Victor Mono](https://github.com/rubjo/victor-mono)
- [Commit Mono](https://github.com/eigilnikolajsen/commit-mono)
- [Code Sample](https://github.com/TheRenegadeCoder/sample-programs-website)
- [Nerd Font](https://github.com/ryanoasis/nerd-fonts)

## License

SIL Open Font License 1.1
