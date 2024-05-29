vcanifs
=======

A bash script to take virtual can interfaces up or down. 

usage: vcanifs up|down {\<vcan interface name\>}

Example 1:
----------
```vcanifs up vcan0 vcan1 vcan2```

Brings the virtual can interfaces vcan0, vcan1 and vcan2 online. If either of them do no exist, it is created first.

Example 2:
----------
```vcanifs down vcan1```

Brings the virtual can interface vcan1 offline.

