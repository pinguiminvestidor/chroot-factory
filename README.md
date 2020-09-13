# chroot-factory

Some stuff to make the creation of a Linux chroot sandbox "by hand" less painful and repetitive when you can't / don't want to use Docker.

Created mostly as an exercise, and mostly by following instructions found in this excellent guide: 

https://www.cyberciti.biz/faq/unix-linux-chroot-command-examples-usage-syntax/

This by no means creates absolutely secure chroot environments or sandboxes completely an environment or application - this is only a study! You've been warned...

## Todo list

 - `buildchroot`: "bootstrap" script to launch your chroot in one command. (DONE)
 - `addtochroot`: "installer" of existing applications in chroot environment
