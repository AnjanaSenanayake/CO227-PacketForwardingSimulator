# CO227-PacketForwardingSimulator -->     <a href="https://hiruna72.github.io/CO227-PacketForwardingSimulator/">Project Website</a> 
Packet forwarding network simulator   

store and forward method is used  

input file method

[no of routers] [no of links]  
[router1ProcessingDelay] [router2ProcessingDelay]  // processing delays   
//then describe link one by one  
[router1] [router2] [link distance] [transmissionRateofLink]  

to run  
compile and run app.java file in  
[simulators/src/main/java/com/co227/project/packetForwadingSimulator/simulators/]


the parameters are in following units

processing delay   - microSeconds  	    (10-1000)  
transmission rate  - MegabitsPerSecond	(1-7)  
packet size 	     - kiloBytes		      (1-5)  	  
link distance 	   - meters		          (several meters to thousonds of kilometers)  
transmiiting speed - kmPerSecond		    (2e+05)   


packet injection  
[packetName] [source] [destination] [packetSize] [priorityValue]


the input used in the program  

9 14  
2 1 3 4 5 6 7 1 0  
0 1 10 10  
0 7 20 10  
1 2 30 15  
1 7 40 20  
2 3 60 20  
2 8 70 14  
2 5 80 16  
3 4 50 10  
3 5 40 20  
4 5 60 15  
5 6 90 15  
6 7 75 15  
6 8 65 13  
7 8 45 45  

which describes the following graph (discard lengths of links)

![Alt text](/simulators/src/main/java/com/co227/project/packetForwadingSimulator/simulators/graph.PNG?raw=true "exampleGraph")
