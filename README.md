# jquery-texinfo
texinfo &amp; info documentation files for jQuery API

To recreate the info file from the texinfo file:

 1. makinfo jquery.texinfo
 2. sudo cp jquery.info /usr/share/info/
 3. cd /usr/share/info/
 4. sudo install-info jquery.info dir

TODO: split items into different chapters for events, selectors, effects, AJAX, etc.
