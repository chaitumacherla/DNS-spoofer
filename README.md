In this project, we will try to modify the packets that are coming from the victim and going to victim

This can be done by trapping all the packets in a queue,modifying them by python code and forwarding the packets.
To create type "iptables -I FORWARD"-j NFQUEUE --queue-num 0" in terminal. 