jQuery sBubble Plugin
=======

This version will trigger with click events instead of hover.

# Demo
[Click here for demo](http://www.ifadey.com/demos/17_jquery-sBubble/)

# Usage
[Check this page](http://www.ifadey.com/2013/01/sbubble-jquery-css3-tooltip-plugin) for usage and customization options.

To close the bubble, you must specify elements that will close it on beign clicked. For this, include an array of ids in an extra parameter:

$('yourelement').sBubble({
	...
	closeIds: ['some-button-id', 'another-button-id']
});
