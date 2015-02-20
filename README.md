These are [Keyboard Maestro](http://www.keyboardmaestro.com/main/) macros for making transcription with Express Scribe and MS Word much more productive.  
A cross-platform web version is being built [here](https://github.com/zevav/js-text-app); want to help?  :-).  There would also be value in porting it to Autohotkey, Autokey and similar .

#Installation

Download the .kmmacros file and file>import macros in Keyboard Maestro.

#Prerequisites

* MS Word for Mac
* Express Scribe

#Setup

##Express Scribe

* set the keyboard shortcut for "copy time" to ⌘⇧⌥/  
* set the time display format to h:mm:ss.t   

##Mac Keyboard Shortcuts

These are a few shortcuts in Mac OS (Yosemite) that conflict with our shortcuts; please uncheck them in System Preferences>Keyboard>Shortcuts.  There may be other conflicts, but if you "restore defaults" before unchecking these, you'll be all set:

* "Turn dock hiding on/off"
* "search with Google" 
* "make new sticky note" 

##MS Word

There are some conflicts here, but Keyboard Maestro seems to always "win" the conflict.  However, you'll lose some Word shortcuts that you usually rely upon.  In tools>customize keyboard, create these new shortcuts:

* ^a for editSelectAll
* ^b for bold
* ⌘⌥f for editFindDialog (and remove it from insertFootNoteNow)
* ^f for editFind
* ^d for formatFont


#Usage

This is a complex set of macros, enough that they basically comprise their own cobbled together application.

While in 
