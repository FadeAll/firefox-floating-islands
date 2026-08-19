## Preview

![Firefox Floating Islands](preview.png)

## Firefox Floating Islands

Custom 'userChrome.css' theme for Firefox that transforms the browser interface

The theme is designed around compact rounded panels and floating navigation

## Features

- Floating navigation bar
- Rounded URL bar
- Compact circular toolbar buttons
- Minimal vertical tabs
- Icon-only vertical tabs
- Floating sidebar
- Rounded Firefox panels
- Hidden default toolbars
- Custom fullscreen behavior
- Modular CSS structure

## Structure

The project is organized into separate CSS modules:

- `userChrome.css` — main entry point that imports all CSS modules.
- `css/toolbox.css` — Firefox toolbar configuration.
- `css/navbar.css` — floating navigation bar.
- `css/urlbar.css` — address bar styling.
- `css/buttons.css` — toolbar and menu buttons.
- `css/panels.css` — panels and popup elements.
- `css/sidebar.css` — floating sidebar.
- `css/vertical-tabs.css` — vertical tabs and tab controls.
- `css/fullscreen.css` — fullscreen behavior.

## Installation

### 1. Enable userChrome.css

Open Firefox and go to:

`about:config`

Set:

`toolkit.legacyUserProfileCustomizations.stylesheets`

to:

`true`

### 2. Find your Firefox profile

Open:

`about:support`

Find **Profile Directory** and open it.

Create a directory named:

`chrome`

### 3. Install the theme

Copy `userChrome.css` and the `css/` directory into the `chrome` directory.

The resulting structure should be:

`chrome/userChrome.css`

`chrome/css/toolbox.css`

`chrome/css/navbar.css`

`chrome/css/urlbar.css`

`chrome/css/buttons.css`

`chrome/css/panels.css`

`chrome/css/sidebar.css`

`chrome/css/vertical-tabs.css`

`chrome/css/fullscreen.css`

### 4. Restart Firefox

Restart Firefox after installing the files.

## Compatibility

This theme targets modern Firefox with vertical tabs support.

Firefox's internal UI structure may change between versions, so some selectors may require updates after major Firefox releases.

## Development

The CSS is separated into modules so individual parts of the interface can be modified independently.

## License

MIT License.
