Man page generation
===================
The man page is generated from the docs/pynag-command.rst file

Generate new man page
---------------------
```
./setup.py build_man
gzip -cf < pynag.1 > pynag.1.gz
```
