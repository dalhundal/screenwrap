Screenwrap
===

A simple wrapper for *[screen][1]*, providing quick and convenient access to named screens.


Installation
---

Just copy *scr* to somewhere in your path.


Usage
---

Lists all screens (if any) that have been created:
    
    scr

Attaches to a screen named 'myScreen', if it doesn't exist, creates it first:

    scr myScreen


Example output
---

    > scr
    - There are no screens running
    
    
    > scr myScreen
    - Found no screen named (myScreen), starting a new screen...
    
    
    > scr
    Found 1 screens
    ---------------
    myScreen
    
    
    > scr myScreen
    - Found a screen named (myScreen), reattaching...


[1]: http://www.gnu.org/software/screen/manual/screen.html