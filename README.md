# Animal-Intrusion-Detection
We address the alarming rise of animal-inflicted harm in residential areas, proposing an image classification-based identification system for enhanced safety.  The research highlights the urgent need for improved safety measures, especially in residential lifts, to protect children and the elderly from stray animal attacks.
  <style>
      @keyframes glow {
        0% {
          fill: white;
        }
        50% {
          fill: red;
        }
        100% {
          fill: white;
        }
      }

      .glowing-svg path {
        animation: glow 2s infinite alternate;
      }
    </style>

<div class="glowing-svg">
      <svg
        version="1.1"
        xmlns="http://www.w3.org/2000/svg"
        xmlns:xlink="http://www.w3.org/1999/xlink"
        x="0px"
        y="0px"
        viewBox="0 0 256 256"
        enable-background="new 0 0 256 256"
        xml:space="preserve"
      >
        <path
          fill="#FFFFFF"
          d="M25.4,186.6c1.7-0.5,34.3-11.2,34.3-11.2s-3.1-9.9-3.5-11.8c-0.5-2.2-1.3-2.2-1.9-2.3h-0.2L20.5,161C20.5,161,24.3,180.2,25.4,186.6z"
        />
        <path
          fill="#FFFFFF"
          d="M105,175.1c0,0-76.5,31.7-78.4,32.3c-0.8,4.9-4.4,20.3-4.4,20.3h32.6c0,0,2.8,0,3.3-2.1c2.2-8.9,3.6-17,3.8-17.3c0.2-0.8,0.7-2,2.1-2.7c0.7-0.4,56.2-28.5,56.2-28.5s0-5.6,0-9.5H105V175.1z"
        />
        <path
          fill="#FFFFFF"
          d="M42.5,101.9c0-3.4,0-5.8,0-7.3C37.1,92,20,83.2,16.3,81.4c0,3.4,0,7.2,0,7.2v0c0,0.1,0,0.2,0,0.3c0,1.2,0.3,3.7,1.6,4.4c1.9,1.1,20.7,11.1,24.7,13.2c0-0.7,0-1.4,0-2.1c0,0,0-0.1,0-0.1C42.5,103.5,42.5,102.7,42.5,101.9z"
        />
        <path
          fill="#FFFFFF"
          d="M245.9,101.4c-0.1-0.3-0.5-0.6-1.1-0.9c-2.7-0.1-15.1-0.7-28.4-1.3c-0.6,10.3-1.5,27.9-1.8,29.1c-0.1,0.7-1.7,3.8-3.9,7.8c0.6,0.4,1.1,0.7,1.4,0.9c1.3,0.7,3.7,1.1,4.8-0.1c0.7-0.8,4.7-5.6,9.3-11.1c6.6-7.9,14-16.7,15.8-18.7l1.3-1.5c1.8-2,2.5-2.8,2.5-3.7C246,101.7,246,101.6,245.9,101.4z"
        />
        <path
          fill="#FFFFFF"
          d="M98.2,146.1c-3.3,5.2-7.8,8.1-12.6,8.1c-2.3,0-4.5-0.7-6.5-1.9c0,3.3,0,6.3,0,7.3c3,0,38,0,41,0c0-0.8,0-2.7,0-5c-6.1-3.1-13.4-6.8-20.8-10.6C99,144.7,98.6,145.4,98.2,146.1z"
        />
        <path
          fill="#FFFFFF"
          d="M95.3,144.3c0.4-0.6,0.7-1.2,1-1.8c-8.5-4.3-17.2-8.7-24.7-12.6c0.7,11.7,6.7,20.9,14,20.9C89.2,150.8,92.7,148.5,95.3,144.3z"
        />
        <path
          fill="#FFFFFF"
          d="M128.9,137.3l-0.6-0.4c-1.3-0.6-50.8-25-82.4-40.6c0,1.4,0,3.2,0,5.6c0,0.8,0,1.6,0,2.6c0,0,0,0.1,0,0.1c0,9.1,3,10.3,4.6,10.9c2.1,0.9,69.7,35.3,79.9,40.6c0-0.2,0-0.5,0-0.8l0.5-17.1C130.1,137.9,129.4,137.5,128.9,137.3z"
        />
        <path
          fill="#FFFFFF"
          d="M138.4,129.3c3.7-4.8,20.9-24.7,21.8-25.7c0.5-0.7,8.1-10.2,21.2-9.5c9.2,0.5,39.8,2,55.2,2.7c-2.1-0.9-3.9-1.7-3.9-1.7L210.1,85l-7-3.1l-13.6-6c-7.9-3.5-16.1-7.2-24.2-10.7l-14.7-6.6c-7.1-3.2-14.3-6.4-21.6-9.5c-3.3-1.3-14.8-6.6-17.9-8c-6.5-2.9-13.2-5.9-20.2-8.1c-1.8-0.6-10-2.1-12-2.3l-19.6-1c-11.4-0.6-24.3-1.2-27.2-1.4c-8.8-0.6-13,0-14.5,4.8c-0.8,2.7-5,24.3-6.5,30.1c-0.4,1.4-0.6,2.6-0.6,3.5c0,3.3,2,4.2,4.3,5.3l-1,0.5c0.9,0.5,114.2,56.2,116.5,57.2c0,0,0,0,0,0l0,0l0,0l0.9,0.5C134.8,131.1,136,131.7,138.4,129.3z"
        />
        <path
          fill="#FFFFFF"
          d="M181.2,97.4c-11.4-0.6-18.3,8.1-18.4,8.2l0,0c-0.2,0.2-21,25.3-24.5,29.8l0,0.1l-0.1,0.1c-1.4,1.5-2.8,2.2-4,2.6c-0.1,6.4-0.4,17-0.4,17c0,0.1,0,0.2,0,0.2c0,2.3,0.9,3.7,5.4,4c2.6,0.2,44.7,1.4,47.9,1.4c2.6,0,4.7-0.3,7-3c2.7-3.2,16.6-28.2,17.5-30.4c0.2-1.4,1-16.1,1.7-28.6C200,98.3,186.8,97.7,181.2,97.4z M193.6,118.5c-1.1,3.3-5.8,19.6-5.8,19.6s-0.6,2.9-2.1,3.8c-1.4,1-4.2,0.7-4.2,0.7c-2.7-0.1-5.5-0.2-8.2-0.3c-4.5-0.1-15.4-0.6-16.4-0.6c-1,0-3.1-0.5-3.5-1.6c-0.6-1.4,0-3.2,0.4-4.6c0.5-1.9,1.1-3.8,1.7-5.7c1.1-4.0,2.3-7.9,3.5-11.9c0.6-2,0.7-3.9,2.5-5.4c1.8-1.5,4.1-1.3,6.3-1.3c2.1,0,4.3,0.1,6.4,0.1c4.5,0.1,8.9,0.4,13.4,0.6c1.3,0.1,2.7,0.1,4,0.2C195.1,112.4,194.7,115.1,193.6,118.5z"
        />
        <path
          fill="#FFFFFF"
          d="M79.1,167.5c0,3.4,0,5.3,0,5.3l-58.2,20l-0.3-1.8c-1.9-10.7-4.8-27.7-5.3-30H10c0,8.2,0,59.4,0,66.8h6.4c0.7-4.4,4.4-20.7,4.5-21l0.2-1c0,0,78.4-32.3,80.7-33.1c0-1.5,0-2.2,0-5.2H79.1L79.1,167.5z"
        />
      </svg>
    </div>

# themer ![GitHub Workflow Status (main branch)].

`themer` takes a set of colors and generates [editor themes](#editorsides), [terminal themes](#terminals), [themes for other apps](#other-apps), and [desktop wallpapers](#wallpapers).

![visual description]("https://drive.google.com/file/d/1dA0aBAxv7RES01_1jijj8H_4jtMXrhbC/view?usp=sharing")

## Table of contents

- [Getting started](#getting-started)
- [CLI documentation](#cli-documentation)
  - [Installation](#installation)
  - [Usage](#usage)
  - [Example workflow: dotfiles integration](#example-workflow-dotfiles-integration)
  - [Example workflow: npx](#example-workflow-npx)
  - [Example workflow: using base16 schemes with Themer](#example-workflow-using-base16-schemes-with-themer)
- [API documentation](#api-documentation)
  - [Installation](#installation-1)
  - [Interface](#interface)
  - [Create custom `ColorSet`s](#create-custom-colorsets)
    - [Color mappings](#color-mappings)
  - [Create custom `Template`s](#create-custom-templates)
- [Themer color sets](#themer-color-sets)
  - [Premium color sets](#premium-color-sets)
  - [Original color sets](#original-color-sets)
  - [Ports from third-party themes](#ports-from-third-party-themes)
- [Themer templates](#themer-templates)
  - [Terminals](#terminals)
  - [Editors/IDEs](#editorsides)
  - [Other apps](#other-apps)
  - [Wallpapers](#wallpapers)
- [Prior art](#prior-art)
- [Contributing](#contributing)
- [Next steps](#next-steps)
  - [Join the community](#join-the-community)
  - [Support `themer`](#support-themer)

## Getting started

There are a few different ways to level up your development setup with `themer`:

1. **Web-based graphical user interface.** `themer` has an official progressive web app located at [themer.dev](https://themer.dev).
2. **Command-line interface.** `themer` can be used to generate themes on the CLI, see the [CLI docs](#cli-documentation) below.
3. **Application programming interface.** `themer` exposes a JavaScript API (complete with TypeScript type definitions) for programmatic use; see the [API docs](#api-documentation) below.

Feature comparison:

|                               | Web UI         | CLI/API  |
| ----------------------------- | -------------- | -------- |
| Instant preview               | ✅             | ❌       |
| Premium color sets            | ✅             | ❌       |
| Supported color format        | Any CSS format | Hex only |
| Wallpaper output format       | PNG + SVG      | SVG only |
| Seamless dotfiles integration | ❌             | ✅       |

## CLI documentation

As of V5, `themer` is distributed as a single TypeScript/JavaScript package containing all built-in color sets and templates for ease of use—but still supports the use of [custom color sets](#create-custom-colorsets) or [templates](#create-custom-templates).

### Installation

Install `themer` from npm with your JavaScript package manager of choice.

```sh
npm install themer
```

`themer` can also be installed globally. Or if you prefer not to install it at all, [it can be used with `npx`](#example-workflow-npx).

### Usage

```sh
themer [options]
```

Pass `themer` one or more color sets, as many templates as you wish, as many wallpaper resolutions as you wish, and an output directory.

| Option                                                      | Description                                                    | Default value                | Available options                                                                                                                                                                                              |
| ----------------------------------------------------------- | -------------------------------------------------------------- | ---------------------------- | -------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------- |
| `-c, --color-set <built-in color set name or file path...>` | the color set(s) to render                                     | `default`                    | [color set name](#themer-color-sets), or path to JS file containing a [custom color set](#create-custom-colorsets), or a file path to a [base16 yaml file](#example-workflow-using-base16-schemes-with-themer) |
| `-t, --template <built-in template name or file path...>`   | the theme template(s) to render                                | `*` (all built-in templates) | [template name](#themer-templates), or path to JS file containing a [custom template](#create-custom-templates)                                                                                                |
| `-s, --size <wallpaper resolution...>`                      | resolution to render in pixels, in the format [width]x[height] | `2880x1800`                  | any                                                                                                                                                                                                            |
| `-o, --output <path>`                                       | the output directory                                           | `themer-output`              | any                                                                                                                                                                                                            |

`--color-set`, `--template`, and `--size` may be specified multiple times.

Your generated theme files, as well as a README on how to install them, will be written to the output directory.

### Example workflow: dotfiles integration

Say you wanted to generate a vim theme and desktop background using `themer`'s default color set. First, install `themer`:

```sh
cd my-dotfiles
npm install themer
```

Then edit your `package.json`:

```json
{
  "scripts": {
    "build": "themer -c default -t vim -t vim-lightline -t hyper -t wallpaper-block-wave -o gen"
  }
}
```

Then run your new script:

```sh
npm run build
```

Now check the `gen/` folder for your generated files. Here's the result:

![example usage result](https://cdn.jsdelivr.net/gh/themerdev/themer@a186c8585721d5defbf4cb1bc94165144d4dd35a/assets/example-usage.png)

### Example workflow: npx

This command will generate a Vim theme and the Block Wave wallpaper, using `themer`'s default color set, and put them in a folder called `output`:

```sh
npx themer -c default -t vim -t wallpaper-block-wave -o output
```

### Example workflow: using base16 schemes with Themer

In place of a themer color set, you can also provide `themer` with any base16 scheme YAML file.

```
themer --color-set path/to/base16-scheme.yml ...
```

Refer to the [base16 repository](https://github.com/chriskempson/base16#scheme-repositories) for a list of base16 schemes.

## API documentation

`themer` ships with a JavaScript API (with TypeScript type definitions) for use in programmatically generating themes.

### Installation

```sh
npm install themer
```

### Interface

`themer`'s default export is an [async generator function](https://developer.mozilla.org/en-US/docs/Web/JavaScript/Reference/Statements/async_function*) that takes three arguments:

1. An array of [`ColorSet` objects](#create-custom-colorsets), or string identifiers of [`themer`'s built-in color sets](#themer-color-sets)
2. An array of [`Template` objects](#create-custom-templates), or string identifiers of [`themer`'s built-in templates](#themer-templates)
3. A `RenderOptions` object used to specify the resolution of the outputted wallpaper images

The objects yielded by the generator are `OutputFile`s.

```ts
import themer from "themer";
import myColors from "./my-colors";
import myTemplate from "./my-template";

// Example usage: generate Vim themes, 1440x900 wallpapers, and custom files
// from themer's "Night Sky" color set and a custom color set.
const files = themer(
  ["night-sky", myColors],
  ["vim", "wallpaper-block-wave", myTemplate],
  { wallpaperSizes: [{ width: 1440, height: 900 }] }
);

for await (const file of files) {
  // ...
}
```

### Create custom `ColorSet`s

```ts
import type { ColorSet } from "themer";

const myColorSet: ColorSet = {
  // Color sets should provide a human-readable name.
  name: "My Color Set",

  // Color sets can define a dark variant, a light variant, or both.
  // Each variant provides two or eight shades and eight accent colors in hex format.
  variants: {
    // In a dark variant, shade0 should be the darkest and shade7 should be
    // the lightest.
    dark: {
      shade0: "#333333",
      // Note: you can define shades 1 through 6 yourself, or you can omit
      // them; if omitted, they will be calculated automatically by
      // interpolating between shade0 and shade7.
      shade7: "#eeeeee",
      accent0: "#ff4050",
      accent1: "#f28144",
      accent2: "#ffd24a",
      accent3: "#a4cc35",
      accent4: "#26c99e",
      accent5: "#66bfff",
      accent6: "#cc78fa",
      accent7: "#f553bf",
    },

    // In a light variant, shade7 should be the darkest and shade0 should be
    // the lightest.
    light: {
      shade0: "#eeeeee",
      shade7: "#333333",
      accent0: "#f03e4d",
      accent1: "#f37735",
      accent2: "#eeba21",
      accent3: "#97bd2d",
      accent4: "#1fc598",
      accent5: "#53a6e1",
      accent6: "#bf65f0",
      accent7: "#ee4eb8",
    },
  },
};

export default myColorSet;
```

_Pro Tip: you can use [`themer`'s Web UI](https://themer.dev) to more easily select your colors, then click the "Download" button to generate a `colors.js` file in the correct format. With the Web UI, you can also input any valid CSS color format (keyword, HSL, RGB, etc.) and it will automatically convert the color to hex for you._

#### Color mappings

To help you choose colors for your own color set, this is approximately how most `themer` templates will utilize your colors:

| Color Key | Typical Usage             | Conventional Color\* |
| --------- | ------------------------- | -------------------- |
| `accent0` | error, VCS deletion       | Red                  |
| `accent1` | syntax                    | Orange               |
| `accent2` | warning, VCS modification | Yellow               |
| `accent3` | success, VCS addition     | Green                |
| `accent4` | syntax                    | Cyan                 |
| `accent5` | syntax                    | Blue                 |
| `accent6` | syntax, caret/cursor      |                      |
| `accent7` | syntax, special           | Magenta              |
| `shade0`  | background color          |                      |
| `shade1`  | UI                        |                      |
| `shade2`  | UI, text selection        |                      |
| `shade3`  | UI, code comments         |                      |
| `shade4`  | UI                        |                      |
| `shade5`  | UI                        |                      |
| `shade6`  | foreground text           |                      |
| `shade7`  | foreground text           |                      |

_\*Conventional color is suggested for consistency with ANSI color names in terminal themes, but is not a hard requirement._

See [`themer`'s Web UI](https://themer.dev) for a more visual representation of the color mappings.

### Create custom `Template`s

```ts
import type { Template } from "themer";

const template: Template = {
  // Templates should provide a human-readable name.
  name: "My Template",

  // The render async generator function takes a color set and the render
  // options, and yields one or more output files. The color set is fully
  // expanded (e.g., if the color set did not include shades 1 through 6
  // when originally authored, those intermediary shades will have already
  // been calculated and included).
  render: async function* (colorSet, options) {
    // The yielded output file has two properties: a string path (relative)
    // and a Buffer of the file's content.
    yield {
      path: "my-file.txt",
      content: Buffer.from("Hello, world!", "utf8"),
    };
  },

  // The renderInstructions function takes an array of paths generated from
  // the render function and should return a Markdown string, which will be
  // included in the generated README.md file.
  renderInstructions: (paths) =>
    `Copy the files (${paths.join(" and ")}) to your home directory.`,
};

export default template;
```

## Themer color sets

### Premium color sets

(Only available on [themer.dev](https://themer.dev).)

| Name                                          | Dark Preview                                                                                                                                           | Light Preview                                                                                                                                            |
| --------------------------------------------- | ------------------------------------------------------------------------------------------------------------------------------------------------------ | -------------------------------------------------------------------------------------------------------------------------------------------------------- |
| [Jamstacker](https://themer.dev/jamstacker)   | ![Jamstacker dark preview](https://cdn.jsdelivr.net/gh/themerdev/themer@bd73b5e6a10f4dfbbfc17f89a3e46dd0550673e4/assets/preview/jamstacker-dark.png)   | (dark only)                                                                                                                                              |
| [Victor Mono](https://themer.dev/victor-mono) | ![Victor Mono dark preview](https://cdn.jsdelivr.net/gh/themerdev/themer@6d814b06830b02d6138e824655f7e3d1314e991c/assets/preview/victor-mono-dark.png) | ![Victor Mono light preview](https://cdn.jsdelivr.net/gh/themerdev/themer@6d814b06830b02d6138e824655f7e3d1314e991c/assets/preview/victor-mono-light.png) |
| [Future Pro](https://themer.dev/future-pro)   | ![Future Pro dark preview](https://cdn.jsdelivr.net/gh/themerdev/themer@6d814b06830b02d6138e824655f7e3d1314e991c/assets/preview/future-pro-dark.png)   | ![Future Pro light preview](https://cdn.jsdelivr.net/gh/themerdev/themer@6d814b06830b02d6138e824655f7e3d1314e991c/assets/preview/future-pro-light.png)   |

### Original color sets

| Name                                                                                                          | Dark Preview                                                                                                                                                                | Light Preview                                                                                                                                                                 |
| ------------------------------------------------------------------------------------------------------------- | --------------------------------------------------------------------------------------------------------------------------------------------------------------------------- | ----------------------------------------------------------------------------------------------------------------------------------------------------------------------------- |
| [`default`](https://github.com/themerdev/themer/tree/main/cli/src/color-set/default.ts)                       | ![default dark preview](https://cdn.jsdelivr.net/gh/themerdev/themer@42a574d77d0a5b68b2f46a0a12c344457585c016/assets/preview/themer-default-dark.svg)                       | ![default light preview](https://cdn.jsdelivr.net/gh/themerdev/themer@42a574d77d0a5b68b2f46a0a12c344457585c016/assets/preview/themer-default-light.svg)                       |
| [`finger-paint`](https://github.com/themerdev/themer/tree/main/cli/src/color-set/finger-paint.ts)             | ![finger-paint dark preview](https://cdn.jsdelivr.net/gh/themerdev/themer@42a574d77d0a5b68b2f46a0a12c344457585c016/assets/preview/themer-finger-paint-dark.svg)             | ![finger-paint light preview](https://cdn.jsdelivr.net/gh/themerdev/themer@42a574d77d0a5b68b2f46a0a12c344457585c016/assets/preview/themer-finger-paint-light.svg)             |
| [`green-as-a-whistle`](https://github.com/themerdev/themer/tree/main/cli/src/color-set/green-as-a-whistle.ts) | ![green-as-a-whistle dark preview](https://cdn.jsdelivr.net/gh/themerdev/themer@42a574d77d0a5b68b2f46a0a12c344457585c016/assets/preview/themer-green-as-a-whistle-dark.svg) | ![green-as-a-whistle light preview](https://cdn.jsdelivr.net/gh/themerdev/themer@42a574d77d0a5b68b2f46a0a12c344457585c016/assets/preview/themer-green-as-a-whistle-light.svg) |
| [`monkey`](https://github.com/themerdev/themer/tree/main/cli/src/color-set/monkey.ts)                         | ![monkey dark preview](https://cdn.jsdelivr.net/gh/themerdev/themer@42a574d77d0a5b68b2f46a0a12c344457585c016/assets/preview/themer-monkey-dark.svg)                         | ![monkey light preview](https://cdn.jsdelivr.net/gh/themerdev/themer@42a574d77d0a5b68b2f46a0a12c344457585c016/assets/preview/themer-monkey-light.svg)                         |
| [`night-sky`](https://github.com/themerdev/themer/tree/main/cli/src/color-set/night-sky.ts)                   | ![night-sky dark preview](https://cdn.jsdelivr.net/gh/themerdev/themer@42a574d77d0a5b68b2f46a0a12c344457585c016/assets/preview/themer-night-sky-dark.svg)                   | (dark only)                                                                                                                                                                   |
| [`polar-ice`](https://github.com/themerdev/themer/tree/main/cli/src/color-set/polar-ice.ts)                   | ![polar-ice dark preview](https://cdn.jsdelivr.net/gh/themerdev/themer@42a574d77d0a5b68b2f46a0a12c344457585c016/assets/preview/themer-polar-ice-dark.svg)                   | ![polar-ice light preview](https://cdn.jsdelivr.net/gh/themerdev/themer@42a574d77d0a5b68b2f46a0a12c344457585c016/assets/preview/themer-polar-ice-light.svg)                   |
| [`right-in-the-teals`](https://github.com/themerdev/themer/tree/main/cli/src/color-set/right-in-the-teals.ts) | ![right-in-the-teals dark preview](https://cdn.jsdelivr.net/gh/themerdev/themer@42a574d77d0a5b68b2f46a0a12c344457585c016/assets/preview/themer-right-in-the-teals-dark.svg) | ![right-in-the-teals light preview](https://cdn.jsdelivr.net/gh/themerdev/themer@42a574d77d0a5b68b2f46a0a12c344457585c016/assets/preview/themer-right-in-the-teals-light.svg) |
| [`shoulder-pads`](https://github.com/themerdev/themer/tree/main/cli/src/color-set/shoulder-pads.ts)           | ![shoulder-pads dark preview](https://cdn.jsdelivr.net/gh/themerdev/themer@cd4919aae2f59901b6119480bf8a926b63916d43/assets/preview/themer-shoulder-pads-dark.svg)           | ![shoulder-pads light preview](https://cdn.jsdelivr.net/gh/themerdev/themer@cd4919aae2f59901b6119480bf8a926b63916d43/assets/preview/themer-shoulder-pads-light.svg)           |

### Ports from third-party themes

| Name                                                                                                    | Dark Preview                                                                                                                                                           | Light Preview                                                                                                                                               |
| ------------------------------------------------------------------------------------------------------- | ---------------------------------------------------------------------------------------------------------------------------------------------------------------------- | ----------------------------------------------------------------------------------------------------------------------------------------------------------- |
| [`dracula`](https://github.com/themerdev/themer/tree/main/cli/src/color-set/dracula.ts)                 | ![dracula dark preview](https://cdn.jsdelivr.net/gh/themerdev/themer@42a574d77d0a5b68b2f46a0a12c344457585c016/assets/preview/themer-dracula-dark.svg)                  | (dark only)                                                                                                                                                 |
| [`github-universe`](https://github.com/themerdev/themer/tree/main/cli/src/color-set/github-universe.ts) | ![github-universe dark preview](https://cdn.jsdelivr.net/gh/themerdev/themer@42a574d77d0a5b68b2f46a0a12c344457585c016/assets/preview/themer-git-hub-universe-dark.svg) | (dark only)                                                                                                                                                 |
| [`lucid`](https://github.com/themerdev/themer/tree/main/cli/src/color-set/lucid.ts)                     | ![lucid dark preview](https://cdn.jsdelivr.net/gh/themerdev/themer@42a574d77d0a5b68b2f46a0a12c344457585c016/assets/preview/themer-lucid-dark.svg)                      | ![lucid light preview](https://cdn.jsdelivr.net/gh/themerdev/themer@42a574d77d0a5b68b2f46a0a12c344457585c016/assets/preview/themer-lucid-light.svg)         |
| [`mojave`](https://github.com/themerdev/themer/tree/main/cli/src/color-set/mojave.ts)                   | ![mojave dark preview](https://cdn.jsdelivr.net/gh/themerdev/themer@42a574d77d0a5b68b2f46a0a12c344457585c016/assets/preview/themer-mojave-dark.svg)                    | ![mojave light preview](https://cdn.jsdelivr.net/gh/themerdev/themer@42a574d77d0a5b68b2f46a0a12c344457585c016/assets/preview/themer-mojave-light.svg)       |
| [`nova`](https://github.com/themerdev/themer/tree/main/cli/src/color-set/nova.ts)                       | ![nova dark preview](https://cdn.jsdelivr.net/gh/themerdev/themer@42a574d77d0a5b68b2f46a0a12c344457585c016/assets/preview/themer-nova-dark.svg)                        | (dark only)                                                                                                                                                 |
| [`one`](https://github.com/themerdev/themer/tree/main/cli/src/color-set/one.ts)                         | ![one dark preview](https://cdn.jsdelivr.net/gh/themerdev/themer@42a574d77d0a5b68b2f46a0a12c344457585c016/assets/preview/themer-one-dark.svg)                          | ![one light preview](https://cdn.jsdelivr.net/gh/themerdev/themer@42a574d77d0a5b68b2f46a0a12c344457585c016/assets/preview/themer-one-light.svg)             |
| [`rivet`](https://github.com/themerdev/themer/tree/main/cli/src/color-set/rivet.ts)                     | ![rivet dark preview](https://cdn.jsdelivr.net/gh/themerdev/themer@42a574d77d0a5b68b2f46a0a12c344457585c016/assets/preview/themer-rivet-dark.svg)                      | ![rivet light preview](https://cdn.jsdelivr.net/gh/themerdev/themer@42a574d77d0a5b68b2f46a0a12c344457585c016/assets/preview/themer-rivet-light.svg)         |
| [`seti`](https://github.com/themerdev/themer/tree/main/cli/src/color-set/seti.ts)                       | ![seti dark preview](https://cdn.jsdelivr.net/gh/themerdev/themer@42a574d77d0a5b68b2f46a0a12c344457585c016/assets/preview/themer-seti-dark.svg)                        | (dark only)                                                                                                                                                 |
| [`solarized`](https://github.com/themerdev/themer/tree/main/cli/src/color-set/solarized.ts)             | ![solarized dark preview](https://cdn.jsdelivr.net/gh/themerdev/themer@42a574d77d0a5b68b2f46a0a12c344457585c016/assets/preview/themer-solarized-dark.svg)              | ![solarized light preview](https://cdn.jsdelivr.net/gh/themerdev/themer@42a574d77d0a5b68b2f46a0a12c344457585c016/assets/preview/themer-solarized-light.svg) |

## Themer templates

### Terminals

- [`alacritty`](https://github.com/themerdev/themer/tree/main/cli/src/template/alacritty.ts)
- [`cmd`](https://github.com/themerdev/themer/tree/main/cli/src/template/cmd.ts)
- [`conemu`](https://github.com/themerdev/themer/tree/main/cli/src/template/conemu.ts)
- [`hyper`](https://github.com/themerdev/themer/tree/main/cli/src/template/hyper.ts)
- [`iterm`](https://github.com/themerdev/themer/tree/main/cli/src/template/iterm.ts)
- [`kitty`](https://github.com/themerdev/themer/tree/main/cli/src/template/kitty.ts)
- [`konsole`](https://github.com/themerdev/themer/tree/main/cli/src/template/konsole.ts)
- [`terminal`](https://github.com/themerdev/themer/tree/main/cli/src/template/terminal.ts)
- [`terminator`](https://github.com/themerdev/themer/tree/main/cli/src/template/terminator.ts)
- [`warp`](https://github.com/themerdev/themer/tree/main/cli/src/template/warp.ts)
- [`windows-terminal`](https://github.com/themerdev/themer/tree/main/cli/src/template/windows-terminal.ts)

### Editors/IDEs

- [`atom-syntax`](https://github.com/themerdev/themer/tree/main/cli/src/template/atom-syntax.ts)
- [`atom-ui`](https://github.com/themerdev/themer/tree/main/cli/src/template/atom-ui.ts)
- [`bbedit`](https://github.com/themerdev/themer/tree/main/cli/src/template/bbedit.ts)
- [`emacs`](https://github.com/themerdev/themer/tree/main/cli/src/template/emacs.ts)
- [`sublime-text`](https://github.com/themerdev/themer/tree/main/cli/src/template/sublime-text.ts)
- [`vim-lightline`](https://github.com/themerdev/themer/tree/main/cli/src/template/vim-lightline.ts)
- [`vim`](https://github.com/themerdev/themer/tree/main/cli/src/template/vim.ts)
- [`visual-studio`](https://github.com/themerdev/themer/tree/main/cli/src/template/visual-studio.ts)
- [`vs-code`](https://github.com/themerdev/themer/tree/main/cli/src/template/vs-code.ts)
- [`xcode`](https://github.com/themerdev/themer/tree/main/cli/src/template/xcode.ts)

### Other apps

- [`alfred`](https://github.com/themerdev/themer/tree/main/cli/src/template/alfred.ts)
- [`brave`](https://github.com/themerdev/themer/tree/main/cli/src/template/brave.ts)
- [`chrome`](https://github.com/themerdev/themer/tree/main/cli/src/template/chrome.ts)
- [`css`](https://github.com/themerdev/themer/tree/main/cli/src/template/css.ts)
- [`firefox-addon`](https://github.com/themerdev/themer/tree/main/cli/src/template/firefox-addon.ts)
- [`firefox-color`](https://github.com/themerdev/themer/tree/main/cli/src/template/firefox-color.ts)
- [`kde-plasma-colors`](https://github.com/themerdev/themer/tree/main/cli/src/template/kde-plasma-colors.ts)
- [`keypirinha`](https://github.com/themerdev/themer/tree/main/cli/src/template/keypirinha.ts)
- [`prism`](https://github.com/themerdev/themer/tree/main/cli/src/template/prism.ts)
- [`sketch-palettes`](https://github.com/themerdev/themer/tree/main/cli/src/template/sketch-palettes.ts)
- [`slack`](https://github.com/themerdev/themer/tree/main/cli/src/template/slack.ts)
- [`wox`](https://github.com/themerdev/themer/tree/main/cli/src/template/wox.ts)
- [`xresources`](https://github.com/themerdev/themer/tree/main/cli/src/template/xresources.ts)

### Wallpapers

See [`themer`'s Web UI](https://themer.dev) for wallpaper previews.

- [`wallpaper-block-wave`](https://github.com/themerdev/themer/tree/main/cli/src/template/wallpaper-block-wave.ts)
- [`wallpaper-burst`](https://github.com/themerdev/themer/tree/main/cli/src/template/wallpaper-burst.ts)
- [`wallpaper-circuits`](https://github.com/themerdev/themer/tree/main/cli/src/template/wallpaper-circuits.ts)
- [`wallpaper-diamonds`](https://github.com/themerdev/themer/tree/main/cli/src/template/wallpaper-diamonds.ts)
- [`wallpaper-dot-grid`](https://github.com/themerdev/themer/tree/main/cli/src/template/wallpaper-dot-grid.ts)
- [`wallpaper-octagon`](https://github.com/themerdev/themer/tree/main/cli/src/template/wallpaper-octagon.ts)
- [`wallpaper-shirts`](https://github.com/themerdev/themer/tree/main/cli/src/template/wallpaper-shirts.ts)
- [`wallpaper-triangles`](https://github.com/themerdev/themer/tree/main/cli/src/template/wallpaper-triangles.ts)
- [`wallpaper-trianglify`](https://github.com/themerdev/themer/tree/main/cli/src/template/wallpaper-trianglify.ts)

## Prior art

`themer` is inspired by [trevordmiller/nova](https://github.com/trevordmiller/nova/) and [chriskempson/base16](http://chriskempson.com/projects/base16/).

Conceptually, `themer` is very similar to [base16](http://chriskempson.com/projects/base16/), but:

1. It is lighter, and simpler to use.
2. It is more easily extensible with your own color sets and templates.
3. It integrates better with your dotfiles, especially if you keep them under version control.

## Contributing

For instructions on how to contribute to `themer`, see [CONTRIBUTING.md](https://github.com/themerdev/themer/blob/main/.github/CONTRIBUTING.md) and [`themer`'s code of conduct](https://github.com/themerdev/themer/blob/main/CODE_OF_CONDUCT.md).

## Next steps

### Join the community

- ⭐️ Star [`themer` on GitHub](https://github.com/themerdev/themer)
- 🐘 Follow [@themer](https://fosstodon.org/@themer) on Mastodon
- 💌 [Join the newsletter](https://themer.dev/join)

### Support `themer`

- 🦁 [Send a tip through the Brave Browser](https://brave.com), either on [the repository page](https://github.com/themerdev/themer) or [`themer`'s Web UI](https://themer.dev)
- 💳 Pay what you want when downloading your theme from [themer.dev](https://themer.dev)
- 👑 Purchase a premium theme from [themer.dev](https://themer.dev)
- 💖 [Sponsor the @themerdev GitHub org](https://github.com/sponsors/themerdev)
