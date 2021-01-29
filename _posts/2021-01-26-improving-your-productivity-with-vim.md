---
title: Improving your Productivity with VIM
layout: post
permalink: /blog/:year/:title/
tags: vim
---

# IMPROVING YOUR PRODUCTIVITY WITH VIM (+ VS CODE SHORTCUTS)

When my peers see me writing code they think I'm possessed by some kind of dark forze which drives me to use a series of strange shortcuts for them. The reality is that, with practice, I have gained a great ability to put the mouse aside.

But, to be honest, the **path was hard**. The vas majority Vim's gurus uses such a great amount of shortcuts, macros, and patterns that shocked me out.

## The Basics

That's the entry point of this post, bring you a series of **most common** shortcurts that I use in my day to day as a web dev. Furthermore, there are also great shortcuts for VS Code that will take you to the next level.

### Modes

- `i` - For normal mode. In this mode you can _insert text before the cursor_.
- `esc` - Exit **insert mode**. A fat cursor appears and you will able to move throught the document.
- `ctrl+v` - Start visual mode (lines).
- `ctrl+V` - Start visual mode (blocks).

### Movement

- `h` - Left
- `j` - Down
- `k` - Up
- `l` - Right
- `0` - Jump to the start of the line.
- `$` - Jump to the end of the line.
- `G` - Go to the last line of the document.
- `zz` - Go to the first line of the document.

### Exiting

- `:q!`- Quit and throw away unsaved changes.
- `:wq` - Write (save) and quit.

### Most used shortcuts (for me)

**Insert text**

- `I`- Insert at the beginning of the line.
- `A` - Insert (append) at the end of the line.
- `o` - Append (open) a new line below the current line.
- `O` - Append (open) a new line above the current line.
- `gd` - Go to a definition (variable, function...).
- `gf` - Go to a specifil file.

**Editing**

- `r` - Replace a single character.
- `x` - Delete characters.
- `u` - Undo
- `ctrl+r` - Redo
- `ciw` - Replace the entire word.
- `cc` - Replace the entire line.

**Cut and paste**

- `yy` - Copy a line.
- `2yy` - Copy two lines.
- `p` - Paste after cursor.
- `P` - Paste before cursor.
- `dd` - Delete a line.
- `d$` - Delete to the end of the line.
- `dw` - Delete the characters of the word from the cursor position to the start of the next word.

**Pro commands**

- `line-number + G` - Go to this line.
- `/search-term` - Search inside the code. Move witch `n`.
- `%` - Move to matching character ({}, []).
- `:/s/text-to-change/new-text/gc` - Replaces the indicated text with the new one throughout the document.

## VS Code

- `ctrl+n` - Move forward through options in a drop-down panel.
- `ctrl+p` - Move backwards through options in a drop-down panel.
- `alt+arrow keys` - Move the current line up or down.
- `alt+shift+arrow keys` - Copy the current line up or down.

I hope you will find it useful for your projects. Honestly in my case I have notably improved the way I write code 😉
