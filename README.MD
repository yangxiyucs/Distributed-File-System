
CS7NS1 Individual Project - Distributed File System, Student ID:17303731 Name:Xiyu Yang

This is the core of any distributed file system and will consist of a server which provides access to files on the machine on which it is executed and a client side file service proxy that provides a language specific interface to the file system.

Caching is a vital element of any file system design that is required to give good performance and scale.

The directory service is responsible for mapping human readable, global file names into file identifiers used by the file system itself. A user request to open a particular file X should be passed by the client proxy to the directory server for resolution.

This server simply holds a flag for each file it is told about. Any client wishing to access a file could simply ask for access from the lock server. Providing all other clients do the same, it can be sure that client has exclusive access when access is granted.
