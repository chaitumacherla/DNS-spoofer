In this project, we will try to modify the packets that are coming from the victim and going to victim in different layers

This can be done by trapping all the packets in a queue,modifying them by python code and forwarding the packets.
To create a queue type "iptables -I FORWARD"-j NFQUEUE --queue-num 0" in terminal. 

Modifying the packets in DNS layer : Here we are dns spoofing the target and redirecting them to the another ip address where we desired to redirect them that means server which contains any backdoor, trojan.

Modifying the packets in HTTP layer : Here we are intercepting the downloads and modify the downloads with a new file of malware or trojan or backdoor. Therefore, creating a new response.

Code injector : Here we are trying to modify the HTML code and replacing it with javascript.

To perform all this, first we have to be man-in-the-middle. There are different methods to become man-in-the-middle. You can use any method to become man-in-the-middle.