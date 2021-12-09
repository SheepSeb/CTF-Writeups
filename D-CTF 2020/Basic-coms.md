# Basic Coms
### 10 points
Look for it and you shall find the flag.

---
We get a pcap file. Firstly I try to use 
```
strings basic-coms.pcapng | grep 'flag'
```
to find if has the flag in plain sight
Afterwards I open the pcap file using wireshark to view it. We search for the http and find 4. The GET request seem intresting haivint the '?important'

There we find the flag in the request

53553	52.630465106	192.168.3.122	93.184.216.34	HTTP	681	GET /?important=The%20content%20of%20the%20f%20l%20a%20g%20is%20FLAG%20and%20respects%20the%20format HTTP/1.1 