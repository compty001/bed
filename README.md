# bed
Binary editor written in Go

## Screenshot
![bed command screenshot](https://user-images.githubusercontent.com/375258/38499347-2f71306c-3c42-11e8-926e-1782b0bc73f3.png)

## Why?
Why not? Programming is so fun!

I learned so much while creating this editor; handling of file pointers, what the saying details should depend on abstractions mean, how to mock file system for tests in Go language, how to solve deadlock or race conditions between goroutines and many other things.

After all, creating by yourself is the best way to learn how it works.

#### Okay, but why?
I actually want a binary editor with Vim-like user interface, which runs in terminals, portable, fast and with window splitting feature.
I think I started coding for what I want before doing research on existing editors.

## Installation
```sh
 $ go get -u github.com/itchyny/bed/cmd/bed
```

## Features
- Basic editing: inserting, replacing, deleting bytes
- Support for large files
- Window splitting
- Partial writing
- Text searching

Note that this software is still in its early stage of development.
Please refer to https://github.com/itchyny/bed/issues/1 for roadmap.

## Bug Tracker
Report bug at [Issues・itchyny/bed - GitHub](https://github.com/itchyny/bed/issues).

## Author
itchyny (https://github.com/itchyny)

## License
This software is released under the MIT License, see LICENSE.
