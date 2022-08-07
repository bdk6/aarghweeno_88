# aarghweeno_88
An Arduino compatible prototyping board

Short story: add prototyping area to Arduino compatible AVR development board.

I have been a fan of the AVR processors for a long time.  My first project with them was in 2006.  The Arduino came along later and it is a neat system, making it very easy to get started.  When I say "Arduino" I mean AVR based ones.  If I should refer to some other, I'll specify.  

Now you can get an Aruino Nano clone for less than $5 US all over the web.  But one thing that has often bothered me about all the standard Arduino boards is that they don't have onbaord prototyping areas.  This little project aims to fix that.

The board is 3.9 x 3.9 inches, just under the 100 x 100 mm size of JLCPCBs cheapest PC board service.  About 1 1/2 inch along the "top" edge holds the AVR, regulator, programming header, and associated components.  The rest of the board is taken up with a prototyping area of holes on 0.1" centers arranged in groups of threes and long rows of bus connections.  There are also four mounting holes, another thing absent from standard Arduinos.  The idea is you can build an entire project on a single board without all those "dupont" (I hate that name) wires and whatnot crap going from board to board.

The one thing I left off that I agonized over was a USB interface or any type of serial port circuit.  Many of my projects don't need either and I generally prefer to use an AVR programmer to flash the chip.  If you really need/want a USB interface you can add it in the proto area.  You might need an SMD to DIP adapter or maybe just buy a USB to 5V serial module with 0.1" header pins.

You are welcome to use this board for any purpose, personal or commercial, as long as you leave the copyright notice in place.  I would like to know about any projects you build with it or comments in general.  If you make enough money selling it to hire Bill Gates and Jeff Bezos as your house boys, I wouldn't mind if you slipped me a mil or two.

20220807   First set of boards
I got the first boards back from JLCPCB on Thursday.  Friday morning I started soldering one up.  After replacing the LED that I soldered in backward, everthing seems to be working fine.  A bit more testing to do, but so far, so good.


![image](https://user-images.githubusercontent.com/23271409/183313629-24229505-7cba-4ad1-8be5-6b0033603522.png)

Today I cleaned up some minor flaws and I'm releasing version 1.1.  Changed to value of C3 (to 0.1 uF from 0.33 uF) and cleaned up some silkscreen.  No substantive changes.  I plan to run a set of these once I've tested the first one more.

