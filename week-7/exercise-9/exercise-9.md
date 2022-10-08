### The network ip of `193.16.20.35/29`
``` 
subnet 29 up bits
3 down bits
29 +3 =32 bits
32 bits is the  allowed numbered of bits in an Ip .
the ups are 1 while down 0
therefore the network IP of 193.16.20.35/29 is 
193.16.20.32.
```
<br>

###  Number of host  `193.16.20.35/29`
```
maximum number of hosts = 2** (32 - netmask_length) -2

where netmask_length = subnet value

maximum number of hosts = 2** (32 - 29) -2
maximum number of hosts = 6

the number of hosts that can be assigned IP's on network is 6.
```
<br>

### Range of IP addresses `193.16.20.35/29`
```
The range of IP addresses that can be assigned to the 
hosts lie in between the value of the `Network IP` and 
the `Broadcast IP` i.e 193.16.20.32 - 193.16.20.39

193.16.20.33
193.16.20.34
193.16.20.35
193.16.20.36
193.16.20.37
193.16.20.38

the above IPs are the acceptable Ips that can be
assigned to hosts.
```

### Calculating broadcast IP `193.16.20.35/29`
```
To get the broadcast IP, the host bits of the subnet value are converted to ones,
and network bits are converted to zeros.

11111111.11111111.11111111.11111000 => 00000000.00000000.00000000.00000111

The broadcast IP is gotten by getting the logical OR operation of the 
IP address and the new subnet value.

193.16.20.35 => 11000001.00010000.00010100.00100011
New subnet value => 00000000.00000000.00000000.00000111
----------- logical OR ------------
11000001.00010000.00010100.00100111

The logical OR value got is then converted to its
decimal value to get its Network IP.

11000001.00010000.00010100.00100111 => 193.16.20.39

Therefore the Broadcast IP of 193.16.20.35/29 is 193.16.20.39.
```


