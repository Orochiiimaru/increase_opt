## Increase /opt

1. df -h /opt
2. lvdisplay
3. lvextend -L 5G /dev/rootvg/opt
4. resize2fs /dev/rootvg/opt

Werkt blijkbaar niet al te goed?
