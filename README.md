DoulCi-server
=============

Leaked DoulCi Activation Lock bypass server by w0rm

How to install:
1) Put files to htdocs folder in XAMPP
2) Edit hosts and add line:
127.0.0.1 albert.apple.com

If need bypass iTunes error (8xxx) - just install Fiddler2 fake RootCA

Warning: 
Server not working without true certificate and private keys (cert included in true_certs folder, but still need private keys).
Activation Tickets do not make a wildcardticket.pem, mean without cellular. 
Now device always reject activation tickets, because do not trust us.