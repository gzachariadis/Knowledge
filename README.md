# VS-Codium
This repository is used as a virtual storage space for everything I have managed to track down and use over the years, in my effort of creating, optimizing and maintaining my VS-Codium Workspace.

## Table of Contents

- [VS-Codium](#vs-codium)
  * [To-Do](#to-do)
- [Features](#features)
  * [Task Runner](#task-runner)
    + [Resources To-Do](#resources-to-do)
- [Shortcuts](#shortcuts)
  * [Workflow Shortcuts](#workflow-shortcuts)
  * [Custom Shortcuts](#custom-shortcuts)
  * [Editor Shortcuts](#editor-shortcuts)
  * [Code Editing Shortcuts](#code-editing-shortcuts)
    + [Lines](#lines)
    + [Words](#words)
  * [Code Formatting Shortcuts](#code-formatting-shortcuts)
  * [Resources](#resources)
- [My Settings](#my-settings)
  * [Fonts](#fonts)
  * [Editor](#editor)
    + [Zoom](#zoom)
    + [Rules](#rules)
    + [Indentation](#indentation)
    + [Word Wrap](#word-wrap)
    + [Cursor](#cursor)
    + [Minimap](#minimap)
  * [Files](#files)
  * [Outline](#outline)
  * [WorkBench](#workbench)
    + [Preview](#preview)
    + [List](#list)
    + [Window](#window)
    + [Breadcrumbs](#breadcrumbs)
  * [Snippets](#snippets)
  * [Extensions](#extensions)
  * [Tips](#tips)
  * [Window Instances](#window-instances)
  * [Uncategorized](#uncategorized)
  * [Personallization](#personallization)
  * [Integrated Terminal](#integrated-terminal)
    + [[Oh My Posh](https://ohmyposh.dev/)](#-oh-my-posh--https---ohmyposhdev--)
      - [Installation](#installation)
      - [Requirements](#requirements)
      - [Theme](#theme)
      - [Update](#update)
      - [Configuration](#configuration)
        * [Create Profile](#create-profile)
        * [Edit Confirguatrion](#edit-confirguatrion)
        * [Troubleshooting Oh My Posh](#troubleshooting-oh-my-posh)
        * [Troubleshooting Powershell](#troubleshooting-powershell)
  * [Resources](#resources-1)

<small><i><a href='http://ecotrust-canada.github.io/markdown-toc/'>Table of contents generated with markdown-toc</a></i></small>

## To-Do

- Find a Way to Turn a Selected Line into Markdown Link (or something else)
- Learn More About Snippets
- Configure a Global Hotkey to Use for Shortcuts
- Configue oh-my-posh - Improve Terminal
- Create an alias for code in powershell to do codium instead.

# Features

## Task Runner

### Resources To-Do

- [Integrate with External Tasks via Tasks](https://code.visualstudio.com/docs/editor/tasks)

- [VSCode: 10 Most Useful Tips And Tricks - Code Runner Chapter](https://www.youtube.com/watch?v=cVGMldhVRxU&list=PL0w2UavVM8W-nw8qz-JnZwXLjzldoTX6f&t=533s)

# Shortcuts

## Workflow Shortcuts

- Show Settings -  ```Ctrl``` + ```,```

- Command Pallet - ```Ctrl``` + ```Shift``` + ```P```

- Show/Hide Sidebar - ```Ctrl``` + ```B```

- Show/Hide Intelisense Autocomplete Feature - ```Ctrl``` + ```Space```

- Zen Mode -  ```Ctrl``` +  ```K``` then  ```F```

### Navigation 

- Search Files by name/Go to File - ```Ctrl``` + ```P```

- Switch Between Open Tabs - ```Ctrl``` + ```Tab``` (Optional : ```Shift``` to Tab Backwards)

- Switch Between Open Tabs vol.2 - ```Alt``` + ```1``` to ```9``` (1 = First Tab, 2 = Second Tab etc. etc.)

- Switch Between Editor Windows - ```Ctrl``` + ```1``` to ```9``` (1 = First Editor, 2 = Second Editor etc. etc.)

### Terminal 

- Show/Hide Terminal -  ```Ctrl``` + ```'```

- Clear Terminal - ```Ctrl``` + ```L```

## Custom Shortcuts

- Split Editor Down

- Split Editor Left

- Split Editor Right

## Editor Shortcuts

- Close Tab - ```Ctrl``` + ```W```

- Open a Right Side View - ```Ctrl``` + ```\``` (next to right shift)

<br>
<br>

- Change Text Size - ```Ctrl``` + ```+``` or ```-```

<br>
<br>

## Editing Shortcuts 

### Lines

- Select Current Line - ```Ctrl``` + ```L```

- Delete Current Line - ```Ctrl``` + ```Shift``` + ```K```

- Indent/Outdent Current Line - ```Ctrl``` + ```[``` or ```]```

- Comment Line - ```Ctrl``` + ```Slash (/)``` (next to Right Shift)

- Duplicate Current Line Upwards/Downwards - ```Shift``` + ```Alt``` + ```Arrow ↓ Down``` or ```Arrow ↑ Up```

- Move the Line Upwards or Downwards - Hold ```Alt``` (or ```Command```) and ```Arrow ↓ Down``` or ```Arrow ↑ Up```.

- Go to the end of Line - ```End```

<br>

- Highlight Everything from Cursor to End of Line - ```Shift``` + ```End```

- Switch Betweeen Quotes - ```Ctrl``` + ```Backslash``` (Requirement ---> [Toggle Quotes Extension](https://open-vsx.org/extension/BriteSnow/vscode-toggle-quotes))

<br>

- Extend your Selection to the Following Line -  Hold ```Shift``` and ```Arrow ↓ Down``` or ```Arrow ↑ Up```.

### Words

- Select Current Word - ```Ctrl``` + ```D```

- Go to Start/End of Current Word - ```Ctrl``` +  ```Arrow  Left``` or ```Arrow Right ▶️ ``` (Also Used to Navigate Faster Between Words instead of Characters)

- Select Words Going Forwards/Backwards - ```Ctrl``` + ```Shift``` + ```Arrow  Left``` or ```Arrow Right ▶️ ```

<br>
<br>
<br>
<br>

## Formatting

- Code Formatting - ```Ctrl``` + ```K``` then ```Ctrl``` + ```F``` 

- Fold/Unfold Code - Select a Piece of Code then ```Ctrl``` + ```Shift``` + ```[``` or ```]```

- Fold based on Indentation Level - ```Ctrl``` + ```K``` then ```Ctrl``` + ```1``` to ```5``` (based on Indentation Level you want to Fold - pressing 2 will fold 3-5)

- Shift a Block of Code Left or Right - ```Shift``` + ```Tab```

### Navigation

- Go to Definition of a Function - ```Ctrl``` + ```Left Click```

- Search for a Function/Variable Declaration (AKA Go to Symbol) - ```Ctrl``` + ```Shift```  + ```O``` (Letter O not 0)

- Go to Specific Line - ```Ctrl``` + ```G``` then type the Line Number eg. 11

### Files

- Search Within a File - ```Ctrl``` + ```F```

- To Open the Replace under Find - ```Ctrl``` + ```H```

- To Replace All Instances of Find - ```Ctrl``` + ```Alt``` + ```Enter```

### Multicursor

- Select all Instances of a Selection and Edit them Simultaneously -  ```Ctrl``` + ```Alt``` + ```L```
  
- Having a Multicursor and pressing ```Ctrl``` + ```Shift``` + ```L``` will Select (given the cursor position) the last common word between those strings. Eg. havigng background-color on 3 lines and hovering a multicursor anywhere withing 'color' will highlight the word 'color' in all 3 lines.

- Select Something then Pressing ```Ctrl``` + ```D``` will Select the Next Instance of Selected Thing and add a Multicursor, pressing ```Ctrl``` + ```D``` again will also select the following etc. etc. 

- Create Secondary Cursor on Line Below - Placing a Curson then Holding ```Alt``` (or ```Command```) and ```Ctrl``` and ```Arrow ↓ Down``` or ```Arrow ↑ Up```.

- Spawn Multiple Cursors - ```Ctrl``` +  ```Shift``` +  ```Alt``` +  ```Up Arrow``` or  ```Down Arrow```

<br>
<br>
<br>
<br>

## Resources

- [VS Code Tips & Tricks](https://github.com/microsoft/vscode-tips-and-tricks)
- [Shortcuts Povio Blog](https://povio.com/blog/shortcut-your-way-to-faster-coding-in-visual-studio-code/#:~:text=Select%20current%20line%3A%20Ctrl%20%2B%20L)
- [The best VS Code trick that you're probably not using.](https://www.youtube.com/watch?v=mOeWy5Q1P4E)

<br>
<br>
<br>
<br>
<br>
<br>
<br>
<br>

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

## Editor

### Zoom

- Editor - Mouse Wheel Zoom : ✅ (Hold ```Ctrl``` and ```Zoom/Unzoom``` Editor with your ```Mouse Wheel``` )

### Rules

- Editor - Rules :  ```"editor.rulers": [ 120 ]```

Renders a Verical Rule after Certain Number of Monospace Characters. As to say, break up the line after 120 characters or it's not going to be readable.

- Workbench - Color Customizations : ```"workbench.colorCustomizations": { "editorRuler.foreground": "#ff4081" }```

Changes the Color of the Rendered Ruler.

### Indentation

- Editor - Guides : Intentation ✅

Controls whether Editor Should Render Intent Guides

### Word Wrap

- Editor - Word Wrap : ```off```

Wraps Lines of Code Based on Visibillity

### Cursor 

- Editor - Curson Blinking : ```Phase```

Controls the Blinking Animation of the Cursor.

- Editor - Cursor Smooth Caret Animation : ```on```

Allows for a small animation as cursor moves from place to place

- Editor - Smooth Scrolling : ✅

### Minimap 

- Editor - Minimap: Enabled ❌

## Files

- Files - Default Language : ```${activeEditorLanguage}```

When creating a New File by Default the Editor will assign it the same language as the file you were editing. Say you editing a Python Script then CTRL+N will create a New Python File, same with a HTML file etc. 

- Files - Default Encoding : ```UTF-8```

When creating a File, it will be by Default a UTF-8 encoding file.

*** Note to Self, Find a Way to do the same with Encoding as Language or Find a Way when Creating or Editing UTF-16 files to be able to create them using UTF-16 Default Encoding ***

<br><br>

## Outline

- Outline: - Collapse Items:  ```alwaysExpand ```
- Outline: - Icons ✅
- Outline: - Problems: Badges ✅
- Outline: - Problems: Colors ✅
- Outline: - Show Functions ✅
- Outline: - Show Methods ✅
- Outline: - Show Modules ✅

Everything else is OFF.

## WorkBench

### Preview

- Workbench - Editor: Enable Preview ❌

By default VS Code will Open a File in "Preview Mode" this means that when you click away, without editing the File or Double Clicking it, it will switch the Open Tab to the New File, since you were just "Previewing the File". I like to disable that and open the file instead.

- Workbench - Startup Editor: ```None```

Controls what to show upon Opening VS Code. I prefer None so Nothing.

### List

- Workbench - Smooth Scrolling : ✅

Enables Smooth Scrolling along Lists and Trees.

### Window

- Window - Zoom Level: ```0```

Adjusts the Zoom Level on the Whole Window - Original size is 0.

### Breadcrumbs

- Workbench - Breadcrumbs :  ❌

Disables Breadcrumbs Fully.

## Snippets

Python Snippets


Javascript Snippets


HTML & Emmet Snippets


CSS Snippets

## Extensions

Installed 

- Python by ms-python

## Tips

## Window Instances

I have 2 Instances Always Open - One on main Screen where I do side by side coding and one on a Vertical Monitor where I do my Functions. 
I prefer to set my functions in a different file, seperating logic from functions or church and state however you wanna call it.

## Uncategorized

- Holding CTRL + Clicking on a Function will Open that Function for you, even if in another file.

- Pressing CTRL + Space spawns Intellisense.

- Pressing Right Click on an Function Reference or Function and Pressing ```Rename Symbol``` (F2) will change UNIVERSALLY anywhere you used it, the name of the function as well as the references to it.

## Personallization

[Theme]() 
[Icon Set]()

## Integrated Terminal

### [Oh My Posh](https://ohmyposh.dev/)
  
#### Installation

```winget install JanDeDobbeleer.OhMyPosh -s winget```

#### Requirements

- [Win-Get Cli](https://learn.microsoft.com/en-us/windows/package-manager/winget/#install-winget)
- [Posh-git](https://github.com/dahlbyk/posh-git)
- [Terminal Icons](https://github.com/devblackops/Terminal-Icons)
- [Python 3.11](https://apps.microsoft.com/detail/python-311/9NRWMJP3717K?hl=en-us&gl=US) - or Desired Version
- [Windows Terminal](https://apps.microsoft.com/detail/windows-terminal/9N0DX20HK701?hl=en-US&gl=US)
- [Windows Terminal Preview](https://apps.microsoft.com/detail/windows-terminal-preview/9N8G5RFZ9XK3?hl=en-US&gl=US)

#### Theme

- [Ballerini](https://github.com/Ballerini-Theme/oh-my-posh/tree/main)

#### Update

```winget upgrade JanDeDobbeleer.OhMyPosh -s winget```

#### Configuration

##### Create Profile

```
codium $PROFILE
```

In case of Error, Run:

```
New-Item -Path $PROFILE -Type File -Force
```

Create the profile for Powershell.

##### Edit Confirguatrion 

Copy the Following Contents into Microsoft.PowerShell_profile.ps1

```
oh-my-posh init pwsh --config 'C:/Users/Reverse/Documents/WindowsPowerShell/ballerini.omp.json' | Invoke-Expression

Import-Module posh-git
Import-Module Terminal-Icons
```

##### Troubleshooting Oh My Posh

Due to frequent updates of Oh My Posh, Antivirus software occasionally flags it (false positive). To ensure Oh My Posh isn't blocked you can either report it to your favorite Antivirus software as false positive (e.g. Report a false positive/negative to Microsoft for analysis) or create an exclusion for it. Exclusions should be added with the full path to the executable, you can get it with the following command from a PowerShell prompt:

```(Get-Command oh-my-posh).Source```

##### Troubleshooting Powershell

if you get ```PowerShell says "execution of scripts is disabled on this system."``` run ```Set-ExecutionPolicy RemoteSigned```

## Resources

- [Oh My Posh Guide](https://www.youtube.com/watch?v=-G6GbXGo4wo)
- [Povio Shortcuts](https://povio.com/blog/shortcut-your-way-to-faster-coding-in-visual-studio-code/#:~:text=Select%20current%20line%3A%20Ctrl%20%2B%20L)

<br>
<br>
<br>
<br>
<br>
<br>
<br>
<br>

<kbd>Ctrl</kbd> + <kbd>Alt</kbd> + <kbd>OEM_8</kbd> + <kbd>Down Arrow </kbd>

```
"when": "editorFocus || editorTextFocus"
 ```

