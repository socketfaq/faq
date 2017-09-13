## 1.4 What are Sockets?

Sockets are just like "worm holes" in science fiction. When things go into one end, they (should) come out of the other. Different kinds of sockets have different properties. Sockets are either connection-oriented or connectionless. Connection-oriented sockets allow for data to flow back and forth as needed, while connectionless sockets (also known as datagram sockets) allow only one message at a time to be transmitted, without an open connection. There are also different socket families. The two most common are AF_INET for internet connections, and AF_UNIX for unix IPC (interprocess communication). As stated earlier, this FAQ deals only with AF_INET sockets.

This brief answer was obviously not nearly enough. A long and kind of painful thread was
captured in the forum version of the FAQ at http://developerweb.net/viewtopic.php?id=2961.

Looks like this needs to be expanded upon!
