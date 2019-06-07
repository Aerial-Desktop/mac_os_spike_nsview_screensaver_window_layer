# mac_os_spike_nsview_screensaver_window_layer
researching what happened for window management with sierra upgrading to high sierra

## Main Research path thus far:
Starting at the ScreenSaver Documentation, which inherits from NS_View.
<br/>https://developer.apple.com/documentation/screensaver

Moving on to learning about NS_View, looking for the window operating system layers so that background windows can be put on the desktop section of the operating system.
<br/>https://developer.apple.com/documentation/appkit/nsview

Helpful Keywords: "Managing the View’s Layer"

## Found Via google search with keyword Apple:

[IOS view and window architecture](https://developer.apple.com/library/archive/documentation/WindowsViews/Conceptual/ViewPG_iPhoneOS/WindowsandViews/WindowsandViews.html#//apple_ref/doc/uid/TP40009503-CH2-SW9)

[Human interface guidelines macOS views](https://developer.apple.com/design/human-interface-guidelines/macos/windows-and-views/outline-views/)

[OSX window architecture stackoverflow1](https://unix.stackexchange.com/questions/517/what-is-the-architecture-of-mac-os-xs-windowing-system#1016)

[old_ applications that can modify different parts of operating system](https://etutorials.org/Mac+OS/using+mac+os+x+v10.3+panther/Part+I+Mac+OS+X+Exploring+the+Core/Chapter+1.+Mac+OS+X+Foundations/Mac+OS+X+Architecture+and+Terminology/)

https://www.raywenderlich.com/3246-calayers/lessons/1


## Additional things to look up: 
Desktop Background view layer.


## Not helpful links:

Kernal might be helpful later the others are not helpful because they are app related and my fix is not needed for an app but rather an operating system program.

[Kernal Programming Guide](https://developer.apple.com/library/archive/documentation/Darwin/Conceptual/KernelProgramming/IOKit/IOKit.html#//apple_ref/doc/uid/TP30000905-CH213-SW1)

[The Role of View Controllers](https://developer.apple.com/library/archive/documentation/WindowsViews/Conceptual/ViewControllerCatalog/Introduction.html)

[The Role of View Controllers Ios](https://developer.apple.com/library/archive/featuredarticles/ViewControllerPGforiPhoneOS/index.html#//apple_ref/doc/uid/TP40007457)

[The Role of View Controllers Ios_legacy](https://developer.apple.com/library/archive/documentation/WindowsViews/Conceptual/ViewControllerPGforiOSLegacy/Introduction/Introduction.html)

[I do not have an app with infrustructure to make use of this thread](https://forums.developer.apple.com/thread/88468)
[same](https://forums.developer.apple.com/message/306407#306407)
