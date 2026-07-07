# Sapphire CLI (`sj`) — Releases

Public release binaries for **`sj`**, the Sapphire command-line client.

This repository hosts the downloadable, versioned release artifacts. The formula
in [`yelka-t/homebrew-tap`](https://github.com/yelka-t/homebrew-tap) points at the
archives published here, so `brew install` works on a clean machine with no
credentials.

## Install

```sh
brew install yelka-t/tap/sapphire-cli
```

macOS and Linux, on both Apple Silicon and x86-64. `jj` (Jujutsu) is installed
automatically as a dependency.

## What `sj` is

`sj` is a thin, transparent wrapper around `jj`: any `jj` command you run through
`sj` behaves exactly as if you ran `jj` directly. On top of that it adds
Sapphire-native commands — `sj login` and `sj logout` — for authenticating your
pushes to Sapphire.

Check your installed version:

```sh
sj --version
```

## Releases

Builds are published here automatically on each tagged release. Grab a specific
version from the [Releases](../../releases) page, or just use `brew` above to stay
current.
