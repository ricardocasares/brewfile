# brewfile

My [Homebrew Bundle](https://github.com/Homebrew/homebrew-bundle) setup for macOS.

## Contents

- **Shell:** fish
- **Fonts:** Paper Mono
- **Dev tools:** mise
- **Apps:** Ghostty, Google Chrome, Zed, Visual Studio Code, Tinycast

## Usage

Install Homebrew, then from this directory:

```sh
brew bundle
```

To check what's missing without installing:

```sh
brew bundle check
```

To dump the currently installed packages back into the Brewfile:

```sh
brew bundle dump --force
```
