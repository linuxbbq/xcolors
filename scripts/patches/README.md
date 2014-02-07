st-term patches
======

These are designed to be directly applicable patches for suckless.org's st (simple terminal).
They are based off of the difference between the stock config.def.h and one customized using the themes from xcolor_code.
You can create a patch by using 
```
diff -u config.def.h yourconfig.h > foo_theme.diff
```

should you wish to contribute.
To apply a patch, cd to your source directory and use 
```
patch < /path/to/whatever_theme
```
to create a newly patched config.h from
your existing config.def.h

