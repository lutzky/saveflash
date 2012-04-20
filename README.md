saveflash
=========

Script to save currently-playing flash files.

To change the output directory, run like so:

    DESTDIR=/some/directory saveflash

It may be helpful to run using `sudo`, as the process playing flash files may
not belong to you. In this case, if you use `sudo`, permissions will be
automatically adjusted.

This script works around the fact that flash deletes the open `.flv` files
while they're still open, so they automatically get freed when the process
dies.
