# NetPackets
show network packets  
[root@zyq NetPackets]# ./netpackets.py -h  
usage: netpackets.py [-h] [-u] [-t] [-I] [-i]  

Print network packets header format  

optional arguments:  
  -h, --help  show this help message and exit  
  -u          Print UDP header format  
  -t          Print TCP header format  
  -I          Print IPV4 header format  
  -i          Print ICMP header format  


[root@zyq NetPackets]# ./netpackets.py -i  
https://datatracker.ietf.org/doc/html/rfc792  
ICMP Header Format:  

	0                   1                   2                   3  
    0 1 2 3 4 5 6 7 8 9 0 1 2 3 4 5 6 7 8 9 0 1 2 3 4 5 6 7 8 9 0 1  
   +-+-+-+-+-+-+-+-+-+-+-+-+-+-+-+-+-+-+-+-+-+-+-+-+-+-+-+-+-+-+-+-+  
   |     Type      |     Code      |          Checksum             |  
   +-+-+-+-+-+-+-+-+-+-+-+-+-+-+-+-+-+-+-+-+-+-+-+-+-+-+-+-+-+-+-+-+  
   |                             unused                            |  
   +-+-+-+-+-+-+-+-+-+-+-+-+-+-+-+-+-+-+-+-+-+-+-+-+-+-+-+-+-+-+-+-+  
   |      Internet Header + 64 bits of Original Data Datagram      |  
   +-+-+-+-+-+-+-+-+-+-+-+-+-+-+-+-+-+-+-+-+-+-+-+-+-+-+-+-+-+-+-+-+  
   
[root@zyq NetPackets]#   
