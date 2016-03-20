[Japanese Readme](README-ja.md)
# vscode-svgviewer
SVG Viewer for Visual Studio Code
[Visual Studio Marketplace](https://marketplace.visualstudio.com/items/cssho.vscode-svgviewer)

## Usage 
0. Press Ctrl+P and type `ext install SVG Viewer` with a trailing space. 
0. Press Enter and restart VSCode.
0. Open a SVG File.
0. Choose process from `Command Palette` or `Shortcut`.

![palette](img/palette.png)

### View SVG - `Ctrl(Cmd)+I O`
Display SVG on an Editor

### Export PNG - `Ctrl(Cmd)+I E`
Convert from SVG to PNG

![preview](img/preview.png)

### Options
The following Visual Studio Code setting is available for the SVG Viewer.  This can be set in `User Settings` or `Workspace Settings`.

```javascript
{
    // Show Transparency Grid
	"svgviewer.transparencygrid": true
}
```