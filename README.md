# get-from-aur
A simple script to update or install stuff from AUR
You're supposed to have some directory with subdirectories which contains sources cloned from AUR with *git clone*
Or you might write *get-from-aur <your-link-here>* and it will clone it to appropriate directory, and then install this.
If you pass dir-name instead of URL, it will make *git pull* and then reinstall this.

I made it for myself, just for fun. If you like it and have ideas how to improve -- I will be thankful.
