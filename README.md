# SimpleLoadBalancer_P4_bmv2
*A simple 4host-1bmv2switch-4server LoadBallancer using P4*

You need P4 VM to create topologies and compile P4 with one bmv2 switch the experiment can be done by pinging from a host to a server.

- download VirtualBox https://www.virtualbox.org/wiki/Downloads
- download P4 ova file https://tinyurl.com/hy436P4vm

# Brief explanation

Red hosts can only communicate with red server and blue ones only with blue servers randomly via 1 bmv2 switch. Hosts can only see fake service IP and fake service MAC, the servers are invisible from the a host pov. Servers can see host src IP so they can reply. The switch P4 programme handles the comunication bewtween who can speak with who and what can be seen from each edge.

