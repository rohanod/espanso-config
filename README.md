# Rohan's Espanso Config

This repository hosts Espanso snippets that I use.

## Package

- `term-snippets`
- `script-numbers-plusminus-9`

## Install (external git repository)

Use Espanso's external package install flow:

```bash
espanso install {package_name} --git https://github.com/rohanod/espanso-config --external

espanso restart
```

## Install (local git repository)

Alternatively, you can clone this repository and install the packages locally:

1. Clone the repo
2. Run the following commands:

```bash
espanso install {package_name} \
  --git "file://{cloned repo path}" \
  --external \
  --force \
  --use-native-git

espanso restart
```
