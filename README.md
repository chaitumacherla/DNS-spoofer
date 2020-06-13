In this project, we will try to modify the packets that are coming from the victim and going to victim

This can be done by trapping all the packets in a queue,modifying them by python code and forwarding the packets.
To create type "iptables -I FORWARD"-j NFQUEUE --queue-num 0" in terminal. 

To perform dns spoofing, first we have to be man-in-the-middle. There are different methods to become man-in-the-middle. You can use any method to become man-in-the-middle.