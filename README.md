alfred-cocoapods-workflow
================

Alfred workflow to search CocoaPods from Alfred. Opens the library URL and copies the dependency string to the clipboard so that you can paste it into the Podfile directly.

Usage
—————

+ to search for cocoapods
	
	```
	pod {query}
	```
	Clicking return opens the project page and copies to dependency string to clipboard

+ to copy dependency string
	
	```
	podc {query}
	```
	Clicking return only copies the dependency string to clipboard which can be pasted directly to the Podfile