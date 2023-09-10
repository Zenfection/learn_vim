# Vim for VSCode

Hello! And thank you for purchasing Vim for VSCode.

## What's Included

Each command has 5 exercises associated with it. There are 22 commands in total and they are divided into 4 sections. Here is a list for your convenience:

1. Navigation
   - `h` - move left
   - `j` - move down
   - `k` - move up
   - `l` - move right
2. Editing
   - `i` - insert text
   - `a` - insert text after cursor
   - `I` - insert text at beginning of line
   - `A` - append text at the end of line
   - `x` - ex-out text
   - `r` - replace a character
   - `o` - insert line below current line
   - `O` - insert a line above current line
3.  Moving
   - `w` - move by word
   - `e` - move by end of word
   - `b` - move backwards by word
4.  Advanced
   - `d` - delete text
   - `c` - change text
   - `y` and `p` - yank text and paste text
   - `v` - select tet in visual mode
   - `f` - find text
   - `F` - find text backwards
   - `ctrl v` - enter multi-cursor mode

## How to Use

1. Open up this folder inside VSCode.
2. Install the recommended extensions.
3. Go through exercises starting with 01-navigation.
4. Have fun!

### Prerequisites

I'm going to assume you have VSCode installed. If not, go install it.

I am also assuming you know the basics of touch-typing. If you don't, that's fine, but you may have some difficulties!

**Install Vim Extension**

You'll need the [Vim extension](https://marketplace.visualstudio.com/items?itemName=vscodevim.vim). VSCode should ask you to install the recommended extensions when you open this up, but if not, make sure you have it installed before you start.

**Enable Key-Repeating**

For Mac, enable key-repeating by executing the following in your Terminal:

```shell
# For VS Code
defaults write com.microsoft.VSCode ApplePressAndHoldEnabled -bool false

 # For VSCode Insider
defaults write com.microsoft.VSCodeInsiders ApplePressAndHoldEnabled -bool false

# For VS Codium
defaults write com.visualstudio.code.oss ApplePressAndHoldEnabled -bool false

# If necessary, reset global default
defaults delete -g ApplePressAndHoldEnabled
```

Then restart VSCode.

If it still doesn't work, try restarting your computer.

For Windows, they say it *should* work. But if not, read the Window specific guide [here](https://github.com/VSCodeVim/Vim#windows).

**Suggestion: Remap Caps Lock to Esc**

When working with Vim, you'll find yourself wishing the `esc` key were closer. Luckily you can make it so by remapping the caps lock key -> esc.

To do this, follow these steps:
1. Open System Preferences.
2. Navigate to Keyboard.
3. Click "Modifier Keys".
4. Change Caps Lock Key to Escape.

For Windows, you may want to check out an open source project called `sharpkeys` [here](https://github.com/randyrants/sharpkeys)(thank you to @Arpan____ for the suggestion!). Note: please use at your own risk. I do not have Windows and have not tested.

## How to Be Successful

If you want to be successful with this course, I suggest committing 10-15mins a day and slowly making the transition to using Vim inside VSCode in your daily editor. It will be painful at first, but with practice and commitment, it will work out :)    

## Feedback/Questions

If you have feedback or questions, feel free to get in touch over Twitter [@jsjoeio](https://twitter.com/messages/compose?recipient_id=1567529924&text=Hi!%20I%20wanted%20to%20get%20in%20touch%20about%20your%20Vim%20for%20VSCode%20course.) or by email [joe@vimforvscode.com](mailto:joe@vimforvscode.com).