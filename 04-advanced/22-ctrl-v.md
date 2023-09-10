# Command - `ctrl v`

> Enter multi-cursor mode with `ctrl v`

The `ctrl v` command lets you enter multi-cursor mode, which is handy when you need to select multiple lines and add cursors to modify text.

A good way to remember it is "*controlling* the *view* mode" where you can control (e.g. enter text) the view mode (the place where you want the text to go).

## Exercise 01  - The Basics of Multiple Cursors

The goal of the first exercise is to learn the basics of the command `ctrl v`.

1. Start with the cursor on the "a" in "apples".
2. Hit `ctrl v`.
3. Move down with `j` until all four lines are selected.
4. Hit `I`.
5. Type -
6. Hit `esc`.

<!-- Text for exercise starts

Shopping List
apples
bananas
carrots
celery

Text for exercise ends -->

### Tips

- How would you do this faster, specifically Step 3?
- Look down at your fingers briefly to identify which fingers you're using to hit the `ctrl v` key. For me, I use my left pinky finger to hit `ctrl` and my left index finger to hit `v` to make `ctrl v`.

## Exercise 02 - Crossing off Todos

The goal of the second exercise is to show another scenario where the `ctrl v` command comes in handy.

Cross off all the todos.

1. Start with the cursor inside the first todo box (where the [x] is).
2. Hit `ctrl v`.
3. Hit `3j`.
4. Hit `rx`.

<!-- Text for exercise starts

Todo List
- [ ] Download VSCode
- [ ] Download Vim extension
- [ ] Learn Vim
- [ ] Excel in the world

Text for exercise ends -->

### Tips

- See how beautiful Vim is when you combine it like so?

## Exercise 03  - Missing Semicolons

The goal of the fourth exercise is to continue practicing the `ctrl v` command.

Oh no! Remember when the linter broke? Well, that happened again. We're missing let statements at the beginning of these lines. Can you fix it?

1. Start on the first line.
2. Hit `ctrl v`.
3. Select the other two lines.
4. Hit `I`.
5. Type let
6. Hit `esc`.

<!-- Text for exercise starts -->

```javascript
x = ;
done = "done"
two = 2
```

<!-- Text for exercise ends -->

### Tips

- This comes in handy when you want to make adjustments to the same positions in multiple lines.

## Exercise 04 - Numbered Lists

The goal of the fourth exercise is to practice another scenario where you can apply the `ctrl v` command.

This is supposed to be a numbered list. Can you make it so?

1. Start with the cursor at the beginning of the first line.
2. Use what you've learned so far to add "1." to the beginning of each line.

<!-- Text for exercise starts

Do this first
Then this.
After that, do this.
Then this.

Text for exercise ends -->

### Tips

- Did you know in markdown your lists can all be 1s and it will still render as expected? Check out the preview if you don't believe me!

## Exercise 05 - Final Review

The goal of the fifth exercise is to review everything we've learned so far.

Oh no! everything has been lost. Can you write down all the commands we've learned so far using this pattern?

- `COMMAND` short description

The first one was recovered. But we're missing the other 21.

1. Add the remaining 21.

<!-- Text for exercise starts

- `h` move left toward the *house*v

Text for exercise ends -->

## Command Complete 🎉

Congrats! You did it ✅.

You have mastered the `ctrl v` command.

22/22 commands done.

### Reflecting

Reflecting on what you've learned so far, answer these questions out loud and pretend you're explaining them to someone who is new to Vim.

- What is the `ctrl v` command used for?
- In which mode do you use it?
- What are some use cases for it?

## The End

Congrats on learning all 22 commands! 🎉

I hope you enjoyed learning this way.

If you enjoyed this and would like more exercises like this, let me know! We've only scratched the surface of Vim. There is so much more to learn! Feel free to get in touch over Twitter [@jsjoeio](https://twitter.com/messages/compose?recipient_id=1567529924&text=Hi!%20I%20wanted%20to%20get%20in%20touch%20about%20your%20Vim%20for%20VSCode%20course.) or by email [joe@vimforvscode.com](mailto:joe@vimforvscode.com).

Thanks so much!

Happy Vim'ing!
-Joe