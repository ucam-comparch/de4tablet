The DE4 Tablet is a portable tablet computer designed by the Computer
Laboratory at the University of Cambridge.

It uses a Terasic DE4 FPGA board with an Altera Stratix IV FPGA.  It has a
full set of peripherals on the DE4, as well as a battery, touchscreen and
HDMI output - you can give presentations from your own FPGA design!

This is the mechanical design - what you put on the FPGA is up to you!
We hope to open source more of the components we use on our boards in
future.

![The DE4 tablet booting](http://www.cl.cam.ac.uk/research/comparch/opensource/de4tablet/tablet-booting-cheri.jpg)
![The FPGA side](http://www.cl.cam.ac.uk/research/comparch/opensource/de4tablet/tablet-fpga.jpg)

To build the Tablet you will need:

[A DE4 FPGA board](http://de4.terasic.com.tw) (we used the SGX230 version)  
[Terasic Multi-touch LCD module](http://www.terasic.com.tw/cgi-bin/page/archive.pl?Language=English&CategoryNo=68&No=653)  
[HDMI Transmitter Daughter Card](http://www.terasic.com.tw/cgi-bin/page/archive.pl?Language=English&CategoryNo=66&No=582) (optional)  
[Energizer XP8000 battery](http://www.energizerpowerpacks.com/uk/products/xp8000/) (optional, ours came from CPC)  
[PicoPSU-80 voltage converter](http://www.mini-itx.com/store/psu)  
Some 1, 2, 3 and 4mm acrylic for laser cutting pieces  
A collection of M3 screws and pillars - see the full parts list  

There are two versions - one with battery and HDMI output and the other
without.  These instructions assume you're building the battery version -
the non-battery version is simpler and you can just omit steps relating to
the HDMI and battery.

You can find the assembly instructions with photos here:
http://www.instructables.com/id/DE4-FPGA-tablet/


Computer Architecture Group, University of Cambridge Computer Laboratory  
June 2013  
http://www.cl.cam.ac.uk/research/comparch/  


Copyright (c) 2013, Theo Markettos  
All rights reserved.  

Redistribution and use in source and binary forms, with or without
modification, are permitted provided that the following conditions are met:

Redistributions of source code must retain the above copyright notice, this
list of conditions and the following disclaimer.

Redistributions in binary form must reproduce the above copyright notice,
this list of conditions and the following disclaimer in the documentation
and/or other materials provided with the distribution.

THIS SOFTWARE IS PROVIDED BY THE COPYRIGHT HOLDERS AND CONTRIBUTORS "AS IS"
AND ANY EXPRESS OR IMPLIED WARRANTIES, INCLUDING, BUT NOT LIMITED TO, THE
IMPLIED WARRANTIES OF MERCHANTABILITY AND FITNESS FOR A PARTICULAR PURPOSE
ARE DISCLAIMED.  IN NO EVENT SHALL THE COPYRIGHT HOLDER OR CONTRIBUTORS BE
LIABLE FOR ANY DIRECT, INDIRECT, INCIDENTAL, SPECIAL, EXEMPLARY, OR
CONSEQUENTIAL DAMAGES (INCLUDING, BUT NOT LIMITED TO, PROCUREMENT OF
SUBSTITUTE GOODS OR SERVICES; LOSS OF USE, DATA, OR PROFITS; OR BUSINESS
INTERRUPTION) HOWEVER CAUSED AND ON ANY THEORY OF LIABILITY, WHETHER IN
CONTRACT, STRICT LIABILITY, OR TORT (INCLUDING NEGLIGENCE OR OTHERWISE)
ARISING IN ANY WAY OUT OF THE USE OF THIS SOFTWARE, EVEN IF ADVISED OF THE
POSSIBILITY OF SUCH DAMAGE.
