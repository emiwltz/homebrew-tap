# emiwltz/homebrew-tap

Homebrew formulae for [something](https://github.com/emiwltz/something), a Mac app that sees every coding agent on
your Mac and gives HTML pages your agent writes a bridge to them.

```sh
brew install emiwltz/tap/something
something
```

It needs macOS 15 or later. Homebrew pours a version built in advance (a bottle) for macOS 26, macOS 15 and Intel
Macs: no Xcode, no build. `brew install --HEAD emiwltz/tap/something` builds the latest `main` from source instead,
with Apple's Command Line Tools.

The formula's source of truth is `packaging/homebrew/something.rb` in the something repository; this tap holds a
copy. The workflows here build the bottles for each pull request (tests.yml), publish them (publish.yml, by hand),
and install something the way a person would on GitHub's fresh Macs (install.yml).
