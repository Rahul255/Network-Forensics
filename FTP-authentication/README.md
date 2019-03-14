# FTP authentication challenge
For this challenge I used wireshark to analyse the FTP package.
First Download the ch1.pcap file. next open wireshark. No wireshark installed? No problem I will show you how to install wireshark via the terminal.
1- Open the Terminal.
2- Type sudo apt install wireshark-qt
3- You have now installed wireshark
### What is wireshark?
Wireshark is a network packet analyzer. A network packet analyzer will try to capture network packets and tries to display that packet data as detailed as possible.
### Features
Main Wireshark Features are:
1- Available for UNIX and Windows.
2- Capture live packet data from a network interface.
3- Open files containing packet data captured with tcpdump/WinDump, Wireshark, and a number of other packet capture programs.
4- Import packets from text files containing hex dumps of packet data.
5- Display packets with very detailed protocol information.
6- Save packet data captured.
7- Export some or all packets in a number of capture file formats.
8- Filter packets on many criteria.
9- Search for packets on many criteria.

Ok, then click on File and open the ch1.pcap file.There you should see many packages. we can ignore most of them and we need to apply a filter to ignore this unuselss packages. This challenge is called FTP authenticaton so, We want only FTP packages right? Write in the filter selection FTP and apply it. now we able to see only FTP packages. There are seven selection no, time, source, destination, protocol, length, info. went to info selection then get the flag.
Password is: cdts3500
