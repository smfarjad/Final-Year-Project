# Final-Year-Project


## Important Commands

### Command for creating topology
sudo mn --topo single,7 --mac --controller=remote,ip=127.0.0.1 --switch ovs,protocols=OpenFlow13

### Command for initiating controller
ryu run farjad_sdn.py

### Command for opening terminals
xterm h1 h2 h3 h4 h5 h6 h7

### Command for initiating simple http server
python -m SimpleHTTPServer 80

### Command for requesting from client to server
curl 10.0.0.100   //10.0.0.100 is virtual server!

### Command for checking connectivity without explicitly opening terminals using xterm
h1 ping -c 5 h4
