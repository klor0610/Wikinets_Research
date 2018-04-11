# TCP/IP Communication Over The Network (Protocol Stack)

1. The web server prepares the HTML page as data to be sent.
2. The HTTP header is then added to the front of the HTML data.
3. The HTTP protocol delivers the HTML web data to the Transport later from the Application Layer.
4. Then the IP is added to the front of the TCP (Transport protocol) information which assings the source and destination IP address also known as an IP Packet. 
5. From here, the Ethernet protocol adds information to both ends of the IP packet turning it into a data link frame.The frame is then sent to the nearest router. The router examines the IP packet and determines the best path for the packet and then sending it out to the Destination host. 
6. The data is then transported through the internet.
7. The source receives the data link frames and each protocol header is processed and then removed in the opposite order it was added. 
8. The web page can now be shown on the clients browser. 
