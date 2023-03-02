# freeMem.sh
a small or shall I say tiny script to clean up memory

[freeMem.sh](https://github.com/BeanGreen247/ArchLinux-KDE-Plasma-setup-script/blob/main/freeMem.sh)

```bash
# cleans cached Memory, prevent system slowdown/lockup
sync && echo 3 > /proc/sys/vm/drop_caches
```
