openNew
=======

A simple BASH script that opens a new Finder Window to a specified directory on OSX

This nifty little script uses AppleScript to open a New Finder window, not reusing the current one, and then points it
to a directory specified when calling. If you copy it to your /bin/ you can call it from whenever. 

When is it useful to use this instead of open /path/?

-When you need multiple windows, as open /path/ && open /path/ only refocuses the window already opened.
-I was sure there was something else, but I've forgotten.
