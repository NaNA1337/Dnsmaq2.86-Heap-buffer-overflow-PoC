# Dnsmaq2.86-Heap-buffer-overflow-PoC

### *WARNING: ITS NOT HAVE TEST FOR REAL ENVIROMENT*

This code is a memory heap overflow PoC written for a specific version of dnsmaq vulnerability. 

You only need to enter the IP to continuously send malicious data packets to the server. 

Please make sure that the server has enabled the specific service and version. 

I have not made any major adjustments to the content of the overflow data. 

Please adjust the starting byte of the `QNAME` field of the data packet according to the actual situation before use.

You can adjust the frequency of sending packets in the `usleep` field of the code to prevent being detected by the server's IP risk control