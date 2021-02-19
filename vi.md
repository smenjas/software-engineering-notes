# vi Cheat Sheet
- vi is an interface for the ex editor. It is one of many [Unix text editors](editors.md).
- vi has two modes: command and insert. You begin in command mode.

## Insert
```
i	insert text before the cursor
I	insert text at the beginning of the line
a	append text after the cursor
A	append text at the end of the line
o/O	insert a blank line below/above the cursor
Esc	return to command mode (when in doubt, hit Esc a few times)
```

## Replace
```
r	replace one character, then return to command mode
R	replace text until you hit Esc (overtype)
c	replace a text object (e.g. cw will change a word)
```

## Cut/Delete
```
x	delete the character under the cursor
X	delete the character to the left of your cursor
d	delete a text object (e.g. dw will delete a word)
D	delete from the current character to the end of the line
```

## Copy/Paste
```
y		copy a text object (e.g. yw will yank a word)
p/P		paste text below/above the cursor
"[a-z][n]yy   	yank [n] lines into named buffer [a-z]
"[a-z]p/P	put the contents of the buffer [a-z] below/above the cursor
```

## Undo
```
u	undo the last change (press u again to "undo the undo")
U	undo all recent changes to the current line
:u	undo the last command
```

## Text Objects
```
0	beginning of the line (home)
$	end of the line (end)

b	back one word (or the beginning of a word)
e	to the end of a word
w	forward one word
(B, E, and W ignore punctuation)

H	top of the screen
L	bottom of the screen
M	middle of the screen

(	previous sentence
)	next sentence
[	previous section
]	next section
```

## Navigate
```
 h      j     k     l (ell)
left   down   up   right

^b	scroll up one screen (page up)
^f	scroll down one screen (page down)
^u	scroll up half a screen
^d	scroll down half a screen

[n]G	go to line [n] (G by itself takes you to the last line)
:[n]	go to line [n]

/[s]	search for [s]
?[s]	search backwards for [s]
n	repeat the search
N	repeat the search backwards
```

## Miscellaneous
```
.	repeat the last command (e.g. dd... will delete a few lines)
J	join the current line with the next line
^T 	set autoindent one tab to the right
^D 	set autoindent one tab to the left
>>	shift text one tab to the right
<<	shift text one tab to the left
```

## Combinations
```
[command][number][text object] (e.g. "d2w" will delete 2 words)
[number][command][text object] (e.g. "2dw" will delete 2 words)
[command][command] affects an entire line (e.g. dd will delete a line)
```

## Save/Quit
```
ZZ	save and quit
:wq	save and quit
:w	save, but don't quit
:q	quit, if no edits have been made
:e!	revert to the last saved version
:q!	wipe out all edits and exit vi
```

## Customize ex
Options apply during the current session only. Edit your `.exrc` file to make permanent changes, but make sure you know what you're doing!
```
:set			view only those options which are currently in effect
:set all		view a listing of other options
:set number		display line numbers
:set showinsert		show insert flag ("I") when in insert mode
:set wrapmargin=[n]	specify a right margin of [n] character widths
:set tabstop=[n]	sets default tab space to [n] character widths
:set ai			set autoindent
```
After setting autoindent, enter insert mode and press tab. From this point on vi will indent each line to this point. Press Esc to stop the indentations.

## More ex Commands
```
:sh			escape temporarily to a shell
^d			return from shell to vi
:![command]		execute UNIX command without leaving vi
:r![command]		read in output of [command]
:r [file]		read in [file]
:r !sort [file]		read in [file], after passing through sort
:$r [file]		append [file] to the end of the current document
:n			open next file (works with wildcard filenames)
:^g			list current line number
```

## Fancy Stuff
```
:3,18d			delete lines 3 through 18
16,25m30		move lines 16 through 25 to after line 30
23,29co62		copy specified lines and place after line 62
:1,10w [file]   	write lines 1 through 10 to [file]
:40,$w >> [file]	copy lines 40 and on, append to [file]
:1,$s/[s1]/[s2]/g	(Yow!) global replacement of [s1] with [s2]
:%s/[s1]/[s2]/g         Easier global replacement of [s1] with [s2]
```

This is simply an edited version of [Joe R. Jah's introduction to vi](http://www.ccsf.edu/Pub/Fac/vi.html).
