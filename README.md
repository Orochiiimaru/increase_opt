## Increase /opt

1. df -h /opt
2. lvdisplay
3. lvextend -L 5G /dev/rootvg/opt
4. resize2fs /dev/rootvg/opt

#PUsh dit naar onze test branch.
