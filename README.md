hnx
===

The hnx script for changing keyboards.

It is a very simple script, switches between the us qwerty keyboard and the us dvorak left-handed keyboard.
If you happen to use both the querty and dvorak one a computer it is useful. It also uses keys that stay the
same over the two keyboard layouts, so the user doesn't have to know the other layout, or even know which
layout is in use at the time.

PLANS:
Create a man(ual) page for the script.
Turn the script into a full package (.deb)

===
New idea to upgrade the script so that other people can use it. Create a file
a list of keyboard formats. The system will then cycle through them every time
the hnx command is entered. Each format gives the command to change the format
(I'll probably use the same command as before, setxkbmap, and ask for flags),
a name for the format to echo to the user in querys and after a switch. There
may even be two names, a short name (for input) and a long name (for output).
Entering hnx NAME will swap directly to that format.

The main things I need are generic functions for the query and swap commands.
Then a way to connect those to the input file. I suppose if I was feeling
really ambisus I would also include some formating aids for the config file.
Actually why not have two format files, a processed and unprocessed one.
