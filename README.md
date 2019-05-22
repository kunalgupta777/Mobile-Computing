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
#Contact
Mail me at upanshug53@gmail.com, if you have any queries.
 



