# Vim

## Basic Commands

**Open a file in VIM**
```bash
vim <file_name>
```

**Exit VIM**
- In command mode: `:q`
- Quit without saving: `:q!`
- Save and quit: `:wq`

**Save a file**
```bash
:w
```

**Save and quit VIM**
```bash
:wq
```

## Navigation

**Move cursor up, down, left, or right**
- Up: `k`
- Down: `j`
- Left: `h`
- Right: `l`

**Go to the beginning of the line**
```bash
0
```

**Go to the end of the line**
```bash
$
```

**Go to a specific line number**
```bash
:<line_number>
```

## Editing

**Switch to insert mode (start editing)**
```bash
i
```

**Delete a character**
```bash
x
```

**Delete a word**
```bash
dw
```

**Delete an entire line**
```bash
dd
```

**Undo last change**
```bash
u
```

**Redo the last undone change**
```bash
Ctrl + r
```

## Copy & Paste

**Copy (yank) a line**
```bash
yy
```

**Paste the copied line below the cursor**
```bash
p
```

**Paste the copied line above the cursor**
```bash
P
```

## Search & Replace

**Search for a word**
```bash
/<word>
```

**Search and replace in the file**
```bash
:%s/<old_word>/<new_word>/g
```

**Move to the next occurrence of a search result**
```bash
n
```

**Move to the previous occurrence of a search result**
```bash
N
```

## Visual Mode

**Select text to copy or delete**
```bash
v
```

**Select entire lines**
```bash
V
```

**Select a block of text**
```bash
Ctrl + v
```

## Miscellaneous

**Open a new file**
```bash
:e <new_file_name>
```

**Close current file and open a new file**
```bash
:e! <new_file_name>
```

**View line numbers**
```bash
:set number
```

**Hide line numbers**
```bash
:set nonumber
```
