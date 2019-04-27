# Ultra scrub lord vim kit

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


## Actions

Actions cand be combined with movement

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

use `N` or `n` for next/previous

|search|description|
|-|-|
|`/search_string`|basic search forward|
|`/<search_string>`| search for exact word forward|
|`?search_string`|basic search backwards|
|`?<search_string>`| search for exact word backwards|

## .vimrc

generate a basic vimrc [here](http://vim-bootstrap.com/)

## Plugins


