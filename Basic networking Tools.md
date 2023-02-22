The network is and always will be the sexiest arena for hacker. An attacker can do almost anything with simple network access, such as scan for host, inject packets, sniff data, and remotely exploits hosts. But if you've worked your way into the deepest depths of an enterprise target.
This chapter will give your some basics on python networking using the socket module. Along the way, we'll build clientsservers, and a tcp proxy. We'll then tum them into our very own netcat complete with a command shell.This chapteris the foundation for subsequent chapters, in which we'll build a host discovery tool, implement cross-platform sniffers, and  create a remote trojan framework 

## Python networking in a paragraph 
Programmers have a number of third-party tools to create networked servers and clients in python, but the core modiule for all of those tools is socket. This module exposes all of the neccesary pieces to quickly write transmission control protocol(TCP) and user datagram protocol(UDP) clients and servers, use raw sockets and so forth. For the purposes of breaking in or maintaining access to target machines, this module is all you need 

## TCP client 
If you are working within the confines of large enterprise enviroments, you won't have the luxury of using networking tools or compilers, and sometimes you'll even be missing the absolute basics like the ability to copy/paste or connect to the internet. This is where being able to quickly create a tcp client comes in extremely handy. But enough jabbering

























