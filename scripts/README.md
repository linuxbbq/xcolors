Scripts
=======

A few of the scripts that we use will be included here for the use of making coversions from one term to another.

Note: on aterm and urxvt
    Many people like to use the "aterm*setting" or "URxvt*setting" syntax to separate xrdb themeing for different terminals.  While the format presented in the xcolor_code directory will often work without tweaking, should you wish to split it out in Xresources, you can generate a quick .bak file and then make changes fitting your needs with:
```
$ sed -i.bak 's/^\*/URxvt./' ~/foo_directory/foo_file
```
Which will put the file into a "URxvt.colorX: " format.  Assuming you wish to use aterm's customized format, you could use something along the lines of:
```
$ sed -i.bak 's/^\*/Aterm\*/' ~/foo_directory/foo_file
```
For similar results with aterm.

Specific Scripts and Usage
=========

There are patches included for suckless.org's st "simple terminal" that modify the existing config headers to incorporate the themes.  The README in the patch directory should cover the usage of the existing ones and how to create new patches, should you be so inclined.
