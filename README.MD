# vstodo

**vstodo** is a VS Code extension for highlighting TODO, FIXME, and custom tags.

## Features

* **Tag Highlighting** - Automatically highlights TODO, FIXME, and your own custom tags.
* **On-the-Fly Configuration** - Customize your tags instantly without restarting the editor.
* **Flexible Styling** - Choose custom color for each tag.


## Configuration Settings

Here is an example of settings:

```json
{
  "vstodo.tags": [
    {
        "tag": "TODO",
        "background": "#ffeb3b4d",
        "foreground": "#ffc107cc",
        "isWholeLine": false
    },
    {
        "tag": "FIXME",
        "background": "#ff3b3b4d",
        "foreground": "#ff0707cc",
        "isWholeLine": false
    }    
  ]
}
```

* `tag` (string) - Text to highlight.
* `foreground` (string) - Text color (HEX).
* `background` (string) - Background color (HEX).
* `isWholeLine` (boolean) - Highlight whole line.
