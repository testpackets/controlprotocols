# controlprotocols
sample packets for testing Lighting control protocols

contents of simple sample packets for testing devices;

sending the test packets individually is easy enough using netcat.

examples;

Sending to a unicast address;
cat acn_valid_u2_2 | nc -4u -w 0  192.168.2.214 5568    

Sending to a multicast address;
cat acn_valid_u2_2 | nc -4u -w 0  239.254.0.2 5568    
