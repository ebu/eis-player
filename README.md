EURORADIO International Signal - VIS Player
==========

This archive file contains a static RadioVIS player. It is a jQuery component that can be integrated in any page using jQuery or simply by using the iframe.
It has been tested against jquery 10.2. The project is split in two folders:

* `component` contains a self-explanatory example of embeding the jQuery component.
* `iframe` contains an example of integration using an iframe.

Do not hesitate to contact Mathias Coinchon (coinchon@ebu.ch) and Michael Barroco (barroco@ebu.ch) if you need further information.

## Technical Details
The radioVIS player opens a websocket connection to `eis-edge.ebu.io` and subscribe to the RadioVIS topic used when iniating the component.
If there is no picture is available, a generic event image (Blue track in the background) will be displayed.

### Debug
When using Chrome or any other in-browser debugger, typing `$('.radiovis-outtertext').show()` in the console will display the RadioText and a red message in case of error

### Issues
Please use the issue tracker to capture any comment or feedback.

## Related project

* [RadioVIS WebSocket server](https://github.com/ebu/radiovis-html5player)
* [RadioDNS server](https://github.com/ebu/radiodns-plugit)


## License (BSD)

Copyright (c) 2013, EBU
All rights reserved.

Redistribution and use in source and binary forms, with or without modification, are permitted provided that the following conditions are met:

1. Redistributions of source code must retain the above copyright notice, this list of conditions and the following disclaimer.

2. Redistributions in binary form must reproduce the above copyright notice, this list of conditions and the following disclaimer in the documentation and/or other materials provided with the distribution.

3. Neither the name of the EBU nor the names of its contributors may be used to endorse or promote products derived from this software without specific prior written permission.

THIS SOFTWARE IS PROVIDED BY THE COPYRIGHT HOLDERS AND CONTRIBUTORS "AS IS" AND ANY EXPRESS OR IMPLIED WARRANTIES, INCLUDING, BUT NOT LIMITED TO, THE IMPLIED WARRANTIES OF MERCHANTABILITY AND FITNESS FOR A PARTICULAR PURPOSE ARE DISCLAIMED. IN NO EVENT SHALL THE COPYRIGHT HOLDER OR CONTRIBUTORS BE LIABLE FOR ANY DIRECT, INDIRECT, INCIDENTAL, SPECIAL, EXEMPLARY, OR CONSEQUENTIAL DAMAGES (INCLUDING, BUT NOT LIMITED TO, PROCUREMENT OF SUBSTITUTE GOODS OR SERVICES; LOSS OF USE, DATA, OR PROFITS; OR BUSINESS INTERRUPTION) HOWEVER CAUSED AND ON ANY THEORY OF LIABILITY, WHETHER IN CONTRACT, STRICT LIABILITY, OR TORT (INCLUDING NEGLIGENCE OR OTHERWISE) ARISING IN ANY WAY OUT OF THE USE OF THIS SOFTWARE, EVEN IF ADVISED OF THE POSSIBILITY OF SUCH DAMAGE.


## Contributors

* Maximilien Cuony [@the-glu](https://github.com/the-glu)
* Michael Barroco [@barroco](https://github.com/barroco)
