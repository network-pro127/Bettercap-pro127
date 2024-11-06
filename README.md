# Bettercap-pro127
using Bettercap NETWORK TRAFFIC MONITORING projects
BetterCAP is a powerful, flexible and portable tool created to perform various types of MITM attacks against a network, manipulate HTTP, HTTPS and TCP traffic in realtime, sniff for credentials and much more.
This is quite a generic description, mostly because ( if we're talking about network MITM attacks ), the logic and details heavily rely on the technique being used ( more in the spoofing section ).

Nevertheless we can simplify the concept with an example. When you connect to some network ( your home network, some public WiFi, StarBucks, etc ), the router/switch is responsible for forwarding all of your packets to the correct destination, during a MITM attack we "force" the network to consider our device as the router ( we "spoof" the original router/switch address in some way ):
Once this happens, all of the network traffic goes through your computer instead of the legit router/switch and at that point you can do pretty much everything you want, from just sniffing for specific data ( emails, passwords, cookies, etc of other people on your network ) to actively intercepting and proxying all the requests of some specific protocol in order to modify them on the fly ( you can, for instance, replace all images of all websites being visited by everyone, kill connections, etc ).

BetterCap is responsible for giving the security researcher everything he needs in one single tool which simply works, on GNU/Linux, Mac OS X and OpenBSD systems.
