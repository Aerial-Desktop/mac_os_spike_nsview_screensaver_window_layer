# mac_os_spike_nsview_screensaver_window_layer
researching what happened for window management with sierra upgrading to high sierra

## Main Research path thus far:
Starting at the ScreenSaver Documentation, which inherits from NS_View.
<br/>https://developer.apple.com/documentation/screensaver

Moving on to learning about NS_View, looking for the window operating system layers so that background windows can be put on the desktop section of the operating system.
<br/>https://developer.apple.com/documentation/appkit/nsview

Helpful Keywords: "Managing the View’s Layer"

## Additional things to look up: 
Desktop Background view layer.


## Not helpful links:

Kernal might be helpful later the others are not helpful because they are app related and my fix is not needed for an app but rather an operating system program.

[Kernal Programming Guide](https://developer.apple.com/library/archive/documentation/Darwin/Conceptual/KernelProgramming/IOKit/IOKit.html#//apple_ref/doc/uid/TP30000905-CH213-SW1)

[The Role of View Controllers](https://developer.apple.com/library/archive/documentation/WindowsViews/Conceptual/ViewControllerCatalog/Introduction.html)

[The Role of View Controllers Ios](https://developer.apple.com/library/archive/featuredarticles/ViewControllerPGforiPhoneOS/index.html#//apple_ref/doc/uid/TP40007457)

[The Role of View Controllers Ios_legacy](https://developer.apple.com/library/archive/documentation/WindowsViews/Conceptual/ViewControllerPGforiOSLegacy/Introduction/Introduction.html)
