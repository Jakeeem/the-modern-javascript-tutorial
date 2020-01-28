1. What is JavaScript?
JavaScript's job is to bring websites to life using programs called 'scripts' that can  be written right in a web page's HTML and run automatically as the page loads.

These scripts are executed as plain text in the browser via a JS VM:
	- V8 (Chrome, Opera, Chromium)
	- SpiderMonkey (FireFox)
	- JavaScriptCore (Safari)

JS is a 'safe' programming language; it is very high level and has no access to memory or CPU. Its capabilities depend on the environment it is being run in; different tools support different functions that expand what JS can do.

What can in-browser JS do?
Vanilla JS is capable of:
	- Adding new HTML to a page, change existing content, modify styles (CSS)
	- React to user actions, run on mouse clicks, pointer movements, key presses
	- Send requests over the network to remote servers, download/upload files (AJAX)
	- Get/set cookies, ask users questions, show messages
	- Remember the data on the client-side (local storage (cookies))

What can't in-browser JS do?
	- read/write files on the hdd, copy them or execute programs. 
	- No direct access to OS functions
	- Separate tabs don't know about each other
	- 

What makes JS unique?
	- Full HTML/CSS integration
	- Simple things done simply
	- Default major browser support

JS is the only browser tech that combines all 3 of these things.

Languages 'over' JS
	There are modern tools that allow developers to code in another language and auto-convert it into JS.

Summary
	JS was created as a browser-only language but is now used in many other environments as well.
	- has a unique position as the most widely-used browser language with full HTML/CSS integration.
	- There are many languages that get transpiled into JS that provide certain features not available in vanilla JS.