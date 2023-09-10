# Command - `yp`

> Yank with `y` and paste with `p`

This is the first time we're learning two commands at once, and there's a reason for that. You can't make use of one without knowing the other. The `y` command is for copying text (or yanking) and the `p` command is for pasting. You use it in normal mode.

It should be easy enough to remember. `y` stands for **y**ank and `p` stands for **p**aste.

## Exercise 01  - Duplicate a Line

The goal of the first exercise is to learn the most common use of these two together: duplicating a line.

1. Move the cursor to the first line.
2. Hit `yyp`.
3. Move to the second line.
4. Hit `yy4p`.

<!-- Text for exercise starts

Duplicate this line.

Duplicate THIS line 4 times.

Text for exercise ends -->

### Tips

- Remember how `dd` deleted the same line? `yy` is copying the same line, and the `p` is for pasting it.
- Try using a different number instead of 4.
- Look down at your fingers briefly to identify which fingers you're using to hit the `y` and the `p` keys. For the `y`, I use my right pointer finger and for the `p` I use my right pinky finger.

## Exercise 02 - Delete and Paste

The goal of this exercise is to demonstrate how you can paste after deleting something.

1. Move the cursor to the first line.
2. Hit `dd`.
3. Hit `p`.
4. Move the cursor to the second paragraph and stop at "h.
5. Hit `da"` to copy the word and quotes.
6. Move the cursor to the : on the last line.
7. Hit `p`.

<!-- Text for exercise starts

Move this line.
So this one is on top.

Delete the word "hello" with quotes.
Paste it after the:

Text for exercise ends -->

### Tips

- There are times where it may be easier to copy with `ctrl/cmd c` vs. `y` and same goes with `ctrl/cmd p` vs. `p`. Use the one that makes the most sense for you.

## Exercise 03  - Change and Paste

The goal of the third exercise is to show that you can paste after using the `c` command.

1. Move the cursor to "blue".
2. Hit `cw` and type in your favorite color.
3. Move the cursor to the second : and hit `p`.

<!-- Text for exercise starts

My favorite color is: blue
Your favorite color is:

Text for exercise ends -->

### Tips

- As you can say, using the `d` or the `c` command is more like "cutting" rather than deleting entirely. Pretty convenient, huh?

## Exercise 04 - Yank Til

The goal of the fourth exercise is to show how you can combine `y` with a motion.

We haven't seen this yet, but you can use `t` like *until* something.

1. Move the cursor to the "f" in "favorite" on the first line.
2. Hit `yt:` (yank until the ":").
3. Move the cursor to the second line, hit `a`, type a space, hit `esc`.
4. Hit `p`, hit `a`, then type : followed by a space and a color.
5. Move the cursor to the "Y" at the beginning, hit `ytr`.
6. Move the cursor to the start of the last line, hit `P` (yes, capital "p").
7. Hit `a`, type a space and then hit `esc`.

<!-- Text for exercise starts

My favorite color is: red
Your
are awesome!

Text for exercise ends -->

### Tips

- Try using the `t` with `c` or `d`.
- The `P` is also new. Same functionality as the `p` command, but it pastes in front of the cursor instead of behind. Yes, this lesson is a lot, but I wanted to make sure I introduce you to these!

## Exercise 05 - Reviewing

The goal of the fifth exercise is to reflect on what you've learned so far.

The commands are mixed up. Use you skills to fix them!

1. Move to the first line.
2. Use the `ci`` and write the correct command.
3. Use the `p` to paste what you *changed* from the first command into the right place.
4. Go through the remaining commands utilizing the new `y` and `p` commands to help you along the way.

<!-- Text for exercise starts

- `j` move left toward the *house*
- `h` move down (*jumping* off a ledge)
- `l` move up (*kicking* a soccer ball upward)
- `k` move right (*left*to right, like English)
- `A` let me *insert* text
- `i` let me *Append* text
- `x` let me *Initially* insert text
- `I` let me *ex-out* a character
- `w` let me *replace* a character
- `O` insert a line below the *original* line
- `o` insert a line *Over* the current line
- `r` move word by word
- `a` move *end* of word by end of word
- `d` move *backwards* word by word
- `e` let me insert text *after* the cursor
- `c` lets me *delete* text
- `d` lets me *change* text
- `y` lets me *yank* text and `p` lets me *paste* text

Text for exercise ends -->

## Command Complete 🎉

Congrats! You did it ✅.

You have mastered the `y` and `p` command (counting as one command since they're used together).

18/22 commands done.

### Reflecting

Reflecting on what you've learned so far, answer these questions out loud and pretend you're explaining them to someone who is new to Vim.

- What is the `y` command used for? And the `p` command?
- In which mode do you use it?
- What was your favorite thing you learned in this lesson?