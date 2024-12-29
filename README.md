# hdml
hard disk media list

## What is this thing?
Well, the name isn't quite accurate but I'll explain: you have (media) files in their dedicated folders - including subfolders - with an image file as preview (or cover art) right next to each one of them. You want to have a simple overview of what's in your folder(s), perhaps a grid of images that you can scroll through in your browser. This simple `Python` script will generate that `HTML` file for you. No dependencies and around 90 lines of code, with some `CSS` included to make the result responsive.

Example: preferred file/folder structure

    [Root Folder]
    ├── [Example Folder 1]
    │   ├── File1.jpg
    │   └── File1.mp4
    |
    ├── [Example Folder 2]
    │   ├── File2.jpg
    │   └── File2.mp4
    |
    ├── [Example Folder 3]
    │   ├── File3.jpg
    │   └── File3.mp4
    |
    └── [Example Folder 4]
        ├── File4.jpg
        ├── File4.mp4
        |
        └── [Example SubFolder 1]
            ├── File5.jpg
            └── File5.mp4

## How to use?
    python3 hdml.py

Note:
* Hover an image to see the filename
* You might want to use images with the same size, or at least the same ratio
* Items are ordered by the names of the images

## Screenshot
![hdml](https://github.com/user-attachments/assets/698eb2bb-f73a-4ca9-93d7-55806ddf42c9)

## This is too simple
That's for a good reason, less is more. For something more advanced, you might want to check out [Snap2HTML](https://github.com/rlv-dan/Snap2HTML) (Windows) or [LinuxDir2HTML](https://github.com/homeisfar/LinuxDir2HTML) (Linux).
