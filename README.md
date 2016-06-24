# ipodctl
usage: ipodctl [-h] [-v] [-m MNT] {add,clear,list,remove} ...

Control iPod from command line

optional arguments:
  -h, --help            show this help message and exit
  -v, --version         show program's version number and exit
  -m MNT, --mnt MNT     mountpoint of the iPod (default: /mnt/ipod)

commands:
  {add,clear,list,remove}
    add                 add content to the iPod
    clear               remove all content from the iPod
    list                list content of the iPod
    remove              remove content from the iPod
