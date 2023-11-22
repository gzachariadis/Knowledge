## VS-Codium
This repository is used as a virtual storage space for everything I have managed to track down and use over the years, in my effort of creating, optimizing and maintaining my VS-Codium Workspace.

# Fonts

Settings

- Editor - Font Size : ```13```


- Editor - Line Height : ```23``` Calculated at ```Font Size``` times (x) ```Line Height``` so 14 x 1.3 = 18.2 (will give a 1.3 Line Height on a 14 pixels Font Size)


- Editor - Font Ligatures : ```False```

<br>

Resources 

- [Coding Fonts](https://coding-fonts.netlify.app/)
- [Nerd Fonts](https://www.nerdfonts.com/)

# Shortcuts

### Important Shortcuts

&nbsp;

- Show Settings -  ```Ctrl``` + ```,```

- Open Terminal -  ```Ctrl``` + ```'```

- Go to File - ```Ctrl``` + ```P```

- Command Pallet - ```Ctrl``` + ```Shift``` + ```P```

### Custom Shortcuts

- Split Editor Down
- Split Editor Left
- Split Editor Right




<kbd>Ctrl</kbd> + <kbd>Alt</kbd> + <kbd>OEM_8</kbd> + <kbd>Down Arrow </kbd>

```
"when": "editorFocus || editorTextFocus"
 ```




# Editor

Zoom

- Editor - Mouse Wheel Zoom : ✅ (Hold ```Ctrl``` and ```Zoom/Unzoom``` Editor with your ```Mouse Wheel``` )

Rules

- Editor - Rules :  ```"editor.rulers": [ 120 ]``` (Renders a Verical Rule after Certain Number of Monospace Characters. As to say, break up the line after 120 characters or it's not going to be readable.)

- Workbench - Color Customizations : ```"workbench.colorCustomizations": { "editorRuler.foreground": "#ff4081" }``` (Changes the Color of the Rendered Ruler)

Indentation

- Editor - Guides : Intentation ✅ (Controls whether Editor Should Render Intent Guides)

Word Wrap

- Editor - Word Wrap : ```off``` (Wraps Lines of Code Based on Visibillity)

Cursor 

- Editor - Curson Blinking : ```Phase``` (Controls the Animation of the Cursor)

Minimap 

- Editor - Minimap: Enabled ❌


# Files

- Files - Default Language : ```${activeEditorLanguage}```

When creating a New File by Default the Editor will assign it the same language as the file you were editing. Say you editing a Python Script then CTRL+N will create a New Python File, same with a HTML file etc. 

- Files - Default Encoding : ```UTF-8```

When creating a File, it will be by Default a UTF-8 encoding file.

*** Note to Self, Find a Way to do the same with Encoding as Language or Find a Way when Creating or Editing UTF-16 files to be able to create them using UTF-16 Default Encoding ***


<br><br>

# Outline

- Outline: - Collapse Items:  ```alwaysExpand ```
- Outline: - Icons ✅
- Outline: - Problems: Badges ✅
- Outline: - Problems: Colors ✅
- Outline: - Show Functions ✅
- Outline: - Show Methods ✅
- Outline: - Show Modules ✅

Everything else is OFF.


# WorkBench

Preview

- Workbench - Editor: Enable Preview ❌

By default VS Code will Open a File in "Preview Mode" this means that when you click away, without editing the File or Double Clicking it, it will switch the Open Tab to the New File, since you were just "Previewing the File". I like to disable that and open the file instead.

- Workbench - Startup Editor: ```None```

Controls what to show upon Opening VS Code. I prefer None so Nothing.






# Snippets






# Extensions

Installed 

- Python by ms-python


# Tips

# Window Instances

I have 2 Instances Always Open - One on main Screen where I do side by side coding and one on a Vertical Monitor where I do my Functions. 
I prefer to set my functions in a different file, seperating logic from functions or church and state however you wanna call it.

# Uncategorized

- Holding CTRL + Clicking on a Function will Open that Function for you, even if in another file.

- Pressing CTRL + Space spawns Intellisense.





# Personallization

[Theme]() 
[Icon Set]()



