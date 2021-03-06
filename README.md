[![Badge for version for Visual Studio Code extension pixelbeat.vscode-framerx-code-snippets](https://vsmarketplacebadge.apphb.com/version-short/pixelbeat.vscode-framerx-code-snippets.svg?color=blue&style=?style=for-the-badge&logo=visual-studio-code)](https://marketplace.visualstudio.com/items?itemName=pixelbeat.vscode-framerx-code-snippets)
[![Installs](https://vsmarketplacebadge.apphb.com/installs-short/pixelbeat.vscode-framerx-code-snippets.svg?color=blue&style=flat-square)](https://marketplace.visualstudio.com/items?itemName=pixelbeat.vscode-framerx-code-snippets)
[![Rating](https://vsmarketplacebadge.apphb.com/rating-short/pixelbeat.vscode-framerx-code-snippets.svg?color=blue&style=flat-square)](https://marketplace.visualstudio.com/items?itemName=pixelbeat.vscode-framerx-code-snippets)
[![The MIT License](https://img.shields.io/badge/license-MIT-orange.svg?color=blue&style=flat-square)](http://opensource.org/licenses/MIT)


# Framer X Code Snippets for VS Code


This extension provides Framer X & React code snippets for TypeScript and ES6.

## Installation

In the command palette (`cmd-shift-p`), select `Install Extension` and type `Framer X Code Snippets for VS Code`.

## Supported languages (file extensions)

- TypeScript React (.tsx)
- TypeScript (.ts)
- JavaScript React (.jsx)
- JavaScript (.js)

# Snippets

The **⇥** means the `TAB →` key.

## Framer X Templates

|        Prefix | Snippet                                                        |
|-------------: |----------------------------------------------------------------|
| `xproperty ⇥` | "import { addPropertyControls, ControlType } from 'framer'..." |
| `xframe ⇥`    | "import { Frame } from 'framer'"                               |


## Framer X Property Controls

|         Prefix | Snippet                                                |
|--------------: |--------------------------------------------------------|
| `xcontrols ⇥`  | "static propertyControls: PropertyControls = {}"       |
| `xstring ⇥`    | "text: {type: ControlType.String, ...}"                |
| `xarray ⇥`     | "children: {type: ControlType.Array, ...}"             |
| `xcolor ⇥`     | "color: {type: ControlType.Color, ...}"                |
| `xcomponent ⇥` | "children: {type: ControlType.ComponentInstance, ...}" |
| `ximage ⇥`     | "image: {type: ControlType.Image, ...}"                |
| `xnumber ⇥`    | "number: {type: ControlType.Number, ...}"              |
| `xfusednum ⇥`  | "fusedNumber: {type: ControlType.FusedNumber, ...}"    |
| `xbool ⇥`      | "boolean: {type: ControlType.Boolean, ...}"            |
| `xsegenum ⇥`   | "segment: {type: ControlType.SegmentedEnum, ...}"      |
| `xenum ⇥`      | "enum: {type: ControlType.Enum, ...}"                  |
| `xfile ⇥`      | "file: {type: ControlType.File, ...}"                  |
| `xhideprop ⇥`  | "...hidden(props) {return props.toggle === false}"     |


## React

|   Prefix | Snippet                                |
| -------: | ------------------------------------- |
| `ximp ⇥` | "import { ModuleName } from 'module'" |

### React Hooks

|    Prefix | Snippet                   |
| --------: | ------------------------ |
|   `xus ⇥` | useState Hook            |
|   `xue ⇥` | useEffect Hook           |
|   `xuc ⇥` | useContext Hook          |
|   `xur ⇥` | useReducer Hook          |
|  `xucb ⇥` | useCallback Hook         |
|   `xum ⇥` | useMemo Hook             |
| `xuref ⇥` | useRef Hook              |
|  `xuih ⇥` | useImperativeHandle Hook |
|  `xule ⇥` | useLayoutEffect Hook     |
|  `xudv ⇥` | useDebugValue Hook       |


## Snippet list



#### Framer X Snippets:

-  Framer X Functional Component (Outdated pattern)
-  Framer X Class Component (Outdated pattern)
-  Import Frame component

#### Framer X Property Controls:

-  Property Control Static Method
-  Control Type Boolean
-  Control Type Number
-  Control Type String
-  Control Type Color
-  Control Type Image
-  Control Type File
-  Control Type Enum
-  Control Type SegmentedEnum
-  Control Type FusedNumber
-  Hide Control Types Pattern
-  Control Type ComponentInstance
-  Control Type Array

---

### React Custom Hooks

|   Prefix | Snippet              |
| -------: | ------------------- |
|  `xui ⇥` | useIdentifier Hook  |
| `xusv ⇥` | useStaticValue Hook |

## Utility Functions

|  Prefix | Snippet                         |
| ------: | ------------------------------ |
| `xrc ⇥` | "function randomColor() {...}" |

## Tips & Tricks

To get the most of this extension I recommend also to install:

- [ES7 React/Redux/React-Native/JS snippets](https://github.com/dsznajder/vscode-es7-javascript-react-snippets), comes with more than +100 snippets.
- [JavaScript Snippet Pack](https://marketplace.visualstudio.com/items?itemName=akamud.vscode-javascript-snippet-pack), comes with a variety of useful snippets for debugging (cl ⇥ console.log) and traditional DOM manipulation methods.

## Credits

New React Hooks snippets contains code samples from the following projects:

- [React Hooks Snippets for VS Code](https://github.com/antmdvs/vscode-react-hooks-snippets)
- [VSCode React Snippets](https://github.com/Wind4/vscode-react-snippets)

New snippet prefixes inspired by Aroa Gil Bo, [Framer X Property Control Template & Snippets
](https://marketplace.visualstudio.com/items?itemName=AroaGilBo.framer-property-control-snippets)


## Feedback & Contributions

Any type of feedback will be extremely useful. I encourage you to [write a review](https://marketplace.visualstudio.com/items?itemName=pixelbeat.vscode-framerx-code-snippets#review-details).

Have you found something wrong/missing or you just want to bring an idea? Please [open a new issue](https://github.com/davo/vscode-framerx-code-snippets/issues/new) and tell me more about it! 🙌🏻

If you have a stash of great code samples, feel free to share them with the rest of the community. Please [create a pull request](hhttps://github.com/davo/vscode-framerx-code-snippets/pulls?q=is%3Apr+is%3Aopen+sort%3Aupdated-desc)! ✨
