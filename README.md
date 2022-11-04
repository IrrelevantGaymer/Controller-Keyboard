# How it Works

There is a 3x3 grid of Keys, each with a symbol on it, called a Stage.  Hold the Left and/or Right Triggers to change the Stage.
There are up to 4 Stages within a Tab.  Press the Left or Right Bumpers to change the Tab.

Use the Left Stick to select one the Keys in the Current Stage (center Left Stick is center on the Stage, up right is up right, etc.).
Press A to Input the Selected Key at the Given Position.  Press X to Backspace (deleting the previous input or a selection).
Press Y to Input a Space.  Press Select to Input an Indentation.  Press Start to Input a New Line.
Press Down on the Left Stick to Toggle Shift (Capitalizing the next inputted Symbol). Press Down Twice to Toggle Caps Lock.

Use the Dpad to move the Caret (Current Typing Position).  While Shift is toggled, moving the Dpad will create a Selection.

# Keyboards

### Tabs: ABC
Stages:
- `CTHSEROAN`
- `DWLIMFGUB`
- `JKXPYVQZ `
- `'!-,.?*;+` - Capital: `"\_@()/:=`

### Tabs: 123
- `123456789`
- `+.*$0,-=/`
- `#%^&|`\-~`
- `[]<()>{};`

# Other Concepts and Ideas

If implemented into an app or game, the B button would be used to exit the text box or 
Start would instead Enter the text instead of inputting a New Line.

For Other Features, keep in mind the ideal max number of Tabs is 3 since you can always access any Tab via 1 button press.

Commands such as Copy, Paste, etc. can be implemented via another Tab or by Pressing down on the Right Stick to Toggle Command.
Command in conjuction with letters could act as commands: Command + C = Copy, Command + D = Duplicate, etc.

Emojis can be added via another Tab or Tabs.  However the number of Emojis would prove difficult to store in this keyboard.
Maybe use the standard keyboard for this since the speed of emoji typing isn't super important, or try to cram in as many emojis as possible.
Using Shift, Caps Lock, and Command to artificially increase the keyboard space, there are a total number of 288 Keys for a single Tab.
This can again be increased further by having a Command Lock, bringing the total to 576.  
There's also the idea of making the Stages act like Tabs for emojis, where there's quite a lot of Stages, thus expanding our Keyspace
to an arbitralily large number, but this could be cumbersome to use.  Current implementation of the app can't support Emojis since
Emojis are stored with UTF32 while the Text Box can only store UTF16.
