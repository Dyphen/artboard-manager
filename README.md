# Sketch Artboard Manager

This plugin automatically arranges the position of all Artboards in your Sketch document, to snap them to rows & columns.

![](https://user-images.githubusercontent.com/3832/28533105-3a1586ca-709c-11e7-8544-87d2bb0ad4f1.gif)

It’s still a work in progress (for one, it doesn’t even have an easy way to change the config…) but it’ll get better 🤞.

## Configuration

You can tweak some of the settings by searching for this bit of code and editing it:

```javascript
var config = {
  renameArtboards: false,
  snapDistance: 400,
  gridHorizontalSpace: 50,
  gridVerticalSpace: 500,
  artboardBasenames: ["A", "B", "C", "D", "E", "F", "G", "H", "I", "J", "K", "L", "M", "N", "O", "P", "Q", "R", "S", "T", "U", "V", "W", "X", "Y", "Z"]
};
```

- If you set `renameArtboards` to `true`, the plugin will rename _all_ artboards in the current page, so handle it with care :)

## TODO

- Arrange artboards on artboard deletion
- UI for editing preferences
