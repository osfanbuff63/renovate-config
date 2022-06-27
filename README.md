# renovate-config

## About

My central renovate config repo. Feel free to use this for anything you want, as I've licensed this under the CC0 license.

## Usage

1. Install the [Renovate app](https://github.com/marketplace/renovate) onto your account, and give it access to at least the repo you want it to work on.
2. Create a `renovate.json` or `renovate.json5` (I recommend json5 over json for comments mostly) in either the root directory or the `.github` directory with these contents:

```json5
{
  "extends": ["github>osfanbuff63/renovate-config:default.json5"]
}
```
If Renovate created a PR for a `renovate.json` file and it doesn't get closed, you can close it once this file is created. Or, create it on the branch of Renovate's PR (usually `renovate/configure`) instead.
