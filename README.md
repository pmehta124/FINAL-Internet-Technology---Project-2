# Load-Balacing-with-Domain-Name-Server

Implemented a practial exmaple of a DNS server that communicates with one client. To avoid the load of different DNS servers, I implements a load-balancing DNS Server to distribute the load based on the queries made. The client communicates with the load balancer (ls) and the load balancer then communicate with the correct DNS server (ts1 or ts2). Overall, I understood how to mitigate a bottleneck for a particular DNS server, allow for future scalability, and apply the architecture in a practial project! 
