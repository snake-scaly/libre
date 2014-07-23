libre
=====

Libre is a portable and generic library for real-time communications with async IO support and a complete SIP stack with support for SDP, RTP/RTCP, STUN/TURN/ICE, BFCP and DNS Client.

Features
--------

- SIP Stack (RFC 3261)
- SDP
- RTP and RTCP
- DNS-Client
- STUN/TURN/ICE
- BFCP
- Jitter-buffer
- Async I/O (poll, epoll, select)
- UDP/TCP/TLS transport

Download
--------

Latest and previous releases of libre can be downloaded [here](http://www.creytiv.com/pub).

Building and installation
-------------------------

To build libre we are using GNU Make. External dependencies are automatically detected by the makefile.

```sh
$ cd re
$ make
$ sudo make install
```

Examples and Demonstration
--------------------------

A separate redemo package is available in [download directory](http://www.creytiv.com/pub).

Here you will find examples on how to use the libre toolkit, including demonstations on how to create a basic UDP and TCP server with less than 100 and 200 lines of C-code respectively. Additionally you will find a basic SIP user-agent example. All the demo programs are built by simply typing make from the redemo directory.

Design Goals
------------

- Portable POSIX source code (ANSI C89 and ISO C99 standard)
- Intelligent and user friendly APIs
- Robust, fast, low memory footprint
- RFC compliance
- IPv4 and IPv6 support

Documentation
-------------

Doxygen API documentation can be found [here](http://www.creytiv.com/doxygen/re-dox/html).

Applications using libre
------------------------

- restund
- baresip

License
-------

```
Copyright (c) 2010 - 2014, Alfred E. Heggestad
Copyright (c) 2010 - 2014, Richard Aas
Copyright (c) 2010 - 2014, Creytiv.com
All rights reserved.


Redistribution and use in source and binary forms, with or without
modification, are permitted provided that the following conditions
are met:

1. Redistributions of source code must retain the above copyright
   notice, this list of conditions and the following disclaimer.

2. Redistributions in binary form must reproduce the above copyright
   notice, this list of conditions and the following disclaimer in the
   documentation and/or other materials provided with the distribution.

3. Neither the name of the Creytiv.com nor the names of its contributors
   may be used to endorse or promote products derived from this software
   without specific prior written permission.


THIS SOFTWARE IS PROVIDED BY THE AUTHOR ``AS IS'' AND ANY EXPRESS OR
IMPLIED WARRANTIES, INCLUDING, BUT NOT LIMITED TO, THE IMPLIED WARRANTIES
OF MERCHANTABILITY AND FITNESS FOR A PARTICULAR PURPOSE ARE DISCLAIMED.
IN NO EVENT SHALL THE AUTHOR BE LIABLE FOR ANY DIRECT, INDIRECT,
INCIDENTAL, SPECIAL, EXEMPLARY, OR CONSEQUENTIAL DAMAGES (INCLUDING, BUT
NOT LIMITED TO, PROCUREMENT OF SUBSTITUTE GOODS OR SERVICES; LOSS OF USE,
DATA, OR PROFITS; OR BUSINESS INTERRUPTION) HOWEVER CAUSED AND ON ANY
THEORY OF LIABILITY, WHETHER IN CONTRACT, STRICT LIABILITY, OR TORT
(INCLUDING NEGLIGENCE OR OTHERWISE) ARISING IN ANY WAY OUT OF THE USE OF
THIS SOFTWARE, EVEN IF ADVISED OF THE POSSIBILITY OF SUCH DAMAGE.
```
