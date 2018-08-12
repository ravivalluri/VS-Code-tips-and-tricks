# Visual Studio Code tips and tricks

A collections of Visual Studio code extensions, snippets, tics and tricks. These extension and shortcut key will make you productive front end developer.

## Extensions

### 1. Javascript
- [JavaScript (ES6) code snippets](https://marketplace.visualstudio.com/items?itemName=xabikos.JavaScriptSnippets)
- [JS Snippet](https://marketplace.visualstudio.com/items?itemName=nathanchapman.JavaScriptSnippets)
- [JS Refactor](https://marketplace.visualstudio.com/items?itemName=cmstead.jsrefactor)
- [Quokka.js](https://quokkajs.com/)
- [ESLint](https://marketplace.visualstudio.com/items?itemName=dbaeumer.vscode-eslint) 

### 2. React
- [React Extension Pack](https://marketplace.visualstudio.com/items?itemName=jawandarajbir.react-vscode-extension-pack)
- [Reactjs code snippets](https://marketplace.visualstudio.com/items?itemName=xabikos.ReactSnippets)
- [React Native Tools](https://marketplace.visualstudio.com/items?itemName=vsmobile.vscode-react-native)
- [ES7 React/Redux/GraphQL/React-Native snippets](https://marketplace.visualstudio.com/items?itemName=dsznajder.es7-react-js-snippets)


### 3. Angular
- [Angular 6 Snippets](https://marketplace.visualstudio.com/items?itemName=Mikael.Angular-BeastCode)
- [Angular Language Service](https://marketplace.visualstudio.com/items?itemName=Angular.ng-template)

### 4. Vue:
- [Vetur](https://marketplace.visualstudio.com/items?itemName=octref.vetur)
- [Vue.js Extension Pack](https://marketplace.visualstudio.com/items?itemName=mubaidr.vuejs-extension-pack)
- [Vue 2 Snippets](https://marketplace.visualstudio.com/items?itemName=hollowtree.vue-snippets)


### 5. CSS:
- [IntelliSense for CSS](https://marketplace.visualstudio.com/items?itemName=Zignd.html-css-class-completion)
- [CSS peak](https://marketplace.visualstudio.com/items?itemName=pranaygp.vscode-css-peek)

### 6. Productivity
- [Debugger for Chrome](https://marketplace.visualstudio.com/items?itemName=msjsdiag.debugger-for-chrome)
- [VS Live Share](https://marketplace.visualstudio.com/items?itemName=MS-vsliveshare.vsliveshare)
- [REST Client](https://marketplace.visualstudio.com/items?itemName=humao.rest-client)
- [Open in browser](https://marketplace.visualstudio.com/items?itemName=techer.open-in-browser)
- [Auto Import](https://marketplace.visualstudio.com/items?itemName=steoates.autoimport)
- [Path Intellisense](https://marketplace.visualstudio.com/items?itemName=christian-kohler.path-intellisense)
- [Excel Viewer](https://marketplace.visualstudio.com/items?itemName=GrapeCity.gc-excelviewer)

### 7. Git
- [GitLens](https://marketplace.visualstudio.com/items?itemName=eamodio.gitlens)
- [Project Manager](https://marketplace.visualstudio.com/items?itemName=alefragnani.project-manager)
- [Git History](https://marketplace.visualstudio.com/items?itemName=donjayamanne.githistory)
- [Git Blame](https://marketplace.visualstudio.com/items?itemName=waderyan.gitblame)

### 8. Others
- [Prettier](https://marketplace.visualstudio.com/items?itemName=esbenp.prettier-vscode)
- [SQL Server](https://marketplace.visualstudio.com/items?itemName=ms-mssql.mssql)
- [Docker](https://marketplace.visualstudio.com/items?itemName=PeterJausovec.vscode-docker)
- [VSCode icons](https://marketplace.visualstudio.com/items?itemName=robertohuertasm.vscode-icons)
- json


### 9. Writing Your Own Extension
- [Building extensions](https://code.visualstudio.com/docs/extensions/overview)
- [Extension Examples](https://code.visualstudio.com/docs/extensions/samples)


## General Capabilities

### 1. Command Palette

`Shift + Cmd + P` - Access to almost anything that you can do in the editor (and you can see keyboard shortcuts)

### 2. Explorer

`Cmd + P` - Open/find files in your project. Type a `?` to see other modes that you use for searching.

### 3. Toggle Sidebar

`Cmd + B` - Toggle open/closed the sidebar. On a smaller screen, you can save space by closing it and using Cmd + P to open files.

### 6. Minimap

The minimap is a small overview of your file in the gutter. Use the Command Palette (search for "minimap") to toggle this on/off.

### 7. Terminal

`Ctrl + ~` - Open a terminal in the root directory of the project that you are editing. Can split the terminal and move it between being docked on the bottom or side.

### 8. Calling code from command-line

`code --help` - From a terminal, you can run the `code` command-line tool. The most common use of this would be to open the current directory that your terminal is in (perhaps after cloning a repo or creating a new project).

## Customizing VS Code

### 11. Settings

`Cmd + ,` - Access all of the settings. Override at a user (all instances of VS Code for your user) or workspace level (this instance of VS Code). Workspace settings are saved either in the `.vscode` folder when you are editing a single directory or when using Workspaces they are saved in the single workspace file.

### 12. Font With Ligature

A popular choice is [Fira Code](https://github.com/tonsky/FiraCode). After installing, you will want to update your VS Code settings `"editor.fontFamily": "Fira Code", "editor.fontLigatures": true`.

## Navigation

### 14. Basic Navigation in a File

`Cmd + Up` - Top of file
`Cmd + Down` - Bottom of file
`Cmd + Left` - Beginning of line
`Cmd + Right` - End of line
`Alt + Left` - Move word by word to the left on a line
`Alt + Right` - Move word by word to the right on a line

Add `Shift` modifier to any of the above to select while moving

`Ctrl + G` - Go to a specific line in the file

### 15. Splitting / Moving Windows

`Cmd + \` to split the window

Can find other splits like splitting down (and bind to keys as necessary|) in the Command Palette.

### 16. Navigating Between Windows

`Cmd + 1` to go to first set of tabs. `Cmd + 2, 3, 4, 5, etc.` to move to additional sets of tabs.
`Ctrl + Tab` navigate between files in a group.

### 17. Navigating Symbols

`Shift + Cmd + O` - navigate between symbols (methods, properties, variables, etc.) in a file.
`Cmd + T` navigate between symbols for your entire project. 
Much faster than searching or scrolling and provides good context (variable vs. method).

### 18. Find in File / Global

`Cmd + F` - find in a file
`Shift + Cmd + F` - find globally
Can add choose whether match is case sensitive, matches partial words, or to use a regular expression.
You can include specific folders (maybe only sometimes search `./node_modules`) or you can unclick the blue box on the gear for files to exclude and it will search all files.

### 19. Find All References / Peek + GoTo Definition

`Shift + F12` - Find all references - find all the places where a function is called (traces dependencies through your files).
`F12` - Go To Definition - jump to where a function is defined
`Alt + F12` - Peek Definition  - show an inline view of the function definition

Also, you can hold down `Cmd` and hover over a function and see a small peek into the definition above and `Cmd + Click` to navigate to the definition.

## Editing

### 20. Creating Files / Deep Path

When creating a new file from the file explorer, you can type a deep path (`/src/app/data/index.js`) and it will create necessary directories along the way.

### 22. Refactoring

`Ctrl + Shift + R` - VS Code supports a number of refactoring options. One that I use often is to select a string, and choose to turn it into a constant. You can also select blocks of code and refactor into a method along with a number of other options.

`F2` - Rename symbol. When you select a symbol name (argument, properties, variable, function, etc.) and choose to Rename symbol it will allow you to rename all instances of it in the current scope (so much better than a find/replace).

### 24. Multi-cursor

Allows you to have multiple active cursors that all respond to your keystrokes. Each cursor can also copy/paste its own buffer.

`Alt + Click`  - will add an additional cursor
`Cmd + D` will select the next instance of the text that you have selected with an additional cursor
`Shift + Cmd + L` will select all instances of the text that you have selected with cursors for each
From the Command Palette you can also select a block of lines and choose to "Add Cursors to Line Ends"

Moving around with `Alt + Left` or `Alt + Right` and selecting with the `Shift` modifier is useful in scenarios where you want each cursor to copy a separate piece of text.

### 25. Move line up/down

`Alt + Up` or `Alt + Down` - move a line up or down (without having to cut and paste it).

### 26. Folding / Unfolding

`Cmd + K + 1, 2, 3, 4` - Fold all of the code at a certain level. Sometimes useful in files to collapse the low-level details, while you get an overview and then dig into the specific area that you need to change. I like to use this in test files.
`Cmd + K, Cmd + J` - Unfold all of the code

### 27. Undo Cursor Position

`Cmd + U` - brings you back to the last place that you edited
`Ctrl + -` - cycles through recent places that you were editing

### 28. Problems

Extensions (like ESLint) can contribute to a list of problems in a file. When problems are found, the file turns red in the file explorer and you can see red in the gutter of the file where the problems exist.

`Shift + Cmd + M` - opens the problem list to see all problems in a file
`F8` - cycles through the problems

## Source Control

VS Code comes with Git support built-in and has extensions for any other source control systems that you might be using.

### 29. Comparing Two Files

`Cmd + Click` on two files in the file explorer and right-click on either to choose "Compare Selected". This allows you to diff any two files in your project.

### 30. Source Control - GIT

The Source Control tab of the sidebar allows you to see changed or staged files and commit files or access other commands. The status bar in the bottom allows access to switching or creating branches. 

In the editor, changes have a blue indicator in the gutter, new lines have a green indicator, and deleted lines have a red indicator. You can click on the indicator in the gutter to see a diff of changes, revert the changes, or even stage individual changes in a file.

## Snippets

### 31. Creating Snippets

Go to `Code > Preferences > User Snippets` to edit your snippets. You can define snippets at a global level or per language (most common). 

Some sample snippets:

```
	"Print var to console": {
		"prefix": "logv",
		"body": [
			"console.log( \"$1\", $1 );",
			"$2"
		],
		"description": "Log a variable to console"
	}
 ```

This snippet is accessed when typing `logv` and then tabbing. The first tab stop will create two cursors with one in the quotes and one in the second argument. This allows you to type a variable name and hit tab again to move to the next line of code.

Here is one that I use in testing:

```
"calledOnce.and.calledWith": {
		"prefix": "shc",
		"body": [
			"$1.should.be.called${2|Once,Twice,Thrice|}",
			"	.and.calledWith( $3 );",
			"$4"
		]
	}
```

In this one, I can type a variable name and then choose between `Once`, `Twice`, or `Thrice` before moving to assert the arguments that it was called with.

For testing (mocha), I often use simple snippets as well:

```
"describe": {
		"prefix": "des",
		"body": [
			"describe( \"$1\", () => {",
			"	$2",
			"} );",
			""
		]
	},
	"it": {
		"prefix": "itt",
		"body": [
			"it( \"$1\", () => {",
			"	$2",
			"} );",
			""
		]
	},
	"beforeEach": {
		"prefix": "bef",
		"body": [
			"beforeEach( () => {",
			"	$1",
			"} );",
			""
		]
	}
  ```

Further info: https://code.visualstudio.com/docs/editor/userdefinedsnippets

## Debugging

### 32. Debug a Node Program

VS Code is known for how well it can debug problems like those running in Node. When going to the debug tab of the sidebar, you can define a run configuration by clicking the gear icon. 

Common choices for debugging node would be to:
`Launch Program` - launch and debug your program directly from VS Code
`Attach by Process ID` - allows you to pick a process running on your machine to attach to (run program like `node --inspect index.js` to allow attaching or `node --inspect-brk index.js` to force the program to wait until the debugger attaches
`Attach to Remote Program` - allows you to specific an `address` and `post` to attach to a program running remotely (perhaps in a docker container on your machine).

The launch configurations support a variety of properties to configure your debugging experience that are futher described in the documentation:

Basic debugging info: https://code.visualstudio.com/docs/editor/debugging
Node.js specific info: https://code.visualstudio.com/docs/nodejs/nodejs-debugging#_attaching-to-nodejs

### 33. Debug Chrome

Install [this extension](https://marketplace.visualstudio.com/items?itemName=msjsdiag.debugger-for-chrome). This will allow you to create Chrome launch configurations for either launching a web application in Chrome or attaching to an existing Chrome instance. With this extension you can set breakpoints in VS Code and hit them while using your web application in Chrome.

Additional documentation for the extension: https://github.com/Microsoft/vscode-chrome-debug

## Honorable Mentions

- [Tasks](https://code.visualstudio.com/docs/editor/tasks) - run npm, grunt, gulp scripts or integrate your own external calls into vs code.

- [Multi-root Workspaces](https://code.visualstudio.com/docs/editor/tasks) - include multiple directories in a single instance of vs code.

- [Insider edition](https://code.visualstudio.com/insiders/) - Install a build that has the latest release each day

- [VS Live Share](https://marketplace.visualstudio.com/items?itemName=MS-vsliveshare.vsliveshare) - allows real-time collaboration. 

    - Sign-in with Github or Microsoft credentials
    - Start a collaboration session and send the link to another user
    - User can join your session and navigate your files and make edits (with permissions)
    - Can also share your terminal (read-only or read/write)
    - Can share a port (like if you are running a web application on port 8080, you can share port and user can run in their machine).

- Keyboard Shortcut Sheets (PDF)

    - [Windows](https://code.visualstudio.com/shortcuts/keyboard-shortcuts-windows.pdf)
    - [Mac](https://code.visualstudio.com/shortcuts/keyboard-shortcuts-macos.pdf)
    - [Linux](https://code.visualstudio.com/shortcuts/keyboard-shortcuts-linux.pdf)



Special Thanks! Ryan Niemeyer ryan@knockmeout.net