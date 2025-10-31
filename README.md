# Kanemu Tap-for-ventura

homebrew tap for macOS 13 (Ventura)

## How do I install these formulae?

`brew install kanemu/tap-for-ventura/<formula>`

Or `brew tap kanemu/tap-for-ventura` and then `brew install <formula>`.

Or, in a `brew bundle` `Brewfile`:

```ruby
tap "kanemu/tap-for-ventura"
brew "<formula>"
```

### Example: Install `imagemagick@7.1.1.47`

Install directly:

```sh
brew install kanemu/tap-for-ventura/imagemagick@7.1.1.47
```

Or tap first, then install:

```sh
brew tap kanemu/tap-for-ventura
brew install imagemagick@7.1.1.47
```

In a `Brewfile`:

```ruby
tap "kanemu/tap-for-ventura"
brew "imagemagick@7.1.1.47"
```

## Documentation

`brew help`, `man brew` or check [Homebrew's documentation](https://docs.brew.sh).
