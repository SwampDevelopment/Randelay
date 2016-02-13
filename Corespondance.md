02/10/2016
Hey, Dude,
 
I think we got the flip-flop thing the way it should be, however, I also need an output that will go lo for a set amount of time (place in code to change) and then return
Hi. I have to be able to disconnect power from the monitor and return it after a flip or a flop.
 
Best,

02/13/2016
Functionality
	A low on triggerIn sets off the following sequnce of events...

	1.	output 1 goes low for 30 seconds(setable in firmware). (To kill the monitor so that it will re aquire the comm protocol
		from witchever PCB is active when it is turned back on)
	2.	output 2 begins pulsing at 100ms(settable in firmware)
		for as long as output 1 is low! then goes back high. (For active indicator LED)
	3.	output 3 toggles its state from L to H or vice versa (This will switch from PBC A or B)
