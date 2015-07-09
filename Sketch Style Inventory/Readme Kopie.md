*****
**Important note:** These plugins are still in development and may not work as expected. Keep an eye for the `experimental` flag ;)
*****

# Style Inventory for Sketch

Design requires free, sometimes chaotic exploration. But design also means organisation and structure. Sketch can be good in both aspects, but moving from exploration to structured layouts with text styles and unified colors is hard. Either you start clean files from scratch, or you use what you have and try to tidy it up. The Style Inventory is meant to help you with that. It gives you an overview of all your used styles and helps you to merge styles of similar layers into one.

## Change Log

**December 7, 2014**
* Moved all unreleated plugins to a new repository called [Sketch Mate](https://github.com/getflourish/Sketch-Mate)


## Plugin Directory

#### Inventory
* Generate/Color Inventory `experimental` `ctrl` + `⌘` + `⌥` + `C`
* Generate/Text Styles Inventory `experimental` `ctrl` + `⌘` + `⌥` + `T`
* Rename Selected Layers

#### Selection
* Select Artboard(s) `shift` + `⌘` + `A`
* Select Group Layers `ctrl` + `⌘` + `G`
* Select Parent Group `⌘` + `⌥` + `G`
* by Color/Select Layers by Color `shift` + `ctrl` + `⌘` + `C`
* by Color/Select Layers by Color on Artboard `ctrl` + `⌘` + `C`
* by Color/Select Next/Previous Layer by Color
* by Name/Select Layers by Name `shift` + `ctrl` + `⌘` + `N`
* by Name/Select Layers by Name on Artboard `ctrl` + `⌘` + `N`
* by Text Style/Choose Similar Text Layer
* by Text Style/Select Similar Text Layers
* by Text Style/Select Similar Text Layers on Artboard `⌘` + `control` + `T`


## Installation

To install all plugins, [download](https://github.com/getflourish/Sketch-Style-Inventory/archive/master.zip) them all first, unzip the archive, and place the folder contents in your Sketch Plugins folder by navigating to `Sketch > Plugins > Reveal Plugins Folder…`

To install only a selection of plugins, you will first need to place the library file `inventory.js` in the root of your Sketch Plugins directory. This is very important as all plugins rely on its functionality.

You can then install selected plugins by double-clicking the file, or alternatively, drag and drop the file onto the Sketch app icon. This will automatically copy the plugin to your Sketch Plugins folder.

## Keyboard Shortcuts

Most plugins have a pre-defined keyboard shortcut. You can always change it by editing the shortcut written in parenthesis at the end of the first line of a plugin.

For example, the first line of `Duplicate Artboard.sketchplugin`:

> // Duplicates the current artboard right next to it. (shift command d)

You can use modifier keys such as `option`, `command`, `control`, `shift`


## Selection

A set of plugins that select layers based on color, name & text style.

### Select Artboard

Depending whether the selection is a layer or an artboard, this plugin will select the current artboard or all artboards of the current page.

![Selection Animation](https://dl.dropboxusercontent.com/u/974773/_keepalive/Style%20Inventory/Select%20Artboard.gif)

**Shortcut:** `shift` + `⌘` + `A`

### Select Layers by Color on Artboard

Based on a selected layer, all layers on the current artboard that match the fill or text color will be selected.

**Shortcut:** `ctrl` + `⌘` + `C`

![Selection Animation](https://dl.dropboxusercontent.com/u/974773/_keepalive/Style%20Inventory/Select%20by%20Color.gif)

### Select Layers by Color

`experimental` Based on a selected layer, all document layers that match the fill or text color will be selected.

### Select Layers by Name

Based on a selected layer, all layers that match the name of the reference layer will be selected. This will also include layers that have appended numbers from duplication (e.g. Rectangle 1, Rectangle 2, …)

**Shortcut:** `ctrl` + `⌘` + `N`

![Selection Animation](https://dl.dropboxusercontent.com/u/974773/_keepalive/Style%20Inventory/Select%20by%20Name.gif)

### Select Layers of Group
Selects the layers of a group.

**Shortcut:** `ctrl` + `⌘` + `G`

### Select Next Layer by Color

`experimental` Based on a selection, the next layer with the same fill color will be selected.

### Select Next Layer by Text Style

`experimental` Based on a selection, the next layer with the same text style will be selected.

![Screenshot](https://dl.dropboxusercontent.com/u/974773/_keepalive/Style%20Inventory/Select%20Layer%20by%20Similar%20Style.png)

## Style Inventory
Generate a visual style sheet with all colors and text styles that you are using. This will help you to get an overview of your used styles so you can merge styles that are very close together. This will also export a CSS file with text styles.

### Export/Text Styles to CSS

This plugin generates an overview of all your text styles and exports it as CSS. [Watch the demo](https://vimeo.com/102635978 "Demo")
This is more proof of concept and only the foundation of a set of helpful plugins that will follow soon.

To do: export opacity, remove attributes that have the default value

[![Demo on Vimeo](https://dl.dropboxusercontent.com/u/974773/_keepalive/Sketch%20CSS%20Vimeo.png)](https://vimeo.com/102635978)

![Screenshot](https://dl.dropboxusercontent.com/u/974773/_keepalive/Sketch%20CSS.png)

### Generate/Color Inventory
Generates an artboard with all colors that are used on the current page.

![Screenshot](https://dl.dropboxusercontent.com/u/974773/_keepalive/Style%20Inventory/Colors.png)

### Generate/Text Style Inventory
Generates an artboard with all text styles that are used in the document.

### Rename/Rename selected layers
`experimental` A simple wizard that will guide you through your styles that are missing variable names. This will be used to to provide more information for SASS and JSON export.
