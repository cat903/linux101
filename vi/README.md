# VIM

Vim stands for vi-improved, vi is a text editor made for unix developed by Bill Joy later an improved version of vi editor was developed by an individual named Bram Moolenaar. By default ubuntu or debian based distros come with minimal version of vim editor.

we cab check vim version by typing  `vi --version` into terminal.


#  Modes in vim
 - **Normal Mode-** This mode is vim's default mode. In this mode we can navigate inside the file.
 Normal mode can be accessed from other mode by pressing `Esc` or `C-[`

 - Insert Mode-Insert mode allows user to type & insert text.

 - Visual Mode-This mode allows us to move through a file, and to delete, copy, or paste a piece of text. When ever vim editor is opened up it's on command mode by default. we can also get into command mode by pressing  `Esc key`

<hr>

To open/create file using vim

```console
vi <filename>
```

if `<filename>` is already there it will openup that file, if `<filename>` doesn't exist when we save the file it will be created. if we terminate 
<hr>

To open up a file in Read only mode

```console
vi -R <filename>
or
view <filename>
```
# BasicCommands_NormalMode

|Command|Effects|
|-------------| -------------|
|h| will start typing text before the cursor's current position, until you are pressing the <Esc> key.|
|j|  will start typing text at the beginning of the current line, until you are pressing the <Esc> key.|
|k| will start typing after the cursor position|
|l| will start typing text at the end of current line|
|o| will insert newline after the current line|
|O| will insert a newline before the current line|

# BasicCommands_InsertMode

| Command  | Effects |
| ------------- | ------------- |
| i  | will start typing text before the cursor's current position, until you are pressing the <Esc> key.      |
| I  |  will start typing text at the beginning of the current line, until you are             pressing the <Esc> key. |
|a| will start typing after the cursor position|
|A| will start typing text at the end of current line|
|o| will insert newline after the current line|
|O| will insert a newline before the current line|
