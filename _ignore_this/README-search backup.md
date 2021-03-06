# Elm Query #

## >>> See README.md <<< ##

Query [Elm Search](https://klaftertief.github.io/elm-search/) to search Elm Modules by function name or by approximate type signature.

Query [Elm Packages](https://package.elm-lang.org/) to search Elm Packages from the official webiste by keyword.

## Install ##

1. Press `Ctrl+Shift+P` (or `Cmd+Shift+P` on Mac) to open the Command Palette
2. Select **Package Control: Install Package**
3. Select **Elm Query**

## Usage ##

### Settings ###

You can set a valid alternative URL (e.g: [https://elm.dmy.fr](https://elm.dmy.fr)) if you really want to.

### Commands ###

#### Search Elm Modules ####

1. Press `Ctrl+Shift+P` (or `Cmd+Shift+P` on Mac) to open the Command Palette
2. Select **Elm Query: Search Modules**
3. Type a function name or type signature in the Input Panel, and press `Enter`
4. Select the desired result from the list presented in the Quick Panel
5. Press `Enter` to open a browser window for the selected Elm module

##### Search Elm Modules By Selection #####

1. Select some text (function name/type signature) or place the cursor in a word
2. Press `Ctrl+Shift+P` (or `Cmd+Shift+P` on Mac) to open the Command Palette
3. Select **Elm Query: Search Selection** in the command palette
4. Select the desired result from the list presented in the Quick Panel
5. Press `Enter` to open a browser window for the selected Elm module

#### Search Elm Packages ####

1. Press `Ctrl+Shift+P` (or `Cmd+Shift+P` on Mac) to open the Command Palette
2. Select **Elm Query: Search Packages**
3. Type a keyword in the Input Panel and press `Enter`
4. Select the desired result from the list presented in the Quick Panel
5. Press `Enter` to open a browser window for the selected Elm package

### Key Bindings ###

Should you want to create key bindings for you convenience, these are the underlying commands:

```json
[
    {
        "caption": "Elm Query: Search Packages",
        "command": "elm_search_package"
    },
    {
        "caption": "Elm Query: Search Modules",
        "command": "elm_search_module"
    },
    {
        "caption": "Elm Query: Search Selection",
        "command": "elm_search_selection"
    },
] 
```

## Contributing ##

Contributions are more than welcome :) Should you like to help out, please bear in mind that contribution should follow the guidelines specified in the [pyproject.toml](./pyproject.toml) file. (**flake8**, **black**).
