# jquery-texinfo
texinfo &amp; info documentation files for jQuery API

To recreate the info file from the texinfo file:

makinfo jquery.texinfo
sudo cp jquery.info /usr/share/info/
cd /usr/share/info/
sudo install-info jquery.info dir
