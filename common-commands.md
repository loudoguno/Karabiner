# Common Commands Karabiner implementation helper doc 
# 
check bear: [© Common Commands Inventory](bear://x-callback-url/open-note?id=8F1ABCE5-EA8D-4701-B37F-401247836E16)

# km 
[Focus 1](keyboardmaestro://m=BC0DC738-DA57-4E7C-96B7-C45A251A93CC)
[Focus 2](keyboardmaestro://m=47BCDC4D-DF12-4F35-A689-3BAB571D42D3)
[Focus 3](keyboardmaestro://m=3B5CC299-C7B5-4789-AC85-811734CD030F)
[Focus 4](keyboardmaestro://m=8DFA7D0D-F082-4DCD-AF76-3FE732334AC0)
[Focus All Macros List (.script)](keyboardmaestro://m=EEB4B976-5A68-4298-B947-0143C1187276)
[Focus Groups List](keyboardmaestro://m=D431B49F-2FC1-4ADE-96FD-33DA77B631E8)
[Focus Macro Body (beginning) ❌ broken (FIXED)](keyboardmaestro://m=6DA47765-763F-4A2B-A6A8-69E21F04069A)
[Focus Macro Body (end)](keyboardmaestro://m=0761AE40-DFF7-48CA-B16B-E88BAAA11857)
[Focus Macro List](keyboardmaestro://m=460007FF-0910-44B9-BD38-0E179517D2EA)
[Focus Name Field (macro)](keyboardmaestro://m=1B16AE41-AA64-4A86-ADC0-6400DEF02D98)

2024-10-23 created own section
vscode://file/Users/loudog/Sync/config.files/Karabiner/karabiner.edn:329 

[ ] 


# Ways to approach

## previous strategy of finding unique simkey modes (e.g. n+w for New Window) and applying that to a common km name...
- works fine enough but does't
- have macros in each apps km group that share the same name so enabled/disabled by KM
- issues with Km's ability recognize overlay app as having focues (can't tell if ray notes is active..)


globe 🌐 with the letter a
# ❗  Consideratiis
## LR⌘ doesn't help with d+f d+s ect... 
## iPad considerations
- still can't 
## Drafts Actions consideratio 

# Universal Shortcut Wrapper Strategies
## App preferences
- cons include few apps offering highly customizable, doesn't sync
## macOS Custom App Keyboard Shortcuts (Keycue and CustomShortcuts)
### Custom Shortcuts 
- bad because can't version control, sync, not progromattic, 
    -  overwrites original
    -  clunky
    -  per-computer basis

## DefaultKeyBindings.dict
## Karabiner app filtering
## Keyboard Maestro
- issue with overlay apps

-----

ommon Commands
Main Window

## Core Essential
Command Palette
Quick Open/Jump to
Copy URL/Path/link/UID...
### Assorted Commands

Open link under cursor (follow)



## Window mgmt
New Window

Open Main Window
- Notes, Bear, Obsidian, electron apps, Drafts

## Text Editing
* Expand Text Selection
select line
move line up/down/left/right 
* set book mark

## code editing
Fold/collapse

Toggle Comment

## built-in/native
Find



## Text Logistics
Move line to



# LOG
# TODO
[ ] text editing


----------------------------------------------------------------
--------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------
-------- IGNORE

# COMMANDS

##### **© Main Window**
if electron or single window based
Window ->Main Window (Bear, Drafts, 
Apple Notes
Obsidian
Evernote

##### Help Menu
`⌘+/` (`⇧⌘+/`)
Bear, Apple Notes, Drafts, 
Obsidian

##### Table of Contents navigation\3\3\21
Pops up a clickable outline of document heads for easy navigation
- Bear 
  - set to ⌘⇧+o as extension of Quick open
- Notion 
- Marked
#### 🔤 Text Editing
##### Start/stop editing notebody
`⌘+↩` Apple Notes, Drafts, Bear
##### Move Text: up/down/left/right (indent-outdent)
`⌃⌘+←↑→↓` (preferred) Apn
`⌥⌘+up/down` in Bear
- `(⇧)⌘+⇥`

##### © Fold Text (expand/collapse)
- `⌘+9/0`
  - OMF
  - Taskpaper
- Apple Notes 
  - ⌥⌘+←/→ 
- some use 
- Bear
  - has fold and unfold all  menu command 
    - ![](CleanShot%202024-10-12%20at%2014.59.16@2x.png)<!-- {"width":149} -->
- Marked
  - `⌘+⌥+←` Collapse all sections, `⌘+⌥+→` Expand all sections

##### © follow link under cursor<!-- {"fold":true} -->
- Obsidian
- Roam
- Bear
##### © Backward/Forward page history
Pref`d+a` and `d+g` `⌘+[` `⌘+]`
- Finder: Back/Forward
⌘
##### © Tab left/right
##### © New Window
##### © move tab to new window
##### © Copy url, copy link, copy ID
##### © toggle bullet/list

#  🔷 CORE-
##### Help Menu/Cheatsheet `⌘⇧+/`
- GitHub 
##### ©  Command Palette
`⌘+p` 
- Roam 
`⌘⇧+p`
- conflict with menubarX
vs code
Drafts: 
Obsidian
Noton: `⌘+K` and `⌘+J`



##### © Quick Open/Jump To
    bear `⌘+o`
##### © pin/flag item
- Omf
- Bear
- Drafts
##### ©  Archive
#### GUI Interfac 
##### © Toggle Left Sidebar
`⌥⌘+s` preferred
Finder  
`⌘+\` Notion
`⇧⌘+s` Raycast, ChatGPT
- OMF, EN, Finder (apple) ⌥⌘+s/i
##### © Toggle Right Sidebar
`⌥⌘+i` preferred
##### © Focus 1/2/3
#### window/tab mgmt
##### © Zoom in/Out (font size) ⌘+/-
- Text edit ⇧⌘+
##### © 
#### text editing
##### © code block
##### © 
#### code editing
##### © comment
# --- 
##### assorted commands 
- rename `F2`, `⌘+l` 
  - Finder doesn't have one just 
  - Raycast AI has `⌥⌘+r` (thoughts around interest in Raycasts unmodifiable defaults...)
  - Finder is
- enable/disable
- duplicate
- delete
- print
- open, save, sace as
- preview ⌘+y
- new tab/window…
- close, hide
- copy, cut, paste, find, find next, replace, undo, redo
- toggle comment/notes c+d

## apps i care about
- roam 
- obsidian
- Bear
- apple notes, Reminders
- Dynalist
- vs code
- OMF
- Drafts


# Raycast commands
```
Name
Shortcut
Copy
⌘ + ⇧ + C
CopyDeeplink
⌘ + ⇧ + C
CopyName
⌘ + ⇧ + .
CopyPath
⌘ + ⇧ + ,
Duplicate
⌘ + D
Edit
⌘ + E
MoveDown
⌘ + ⇧ + ↓
MoveUp
⌘ + ⇧ + ↑
New
⌘ + N
Open
⌘ + O
OpenWith
⌘ + ⇧ + O
Pin
⌘ + ⇧ + P
Refresh
⌘ + R
Remove
⌃ + X
RemoveAll
⌃ + ⇧ + X
ToggleQuickLook

⌘ + Y
```

            test

                        ￼;test
        ￼;test  ￼;test

    ￼;test

