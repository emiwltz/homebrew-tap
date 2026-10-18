# emiwltz/homebrew-tap

Homebrew formulae for [something](https://github.com/emiwltz/something), a Mac app that sees every coding agent on
your Mac and gives HTML pages your agent writes a bridge to them.

```sh
brew install --HEAD emiwltz/tap/something
something
```

It builds from source on macOS 15 or later and needs Apple's Command Line Tools (`xcode-select --install`). No
version is tagged yet, so the formula builds the latest `main`.

The formula's source of truth is `packaging/homebrew/something.rb` in the something repository; this tap holds a
copy. The workflow here installs it the way a person would, on GitHub's fresh Macs.
