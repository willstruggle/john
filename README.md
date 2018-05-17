# John the Ripper 1.8.0.13-jumbo-1-bleeding-0abfc74 2018-05-15 08:39:32
Ini adalah binary dari john the ripper versi jumbo yang di recompile dari system backbox 5 (Ubuntu 16.04).
Binary ini sengaja saya recompile karena john the ripper bawaan dari backbox 5 sendiri masih menggunakan john versi terdahulu.

# Cara installasi
1. ```sudo su```
2. ```apt-get install openssl libgmp-dev libgomp1```
3. ```cd /opt```
4. ```git clone https://github.com/koboi137/john```
5. ```cd john/```
6. ```mv librexgen.so.2.0.8 /usr/local/lib/```
7. ```ln -s /usr/local/lib/librexgen.so.2.0.8 /usr/local/lib/librexgen.so.2.0```
8. ```ln -s /usr/local/lib/librexgen.so.2.0.8 /usr/local/lib/librexgen.so```
9. ```echo "export PATH=/opt/john:$PATH" >> ~/.profile```
10. ```ldconfig```

Untuk informasi lebih lanjut bisa kunjungi di githubnya langsung https://github.com/magnumripper/JohnTheRipper
