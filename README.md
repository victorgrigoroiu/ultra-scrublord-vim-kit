# Ultra scrub lord vim kit

`:h help`,`:h <topic>`

## Overview

## Basics

### Movement

| key | description|
|-|-|
|`h`|move left|
|`j`|move down|
|`k`|move up|
|`l`|move right|
|`w`/`W`|move wordwise (ignore punctuation)|
|`e`/`E`| move to the end of word|
|`b`/`B`| move back|
|`f char`|go to the nearest `char`, use `;` for next|
|`$`| move to end of line|
|`0`| move to the start of the line|
|`gg`|go to the start of the buffer|
|`G`|go to buffer end|

other movements are `Ctrl-e`, `Ctrl-y`, `Ctrl-d` ...

### Modes
|key|description|
|-|-|
|`v`|visual mode|
|`ESC`| go to normal mode|
|`:`| enter ex command|

### The ex command line

### Buffers

|ex command or key combination| description|
|-|-|
|`:e /path/to/file`|it opens a specified file or creates a new one if it does not exist after `w`|
|`:bd`|delete/close current buffer|
|`Ctrl-6`| navigate(toggle between open buffers)|
|`<BufferNumber>Ctrl-6`|got to the numbered buffer|

some ex commands for buffer navigation `:bnext`, `:bprevious`

## Actions

Actions can be combined with movement

|key|descritption|
|-|-|
|`x`|delete under the cursor|
|`r char`|replace under the cursor|
|`d`|delete|
|`dd`|delete/cut line|
|`y`|yank/copy|
|`yy`| yank/copy line|
|`p`|put text from register after the cursor|
|`P`|put text from register after the cursor|
|`u`|undo|
|`U`|undo line|
|`Ctrl-r`|redo|


## Search and RE

### Basic search

use `n` or `N` for next/previous

|search|description|
|-|-|
|`/search_string`|basic search forward|
|`/<search_string>`| search for exact word forward|
|`?search_string`|basic search backwards|
|`?<search_string>`| search for exact word backwards|

### Search and replace using RE

|command|description|
|-|-|
|`s/old/new/`|search first ocurence of `old` and change it with `new` on a line|
|`s/old/new/g`|same as above but use the global `g` option|
|`%s/old/new/g`|search and replace in the whole document|
|`%s/old/new/gc`|same as above but ask for confirmation|

## .vimrc

generate a basic vimrc [here](http://vim-bootstrap.com/)

## Plugins


