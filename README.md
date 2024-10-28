Personal set of Obsidian snippets.

# Installation

Symlink snippets into your vault:

```sh
$ ln -s /path/to/obsidian-css-snippets/snippets /path/to/obsidian-vault/.obsidian/snippets
```

# Snippets

## `colours.css`

Definition of a personal palette of colours. Obsidian has [a set of predefined
colours](https://docs.obsidian.md/Reference/CSS+variables/Foundations/Colors)
but I didn't quite like these so I made my own set.

## `image-opts.css`

Modifiers that can be applied to images using pipes e.g.

```md
![[path/to/image.png|center]]
```

### Available modifiers

| CSS class      | Effect |
| -------------- | ------ |
| `center`       | Center image |
| `invert-dark`  | Invert image and rotate hue by 180 degrees on dark theme |
| `invert-light` | Invert image and rotate hue by 180 degrees on light theme |

## `sidebar.css`

Sidebar customisation. Based on
[Obsidian-Colored-Sidebar](https://github.com/CyanVoxel/Obsidian-Colored-Sidebar)
by CyanVoxel (MIT license).
