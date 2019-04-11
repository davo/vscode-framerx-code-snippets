# Framer X Code Snippets for VS Code

This extension provides Framer X & React code snippets for TypeScript and ES6.

Here is a adirect link to the extension at the VS Code Marketplace [Framer X Code Snippets](https://marketplace.visualstudio.com/items?itemName=pixelbeat.vscode-framerx-code-snippets)

## Installation

In the command palette (`cmd-shift-p`), select `Install Extension` and type `Framer X Code Snippets for VS Code`.

## Supported languages (file extensions)

-   TypeScript React (.tsx)
-   TypeScript (.ts)
-   JavaScript React (.jsx)
-   JavaScript (.js)

## Snippet list

#### Framer X Snippets:

-   [x] Framer X Default Code Component
-   [x] Import Frame component

#### Framer X Property Controls:

-   [x] Property Control Static Method
-   [x] Control Type Boolean
-   [x] Control Type Number
-   [x] Control Type String
-   [x] Control Type Color
-   [x] Control Type Image
-   [x] Control Type File
-   [x] Control Type Enum
-   [x] Control Type SegmentedEnum
-   [x] Control Type FusedNumber
-   [x] Hide Control Types Pattern
-   [x] Control Type ComponentInstance
-   [x] Control Type Array
-   [ ] Control Type Object `internal`

#### Framer X Code Overrides:

-   [ ] Events Overrides
-   [ ] Animation Overrides

#### Framer X Hooks:

-   [ ] useAnimation
-   [ ] useCache
-   [ ] useConstraints
-   [ ] useCycle
-   [ ] useExternalRef
-   [ ] useGestures
-   [ ] useMap
-   [ ] useMotionValue
-   [ ] usePanGesture
-   [ ] userAgent
-   [ ] userSelect
-   [ ] useSpring
-   [ ] useTapGesture
-   [ ] useTransformedValue
-   [ ] useViewportScrollValues

---

# Snippets

The **⇥** means the `TAB →` key.

## Framer X Templates

|  Prefix | Template                                                    |
| ------: | ----------------------------------------------------------- |
| `xcc ⇥` | "import { PropertyControls, ControlType } from 'framer'..." |
| `xif ⇥` | "import { Frame } from 'framer'"                            |

## Framer X Property Controls

|    Prefix | Method                                                   |
| --------: | -------------------------------------------------------- |
|  `xipc ⇥` | "import { PropertyControls, ControlType } from 'framer'" |
|   `xpc ⇥` | "static propertyControls: PropertyControls = {}"         |
|  `xcts ⇥` | "text: {type: ControlType.String, ...}"                  |
|  `xcta ⇥` | "children: {type: ControlType.Array, ...}"               |
|  `xctc ⇥` | "color: {type: ControlType.Color, ...}"                  |
| `xctci ⇥` | "children: {type: ControlType.ComponentInstance, ...}"   |
|  `xcti ⇥` | "image: {type: ControlType.Image, ...}"                  |
|  `xctn ⇥` | "number: {type: ControlType.Number, ...}"                |
| `xctfn ⇥` | "fusedNumber: {type: ControlType.FusedNumber, ...}"      |
|  `xctb ⇥` | "boolean: {type: ControlType.Boolean, ...}"              |
| `xctse ⇥` | "segment: {type: ControlType.SegmentedEnum, ...}"        |
|  `xcte ⇥` | "enum: {type: ControlType.Enum, ...}"                    |
|  `xctf ⇥` | "file: {type: ControlType.File, ...}"                    |
| `xcpct ⇥` | "...hidden(props) {return props.isEnabled === false }"   |

## React

|   Prefix | Method                                |
| -------: | ------------------------------------- |
| `ximp ⇥` | "import { ModuleName } from 'module'" |

### React Hooks

|    Prefix | Method                   |
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

### React Custom Hooks

|   Prefix | Method              |
| -------: | ------------------- |
|  `xui ⇥` | useIdentifier Hook  |
| `xusv ⇥` | useStaticValue Hook |

## Utility Functions

|  Prefix | Method                         |
| ------: | ------------------------------ |
| `xrc ⇥` | "function randomColor() {...}" |

## Tips & Tricks

To get the most of this extension I recommend also to install:

-   [ES7 React/Redux/React-Native/JS snippets](https://github.com/dsznajder/vscode-es7-javascript-react-snippets), comes with more than +100 snippets.
-   [JavaScript Snippet Pack](https://marketplace.visualstudio.com/items?itemName=akamud.vscode-javascript-snippet-pack), comes with a variety of useful snippets for debugging (cl ⇥ console.log) and traditional DOM manipulation methods.

## Credits

New React Hooks snippets contains code samples from the following projects:

-   [React Hooks Snippets for VS Code](https://github.com/antmdvs/vscode-react-hooks-snippets)
-   [VSCode React Snippets](https://github.com/Wind4/vscode-react-snippets)

## Feedback & Contributions

Any type of feedback will be extremely useful. I encourage you to [write a review](https://marketplace.visualstudio.com/items?itemName=pixelbeat.vscode-framerx-code-snippets#review-details).

Have you found something wrong/missing or you just want to bring an idea? Please [open a new issue](https://github.com/davo/vscode-framerx-code-snippets/issues/new) and tell me more about it! 🙌🏻

If you have a stash of great code samples, feel free to share them with the rest of the community. Please [create a pull request](hhttps://github.com/davo/vscode-framerx-code-snippets/pulls?q=is%3Apr+is%3Aopen+sort%3Aupdated-desc)! ✨
