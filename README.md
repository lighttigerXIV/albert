<p align="center">
  <img src="https://raw.githubusercontent.com/catppuccin/catppuccin/dev/assets/logos/logos/500x500_circle.png" width="90" />
  <h2 align="center">Style Guide</h2>
</p>

<p align="center">A guide on how to style and develop elements using the Catppuccin color palette!</p>

<p align="center">
  <img src="https://raw.githubusercontent.com/catppuccin/catppuccin/dev/assets/misc/sample.png"/>
</p>

# 🍉 Ports

## Creation

You can create ports using [this](https://github.com/catppuccin/template) public template as a blueprint. However, the problem with this is that they leave a _small_ tag under the repos' name that says "generated from <template>". To avoid this follow these instructions:

1. Create the repo and leave it empty
2. Add this template as a remote: `git remote add template git@github.com:catppuccin/template.git`
3. Pull from it: `git pull template main`
4. Delete the remote: `git remote remove template`

## Styling Rules

- The name of the repo must be the simplest version of the app's name (e.g `nvim` instead of `NeoVim`)
- Put the images under `assets/`. If there are a bunch of them consider [creating an empty branch](https://gist.github.com/joncardasis/e6494afd538a400722545163eb2e1fa5) (e.g. `assets`) and storing them there.
- Format repo description as "<allusive emoji> Catppuccin theme for AwesomeApp"
- Add `catppuccin` to the topics.
- Uppercase meta files (e.g. `README.md`)
- Don't add health files (like `CODE_OF_CONDUCTS` or `SUPPORT`), those are organization-wide files stored [here](https://github.com/catppuccin/.github).
- Emojis are _the way_, feel free to use them as much as you want.

# 🦊 User Interfaces

(WIP)

# 🍨 Code Editors

## Syntax

(WIP)
