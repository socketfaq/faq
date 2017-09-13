## How do Sockets Work?

The implementation is left up to the vendor of your particular unix, but from the point of view of the programmer, connection-oriented sockets work a lot like files, or pipes. The most noticeable difference, once you have your file descriptor is that read() or write() calls may actually read or write fewer bytes than requested. If this happens, then you will have to make a second call for the rest of the data. There are examples of this in the source code that accompanies the faq.

Some good discusson added to this: http://developerweb.net/viewtopic.php?id=2962
