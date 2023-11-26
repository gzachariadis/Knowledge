## VS-Codium
This repository is used as a virtual storage space for everything I have managed to track down and use over the years, in my effort of creating, optimizing and maintaining my VS-Codium Workspace.

# Shortcuts

### Important Shortcuts

&nbsp;

- Show Settings -  ```Ctrl``` + ```,```

- Open Terminal -  ```Ctrl``` + ```'```

- Go to File - ```Ctrl``` + ```P```

- Command Pallet - ```Ctrl``` + ```Shift``` + ```P```

- Show/Hide Sidebar - ```Ctrl``` + ```B```

- Show/Hide Intelisense Autocomplete Feature - ```Ctrl``` + ```Space```

### Custom Shortcuts

- Split Editor Down
- Split Editor Left
- Split Editor Right


<kbd>Ctrl</kbd> + <kbd>Alt</kbd> + <kbd>OEM_8</kbd> + <kbd>Down Arrow </kbd>

```
"when": "editorFocus || editorTextFocus"
 ```

### Editor Need Knows

- Holding ```Alt``` (or ```Command```) and ```Arrow ↓ Down``` or ```Arrow ↑ Up``` will Move the cursored Line upwards or downwards



# My Settings

## Fonts

Settings

- Editor - Font Size : ```Place Here```


- Editor - Line Height : ```Place Here```

Calculated at ```Font Size``` times (x) ```Line Height``` so 14 x 1.3 = 18.2 (will give a 1.3 Line Height on a 14 pixels Font Size)

- Editor - Font Ligatures : ```False```

Resources 

- [Coding Fonts](https://coding-fonts.netlify.app/)
- [Nerd Fonts](https://www.nerdfonts.com/)

<br>

# Editor

Zoom

- Editor - Mouse Wheel Zoom : ✅ (Hold ```Ctrl``` and ```Zoom/Unzoom``` Editor with your ```Mouse Wheel``` )

Rules

- Editor - Rules :  ```"editor.rulers": [ 120 ]```

Renders a Verical Rule after Certain Number of Monospace Characters. As to say, break up the line after 120 characters or it's not going to be readable.

- Workbench - Color Customizations : ```"workbench.colorCustomizations": { "editorRuler.foreground": "#ff4081" }```

Changes the Color of the Rendered Ruler

Indentation

- Editor - Guides : Intentation ✅

Controls whether Editor Should Render Intent Guides

Word Wrap

- Editor - Word Wrap : ```off```

Wraps Lines of Code Based on Visibillity

Cursor 

- Editor - Curson Blinking : ```Phase```

Controls the Animation of the Cursor.

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

Python Snippets


Javascript Snippets


HTML & Emmet Snippets


CSS Snippets


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

- Pressing Right Click on an Function Reference or Function and Pressing ```Rename Symbol``` (F2) will change UNIVERSALLY anywhere you used it, the name of the function as well as the references to it.



# Personallization

[Theme]() 
[Icon Set]()

# Integrated Terminal

## [Oh My Posh](https://ohmyposh.dev/)
  
### Installation

```winget install JanDeDobbeleer.OhMyPosh -s winget```

### Requirements

- [Win-Get Cli](https://learn.microsoft.com/en-us/windows/package-manager/winget/#install-winget)
- [Posh-git](https://github.com/dahlbyk/posh-git)
- [Terminal Icons](https://github.com/devblackops/Terminal-Icons)
- [Python 3.11](https://apps.microsoft.com/detail/python-311/9NRWMJP3717K?hl=en-us&gl=US) - or Desired Version
- [Windows Terminal](https://apps.microsoft.com/detail/windows-terminal/9N0DX20HK701?hl=en-US&gl=US)
- [Windows Terminal Preview](https://apps.microsoft.com/detail/windows-terminal-preview/9N8G5RFZ9XK3?hl=en-US&gl=US)

### Theme

- [Ballerini](https://github.com/Ballerini-Theme/oh-my-posh/tree/main)

### Update

```winget upgrade JanDeDobbeleer.OhMyPosh -s winget```

### Configuration

#### Create Profile

```
codium $PROFILE
```

In case of Error, Run:

```
New-Item -Path $PROFILE -Type File -Force
```

Create the profile for Powershell.

#### Edit Confirguatrion 

Copy the Following Contents into Microsoft.PowerShell_profile.ps1

```
oh-my-posh init pwsh --config 'C:/Users/Reverse/Documents/WindowsPowerShell/ballerini.omp.json' | Invoke-Expression

Import-Module posh-git
Import-Module Terminal-Icons
```

### Troubleshooting Oh My Posh

Due to frequent updates of Oh My Posh, Antivirus software occasionally flags it (false positive). To ensure Oh My Posh isn't blocked you can either report it to your favorite Antivirus software as false positive (e.g. Report a false positive/negative to Microsoft for analysis) or create an exclusion for it. Exclusions should be added with the full path to the executable, you can get it with the following command from a PowerShell prompt:

```(Get-Command oh-my-posh).Source```

### Troubleshooting Powershell

if you get ```PowerShell says "execution of scripts is disabled on this system."``` run ```Set-ExecutionPolicy RemoteSigned```

### Resources

[Oh My Posh Guide](https://www.youtube.com/watch?v=-G6GbXGo4wo)



# TO-DO

- Learn More About Snippets
- Configure a Global Hotkey to Use for Shortcuts
- Configue oh-my-posh - Improve Terminal
- Create an alias for code in powershell to do codium instead.
