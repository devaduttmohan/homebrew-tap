# devaduttmohan/tap

Homebrew casks for [Notch](https://github.com/devaduttmohan/notch), a Dynamic Island for the MacBook notch.

```sh
brew install --cask devaduttmohan/tap/notch
```

That installs Notch.app in Applications and puts `notchctl` on your PATH. Notch updates
itself from Customise › About; `brew upgrade --greedy` also works. Apple silicon, macOS 14
or later.

`Casks/notch.rb` is written by Notch's `bin/release` with each release.
