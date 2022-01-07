<h3 align="center">
	<img src="https://raw.githubusercontent.com/catppuccin/catppuccin/dev/assets/logos/exports/1544x1544_circle.png" width="100" alt="Logo"/><br/>
	<img src="https://raw.githubusercontent.com/catppuccin/catppuccin/dev/assets/misc/transparent.png" height="30" width="0px"/>
	Catppuccin's Style Guide
	<img src="https://raw.githubusercontent.com/catppuccin/catppuccin/dev/assets/misc/transparent.png" height="30" width="0px"/>
</h3>

<p align="center">
    <a href="https://github.com/catppuccin/style-guide/stargazers"><img src="https://img.shields.io/github/stars/catppuccin/style-guide?colorA=1e1e28&colorB=c9cbff&style=for-the-badge&logo=starship style=for-the-badge"></a>
    <a href="https://github.com/catppuccin/style-guide/issues"><img src="https://img.shields.io/github/issues/catppuccin/style-guide?colorA=1e1e28&colorB=f7be95&style=for-the-badge"></a>
    <a href="https://github.com/catppuccin/style-guide/contributors"><img src="https://img.shields.io/github/contributors/catppuccin/style-guide?colorA=1e1e28&colorB=b1e1a6&style=for-the-badge"></a>
</p>

<p align="center">
	A guide on how to properly style and implement the Catppuccin palette for various things such as terminal emulators, user interfaces, code editors, etc...
</p>

# 🍉 Ports

## Creation

You can create ports using [this](https://github.com/catppuccin/template) public template as a blueprint. However, you shouldn't create them the traditional way (by clicking **Use this template**), because this leaves a _small_ tag under the repos' name that says `generated from <template>`. To avoid this, follow the instructions below:

1. Create the repo and leave it empty
2. Add this template as a remote: `git remote add template git@github.com:catppuccin/template.git`
3. Pull from it: `git pull template main`
4. Delete the remote: `git remote remove template`

## Styling Rules

-   The name of the repo must be the simplest version of the app's name (e.g `style-guide` instead of `NeoVim`)
-   Put the images under `assets/`. If there are a bunch of them consider [creating an empty branch](https://gist.github.com/joncardasis/e6494afd538a400722545163eb2e1fa5) (e.g. `assets`) and storing them there.
-   Format the repo's description as "`<allusive emoji>` Vibrant pastel theme for App"
-   Add `catppuccin` to the topics.
-   Uppercase meta files (e.g. `README.md`)
-   Don't add health files (like `CODE_OF_CONDUCTS.md` or `SUPPORT.md`), those are organization-wide files stored [here](https://github.com/catppuccin/.github).
-   Emojis are _the way_, feel free to use them as much as you want.

# 🦄 General Standard

These are general use cases for most of the palette relevant for user interfaces. The `function` expresses a very vague use-case of a color and the `scope example` how it is generally used:

| Function     | Scope Examples                     | Color     |
| ------------ | ---------------------------------- | --------- |
| `base`       | `splits`; `sign columns`           | black0    |
| `surface`    | `x`                                | black1    |
| `top`        | `background`                       | black2    |
| `overlay`    | `floating elements`; `cursor line` | black3    |
| `standout`   | `searches`                         | black4    |
| `subtle`     | `comments`                         | gray0     |
| `active`     | `foreground`                       | white     |
| `inactive`   | `x`                                | gray2     |
| `projection` | `cursors`                          | rosewater |

# 🎃 Terminals

## Main

#### Normal

| Scope    | Color  |
| -------- | ------ |
| `color0` | gray0  |
| `color1` | red    |
| `color2` | green  |
| `color3` | yellow |
| `color4` | blue   |
| `color5` | mauve  |
| `color6` | pink   |
| `color7` | white  |

#### Bright

| Scope     | Color     |
| --------- | --------- |
| `color8`  | gray1     |
| `color9`  | maroon    |
| `color10` | teal      |
| `color11` | yellow    |
| `color12` | lavender  |
| `color13` | mauve     |
| `color14` | pink      |
| `color15` | rosewater |

#### Extended Colors

| Scope     | Color    |
| --------- | -------- |
| `color16` | peach    |
| `color17` | flamingo |

## UI

#### Misc

| Scope         | Color     |
| ------------- | --------- |
| `cursor`      | rosewatet |
| `cursor text` | black2    |
| `urls`        | rosewater |
| `cursor`      | rosewatet |

#### Window

| Scope             | Color    |
| ----------------- | -------- |
| `active border`   | lavender |
| `inactive border` | black4   |
| `bell border`     | yellow   |

#### Tabs

| Scope                     | Color  |
| ------------------------- | ------ |
| `active tab foreground`   | pink   |
| `active tab background`   | black4 |
| `inactive tab foreground` | white  |
| `inactive tab background` | black2 |

## Syntax

| Scope                  | Color  |
| ---------------------- | ------ |
| `foreground`           | white  |
| `background`           | black2 |
| `selection foreground` | white  |
| `selection background` | black2 |
| `mark1 foreground`     | black2 |
| `mark1 background`     | blue   |
| `mark2 foreground`     | black2 |
| `mark2 background`     | pink   |
| `mark3 foreground`     | black2 |
| `mark3 background`     | sky    |

# 🍨 Code Editors

## Syntax

(WIP)
