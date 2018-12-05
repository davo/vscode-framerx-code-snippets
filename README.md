# Framer X Code Snippets for VS Code

This extension provides you Framer X & React snippets in ES6/ES7 and TypeScript for VS Code.

Here is direct link to the extention at the VS Code Marketplace [Framer X Code Snippets](https://marketplace.visualstudio.com/items?itemName=pixelbeat.vscode-framerx-code-snippets)

## Supported languages (file extensions)

- TypeScript React (.tsx)
- TypeScript (.ts)
- JavaScript React (.jsx)
- JavaScript (.js)

## Snippets list

<details>
<summary><b>Expand snippets list</b></summary>


#### Framer X Snippets:

  * [x] Framer X Default Code Component
  * [x] Import Frame component

#### Framer X Property Controls:

  * [x] Property Control Static Method
  * [x] Control Type Boolean
  * [x] Control Type Number
  * [x] Control Type String
  * [x] Control Type Color
  * [x] Control Type Image
  * [x] Control Type File
  * [x] Control Type Enum
  * [x] Control Type SegmentedEnum
  * [x] Control Type FusedNumber
  * [x] Hide Control Types Pattern


#### Framer X Code Overrides:

  * [ ] Events Overrides
  * [ ] Animation Overrides

---


</details>

# Methods

The **⇥** means the `TAB→` key.

## Framer X Essentials

| Prefix      | Method                                                                              |
| ----------: | ----------------------------------------------------------------------------------- |
| `xcc→`       | "import { PropertyControls, ControlType } from 'framer'..."                         |
| `xif→`       | "import { Frame } from 'framer'"                                                    |

## Framer X Property Controls

| Prefix      | Method                                                                              |
| ----------: | ----------------------------------------------------------------------------------- |
| `xipc→`      | "import { PropertyControls, ControlType } from 'framer'"                            |
| `xpc→`       | "static propertyControls: PropertyControls = {}"                                    |
| `xcts→`     | "text: {type: ControlType.String, ...}"                                             |
| `xctc→`     | "color: {type: ControlType.Color, ...}"                                             |
| `xcti→`     | "image: {type: ControlType.Image, ...}"                                             |
| `xctn→`     | "number: {type: ControlType.Number, ...}"                                           |
| `xctfn→`    | "fusedNumber: {type: ControlType.FusedNumber, ...}"                                 |
| `xctb→`     | "boolean: {type: ControlType.Boolean, ...}"                                         |
| `xctse→`     | "segment: {type: ControlType.SegmentedEnum, ...}"                                  |
| `xcte→`     | "enum: {type: ControlType.Enum, ...}"                                               |
| `xctf→`     | "file: {type: ControlType.File, ...}"                                               |
| `xcpct→`     | "...hidden(props) {return props.isEnabled === false }"                              |

## React

| Prefix      | Method                                                                              |
| ----------: | ----------------------------------------------------------------------------------- |
| `imp→`       | "import { ModuleName } from 'module'"                                               |

