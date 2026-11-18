# Brewfiles

Declarative Homebrew Bundle manifests for macOS, organized as `Brewfile.*`. CI validates all manifests, including a nightly build.

## Usage

```bash
cat Brewfile.* | brew bundle --file=-
```
