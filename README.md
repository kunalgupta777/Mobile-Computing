# Mobile-Computing
This repository contains all the 6 programs ( except the research paper implementation ) for the Mobile Computing Lab.
All codes are implemented in *NS2*

# How to install NS2?
Open up a terminal and type
``` bash
$ sudo apt-get install ns2
```
Further, install the NAM visualiser by typing
``` bash
$ sudo apt-get install nam
```
To verify, use
``` bash
$ ns
%
```
If you see that % sign, this means ns2 is successfully installed.

# How to use this repository?
You can clone this repo by
```
git clone https://github.com/kunalgupta777/Mobile-Computing
```
# How to use the code?

Navigate to the folder of any program (1-6). Each programs consists of atleast 2 scripts: 
 - *a .tcl script* 
 - *.awk script*
When you run the tcl (tool chain language) script, it generates two more files:
 - *.tr file*  - a trace file which logs all the events
 - *.nam file* - which will be used by the NAM simulator.
All the codes are already tested, and hence each folder contains the necessary extra files.

To run the .tcl file, navigate to the folder of the experiment, and type:
``` bash
$ ns progX.tcl
```
where 'X' is the program number.
You'll see a NAM window opening up, use the GUI tool to see the visualisation.
To run the .awk file, type
``` bash
$ awk -f <name of awk file>.awk <name of trace file>.tr
```
to see the output/statistics of the code.

# List of Experiments:
1.   Implement three nodes point - to - point network on NS2/NS3 with full duplex links between them. Set the queue size, vary the bandwidth and find the number of packets dropped.
2.   Implement:
      i.   transmission of ping messages
      ii.  transmission of traceroute
     over a network topology consisting of 6 nodes on NS2/NS3 and find the number of packets dropped, number of hops, and intermediate node ids.
3.   Implement an Ethernet LAN using n nodes and set multiple traffic nodes and plot congestion window for different source/destination on NS2/NS3.
4.   Implement and study the performance of GSM on NS2/NS3 using MAC layer.
5.   Implement and study the performance of CDMA on NS2/NS3 using stack environment.
6.   Simulate a mobile ad-hoc network on NS2/NS3. 

# Contact
Mail me at upanshug53@gmail.com, if you have any queries.
 



