
```
[not_real_ip]
client1
client2
client3

[real_ip]
server1
server2
server3

[service_wireguard_server:children]
real_ip

[service_wireguard_client:children]
not_real_ip

```
