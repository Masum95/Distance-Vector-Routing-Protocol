This is a C++ implemenation of [DVR Routing Protocol](https://en.wikipedia.org/wiki/Distance-vector_routing_protocol). Setup file contains necessary parts to setup virtual interface and topo.txt file includes topology info of the network.

To run the project
- Run setup file
- Run driver.py with topology filename being the first argument
    >./driver.py topo.txt
- Run Main.cpp file with IP address being the first argument and topology filename as the second one.
    > g++ Main.cpp -o Main -std=c++11 && ./Main 192.168.10.1 topo.txt
