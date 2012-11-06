iPadMiniDetection
=================

Upon hearing of Apple's decision to remove any web-visible differentiators between the iPad mini and (much larger) iPad 2, I created this simple script for detecting if user is using an iPad mini.

There are only 2 lines of JavaScript required:

	var isIpadMini = confirm("Are you using an iPad mini?")
	if (isIpadMini) document.body.className += " ipad-mini"
	
This method is bullet-proof and will work in nearly every situation (Except if your user is very drunk and forgets that they are using an iPad mini. In this case, they have more pressing issues to deal with than abnormally-small text.)