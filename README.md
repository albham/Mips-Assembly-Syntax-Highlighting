# Gnome Editors syntax highlighting for MAL

This file adds syntax highlighting for any editor which allows gtksourceview (e.g. gedit).

You will need to move it to the appropriate folder.
For linux, probably /usr/share/gtksourceview-2.0/language-specs
For windows, probably Program Files (x86)/gedit/share/gtksourceview-2.0/language-specs

If you have version 3.0 of gtksourceview, then the folders are:
For linux, probably /usr/share/gtksourceview-3.0/language-specs
For windows, probably Program Files (x86)/gedit/share/gtksourceview-3.0/language-specs


## Comparison Instructions

Table of register comparison conditional branch instructions :

| Signed     | Comp  | Unsigned |
|:-----------|:-----:|:---------|
| `blt`      |  <    | `bltu`
| `ble`      |  <=   | `bleu`
| `beq`      |  ==   | `beq`
| `bne`      | !=    | `bne`
| `bge`      |  >=   | `bgeu`
| `bgt`      |  >    | `bgtu`

Table of register comparison with zero conditional branch instructions :

| Signed          |  Comp  |
|-----------------|:------:|
| `bltz`          |  < 0   |
| `blez`          |  <= 0  |
| `beqz`          |  == 0  |
| `bnez`          | != 0   |
| `bgez`          |  >= 0  |
| `bgtz`          |  > 0   |

