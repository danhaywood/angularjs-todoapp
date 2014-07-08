AngularJS-todoapp
=================

Pure client-side todoapp, implemented in AngularJS.  There is no REST interaction here, the objects are stored in memory.

Integrates:
- angularjs
- bootstrap
- angular-ui-router
- angular-xeditable
- angular-strap


To run
------
Will run directly in Firefox; just open up index.html


Chrome does not support XMLHttpRequest calls to file://, so the app must be hosted.

If you have Python installed, use:

    python -m SimpleHTTPServer 8080

Then navigate to http://localhost:8080
    
    chrome --disable-web-security

or 

chrome --allow-file-access-from-files --allow-file-access --allow-cross-origin-auth-prompt
