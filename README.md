# G2-E-sports-Networking
G2 E-sports a global E-sports conglomerate wants to expand into Bangladesh to enrich and diversify their already growing arsenal of promising E-sports professionals. The aim of G2 in Bangladesh is to not only search for talented E-sports players but, also build Lan Cafes all over Bangladesh to connect like-minded E-sports enthusiasts. G2 believes that Bangladesh has the potential to make it big in the global E-sports events of various games. Now, G2 will initially construct one Lan Cafes in the capital of six Divisions of Bangladesh, aside from these 6 Lan Cafes their will be two corporate offices in Dhaka and Chittagong which will be situated in the same building and network as the respective Lan Cafes. G2 is very sorry for not being able to establish Lan Cafes in the remaining two divisions due to lack of resources. Now they have selected me as their network engineer so, my task is to design and implement a network connection to connect the branches/Lan Cafes according to their requirements. In the following table the distance is given in kilometer between each branch and also their maximum capacity is mentioned in brackets beside the name of each branch.
While creating the network infrastructure there are certain restrictions and rules that you need to follow: 
>1. Choose an appropriate network address and create subnets to assign to each of the branches with the least amount of waste.
>Dhaka and Chittagong branch has corporate offices so, to ensure security they will use static addressing while the other branches will get their IP addresses through DHCP
>2. Dhaka and Chittagong branch will be communicating via email so, set up an email server for sending and receiving emails among Dhaka and Chittagong branch.
>3. Assume that Khulna, Rajshahi, Mymensingh and Sylhet will use private addressing while the rest of the branches will be using public addressing
>4. Dhaka and Chittagong branch will have printers for the corporate activities
>5. Rajshahi (156) has a web server and a DNS server. When someone connects to the web server it will show “Hello Bangladesh! Welcome to the G2 army” in the homepage www.g2bangladesh.com 
>6. Establish connections among all the branches with the shortest route possible
>>a. Must have at least one floating route.
>>b. Must have a backup system to handle missing routing entries. You have to remember the default route cannot be used while exchanging packets. Data will be delivered using static or dynamic routes only. For an ISP router you can use the default route but for communicating among the given networks in the above table you have to use static or dynamic routing
>>c. Configure half of the network to be routed dynamically
>7. Showing 2 end devices per network is good enough to represent the whole population
>8. You need to be able to ping each branch from another after all the setups are complete

Deliverables
>1. The network mentioned above should be implemented in packet tracer, with necessary devices and full configuration.
>2. After completion you should be able to test the conditions imposed.
>3. You will have to submit the followings:
>>a. Network topology diagram with proper labels
>>b. The configuration commands of all the routers that you have implemented.
>>c. VLSM tree
>>d. IP address table
