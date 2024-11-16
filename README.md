<p align="center" style="font-weight:bold; font-size=25px;">
  Industrious Blue for Visual Studio Code
</p>
 <p align="center">
  <img src="https://raw.githubusercontent.com/trebleCode/industrious-blue/main/images/industrious-blue-bot.jpeg" alt="Industrious Blue Bot"/>
</p>
<p align="center">
A dark theme for VS Code with blues and greys
</p>

![Screenshot](https://raw.githubusercontent.com/treblecode/industrious-blue/main/images/screen1.png)
<br />
<br />
![Screenshot](https://raw.githubusercontent.com/treblecode/industrious-blue/main/images/screen2.png)
<br />
<br />
![Screenshot](https://raw.githubusercontent.com/treblecode/industrious-blue/main/images/screen3.png)
<br />
<br />
![Screenshot](https://raw.githubusercontent.com/treblecode/industrious-blue/main/images/screen4.png)
<br />
<br />
## Contributing

If you'd like to contribute to this theme, please read the [contributing guidelines](./.github/CONTRIBUTING.md).

##

If you have technical limitations to download the theme extension, you can achieve the visual result by editing your settings.json file
https://code.visualstudio.com/docs/getstarted/settings#_settings-json-file	
	
In your settings.json file, add a key of "workbench.colorCustomizations" as an object.

Ex.

"workbench.colorCustomizations": {
	"activityBar.activeBackground": "#025687",
        "activityBar.background": "#010c13"
}

	
Disable all other active themes.
Copy and paste the customizations below into your settings.json file and save.

	"workbench.colorCustomizations": {
	"activityBar.activeBackground": "#025687",
        "activityBar.background": "#010c13",
        "activityBar.border": "#010c13",
        "activityBar.inactiveForeground": "#c7c6c6",
        "badge.background": "#025687",
        "breadcrumb.background":"#010c13",
        "editor.background": "#010c13",
        "editor.findMatchBackground": "#0e364d",
        "editor.findMatchHighlightBackground": "#0e364d",
        "editorGroup.border": "#010c13",
        "editorFindWidget.findInput.selectionBackground": "#c7c6c6",
        "editorGroupHeader.tabsBackground": "#010c13",
        "editorGroupHeader.border": "#010c13",
        "editorWidget.background": "#010c13",
        "editorWidget.border": "#010c13",
        "input.background": "#15475f85",
        "input.border": "#84bcd885",
        "list.activeSelectionBackground": "#010c13",
        "list.highlightForeground": "#008cff",
        "list.hoverBackground": "#025687",
        "list.hoverForeground": "#ffffff",
        "list.inactiveSelectionBackground": "#025687",
        "menu.background": "#010c13",
        "menu.border":"#025687",
        "menu.selectionBackground": "#025687",
        "menu.separatorBackground": "#010c13",
        "panel.background": "#010c13",
        "panel.border": "#010c13",
        "quickInput.background": "#010c13",
        "quickInput.foreground": "#78dae7",
        "quickInputList.focusBackground": "#4350572a",
        "quickInputList.focusForeground": "#afd8f0",
        "scrollbarSlider.activeBackground": "#025687",
        "scrollbarSlider.background": "#025687",
        "scrollbarSlider.hoverBackground": "#025687",
        "selection.background": "#2b80b1",
        "sideBar.background": "#010c13",
        "sideBar.border": "#010c13",
        "sideBar.foreground": "#c7c6c6",
        "sideBarSectionHeader.background": "#010c13",
        "sideBarSectionHeader.border": "#010c13",
        "sideBarTitle.foreground": "#afd8f0",
        "statusBar.background": "#010c13",
        "statusBar.foreground": "#c7c6c6",
        "tab.activeBackground": "#010c13",
        "tab.activeForeground": "#ffffff",
        "tab.hoverBackground": "#025687",
        "tab.hoverForeground": "#ffffff",
        "tab.inactiveBackground": "#010c13",
        "tab.border": "#010c13",
        "terminal.background": "#010c13",
        "terminal.foreground": "#afd8f0",
        "terminalCursor.foreground": "#c7c6c6",
        "titleBar.activeBackground": "#010c13",
        "titleBar.inactiveBackground": "#010c13",
        "titleBar.border": "#010c13",
        "toolbar.hoverBackground": "#01283a",
        "welcomePage.background": "#010c13",
        "window.activeBorder": "#010c13",
        "window.inactiveBorder": "#010c13"
	}
	
Upon save the colors should change in the UI.

## Roadmap

1. Token Colorization
2. Git Diff Colorization

## License

[MIT License](./LICENSE)
