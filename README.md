# Rohan's Espanso Config

This repository hosts Espanso snippets that I use.

## Package

- `term-snippets`
- `script-numbers-plusminus-9`

## Install (external git repository)

Use Espanso's external package install flow:

`espanso install {package_name} --git https://github.com/rohanod/espanso-config --external`

## Install (local git repository)

Alternatively, you can clone this repository and install the packages locally:

1. Clone the repo
2. Navigate to the repo
3. Run the following commands:

```bash
espanso install {package_name} \
  --git "file://$PWD" \
  --external \
  --force \
  --use-native-git

espanso restart
```
