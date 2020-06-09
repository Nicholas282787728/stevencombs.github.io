---
layout: post
title: 'retroCombs: Commodore Plus/4 - Chapter 2, Using the Keyboard and the Screen'
date: '2020-06-04'
author: 'Steven B. Combs, Ph.D.'
permalink: plus4-3
email: 'steven.combs@gmail.com'
comments: 'yes'
category: retro
tags:
  - commodore
  - retro
  - plus4
  - unboxing
  - vic20
  - video
  - machinelanguage
  - 1980s
---

In the next Commodore Plus/4 retroCombs episode,

![Video Thumbnail](/images/posts/2020-06-04-retroCombs-thumbnail.jpg)

## Series Information

This episode is part of a series. You can check the entire series and additional resources at:

<https://www.stevencombs.com/plus4>

## User's Manual

As part of my Commodore Plus/4 YouTube series, I work through each chapter of the Plus/4 manual. I've taken the time to scan each chapter so you can read and follow along. Use the link below for this episode's chapter:

[Chapter 2 - Using the Keyboard and the Screen](https://www.stevencombs.com/plus4/users-manual/p4um-chapter-2.pdf)

1. [Front Matter](/plus4/users-manual/p4um-title-introduction.pdf)
2. [Chapter 1 - Unpacking and Setting Up](/plus4/users-manual/p4um-chapter-1.pdf)


## YouTube Video: _retroCombs: Commodore Plus/4, Chapter 2, Using the Keyboard and the Screen_

In the video below, I

<div style="position:relative;padding-top:56.25%;"><p><iframe src="link" frameborder="0" allowfullscreen="true" mozallowfullscreen="true" webkitallowfullscreen="true" style="position:absolute;top:0;left:0;width:100%;height:100%;"></iframe></p></div>

## Links Mentioned in this Episode:

Below are the links mentioned in the video.

1.

## Key to Keys

Because the Commodore Plus/4 keyboard is so different from modern keyboards, I had to devise and modernize key nomenclature to identify keystroke combinations as shown in the table below:

Key  | Description   | Key  | Description
:----|:--------------|:-----|:-----------
`⇪`  | Caps Lock     | `F1` | Function 1
`C=` | Commodore     | `F2` | Function 2
`⌃`  | Control       | `F3` | Function 3
`⎋`  | Escape        | `F4` | Function 4
`⌂`  | Home          | `F5` | Function 5
`⌫`  | Insert/Delete | `F6` | Function 6
`⏎`  | Return        | `F7` | Function 7
`RS` | Run/Stop      | `F8` | Help
`⇧`  | Shift         |      |

## Episode Contents

In this episode I describe and demonstrate each of the items below:

1. Upper-case -vs- lower-case mode: Default is upper-case graphics mode. Switch between them with `⇧` + `C=`.

    > **WARNING:** Don't use the ⇧ key when typing basic programs.

2. Run Stop `RS`: Stops a running program. `⇧` + `RS` loads and runs the first program program on a disk drive

    > **TIP:** If there is a program in memory, `⇧` + `RS` will also fail to load the first program on a disk drive, but will still execute the run command on the code in memory.

3. Cursor Keys: Covered in last episode, but Plus/4 includes all four keys!
4. Clear Home `⌂`: Home, clear, and clear window functions. Home moves the cursor to the top-left corner of the screen (home). `⇧` + `⌂` move to cursor to the home and clears the screen. 2 x `⌂` Clears the main and other windows (more on windowing in chapter 4)
5. Control `⌃`: Works with other keys that we will learn throughout this series. `⌃` + S will pausing printing (!) and listing of a program. Any key resumes the listing.
6. Commodore Key `C=`: Work with other keys. `C=` shift key for the left graphic characters on the keys, the bottom row of colors on the top number keys, and will slow down program scrolling.
7. Color Controls:

    * `⌃` + `9` = Reverse On
    * `⌃` + `0` = Reverse Off
    * `⌃` + `,` = Reverse On
    * `⌃` + `.` = Reverse Off


8. Escape Key `⎋`: Do not use like a shift (`⇧`) key. Tap `⎋` and then tap another key as shown below (I'm not covering them all but we will add in future chapters):

    * `⎋`, `A` = Auto Insert
    * `⎋`, `C` = Cancel Auto Insert
    * `⎋`, `D` = Delete Line
    * `⎋`, `I` = Insert Line
    * `⎋`, `J` = Move to Beginning of Line
    * `⎋`, `K` = Move to End of Line
    * `⎋`, `L` = Screen Scrolling On
    * `⎋`, `M` = Screen Scrolling Off
    * `⎋`, `O` = Cancel Insert, Quote (Chapter 4), Reverse, and Flash
    * `⎋`, `P` = Erase From Position to left
    * `⎋`, `Q` = Erase from Position to Right
    * `⎋`, `X` = Cancel an Escape functions


9. Special Keys: Per the manual, the keyboard contains special keys such as: `£`, `π`, `<`, `>`, `[`, `]`, `←`, and `↑`.
10. Function Keys: Type the `KEY` command to display the fuctions of the keys as shown below:

    ```
    KEY 1,"GRAPHIC" or built-in software
    KEY 2,"DLOAD"+ CHR$(34)
    KEY 3,"DIRECTORY"+ CHR$(13)
    KEY 4,"SCNCLR"+ CHR$(13)
    KEY 5, "DSAVE"+ CHR$(34)
    KEY 6,"RUN"+ CHR$(13)
    KEY 7, "LIST"+ CHR$(13)
    KEY 8, "HELP"+ CHR$(13)
    ```
    I demonstrate each function key.

    > **TIP:** CHR$(34) = `"` and CHR$(13) = `⏎`

    Function Keys `F4`, `F5`, `F6`, and `F7` require `⇧` and you can reprogram the keys as I demonstrate. A soft reset will retain the reprogramming and a hard reset will clear the reprogramming.

## Random Thoughts

I can't believe I learned so much about this computer just by reviewing the use of the keyboard.

## Join the Fun

Help make this series better! Post feedback, questions, and ideas. Let me know if you are following along. Let's make this a community project. For now, Leave your comments and thoughts below or in the comments [under the YouTube video](link).

🕹️ retroCombs OUT!
