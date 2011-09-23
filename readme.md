# About
This is a fork of pyparadigm's [SublimeBrackets](https://github.com/pyparadigm/SublimeBrackets "Go to SublimeBrackets.")
I forked this to fix some issues I had and to add some features I wanted.  I also wanted to improve the efficiency of the matching.
I also merged in pyparadigm's SublimeTagmatcher as well.  This cuts down on the parallel searching that is now streamlined in one search.

# New and Noteworthy
The 9/22/11 commit will require you to re-configure your user settings.  I apologize for this, but it was unavoidable. I hope to not have to change existing setting names or types again.  I think I am finally settling down on major code changes to architecture.
- Pick your highlight style: solid, outline, or underline

# Installation 
* Latest version: [Click here to download.](https://github.com/facelessuser/BracketHighlighter/zipball/master "Click here to download lastest version.")
- Must be running **Sublime Text 2 Build 2108** or higher.
- Drop the folder into your Sublime Text 2 packages directory.
- You may need to restart Sublime Text 2

# Features
- Customizable highlighting of brackets (),[],<>,{}
- Customizable highlighting of Tags (supports unary tags and supports self closing /> (HTML5 coming))
- Customizable highlighting of quotes
- Selectively disable or enable specific matching of tags, brackets, or quotes
- Selectively whitelist or blacklist matching of specific tags, brackets, or quotes based on language
- When using on demand shortcut, show line count and char count between match in the status bar
- Works with multi-select.

# Options
- Open BracketHighlighter.sublime-settings and configure your preferences (can be accessed from menu).
- Change the scope, highlight style, icon for bracket types, which brackets to match, set search thresholds, etc.
- Save the file and your options should take effect immediately.

# Screenshot
![Options Screenshot](https://github.com/facelessuser/BracketHighlighter/raw/master/example.png)
