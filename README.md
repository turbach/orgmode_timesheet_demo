# How to track your time in Emacs orgmode with 3 keystrokes

Overview: Make a list of your projects in a text file. Then let emacs
  orgmode generate timestamps to track your time and generate a simple
  report.

Notation:
   C-c means press Control and the lowercase c keys at the same
   time, C-x means Control and x, etc..
   
# How to 

1. One time setup

  - save the timesheet.org template file on linux (or type it up)
  - open the file in emacs (you may need to press TAB TAB to expand the view)
  - edit the Project labels as you like
  - add more project lines if you like, each begins with a "*" and whatever label you want

2. Daily use: clock in on a project, work on it, clock out
   a. clock IN to set the [start] timestamp: put the cursor on the Project press C-c C-x C-i 
   b. do whatever work you are doing.
   c. clock OUT to set the [stop] timestamp. anywhere in the document press C-c C-x C-o

3. Report: move the cursor to the line "#+BEGIN:# and press C-c C-c. You can do this anytime

Tip: Orgmode documents are like tree-like and the view can be expanded
  or collapsed.  Press TAB once or twice to toggle the view. See
  online docs and reference card for other commands.

Tip: the time stamps are just text, if you goof up the clock edit the timestamp

General orgmode info:

- online docs: https://orgmode.org/guide/
- reference card: https://orgmode.org/orgcard.pdf


