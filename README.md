# EMI_Lab
This repository houses the code used for a high school physics lab. It is neither of quality nor of importantance, as the lab is now done.
The code used for the transmitting and receiveing Raspberry Pis are in the similarly named .py files.
To run the code, first update the Pis with

>sudo apt-get update

>sudo apt full-upgrade

Then install python 3 with

>sudo apt-get install python3.11

Finally, run the programs with

>python3 transmit.py

or

>python3 recieve.py

(Yes I know I mispelled receive. I was tired.)

The programs will run unitl finished. Make sure both of the programs have a signal.txt and a data.txt file in the same directory/folder as them.
On the transmit side, the data.txt file will act as the data that is being sent.
On the receive side, the data.txt file will act as the final output for the program.

I'd suggest hooking both Raspberry Pis up to a network and using ssh to configure/run the programs.
