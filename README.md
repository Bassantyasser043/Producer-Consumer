
# Producer-Consumer

## Opening both angular and Spring boot code: 
### Running Angular:
1. Unzip downloaded file.
2. you must have NodeJS and angular-Cli on your computer.
3. After unzipping the file, open the project file and press right click on the background of the folder. Open cmd window.
4. Write npm install in cmd window.
5. Now, you can open the project by writing ng serve –open in cmd window (port number: 4200).
### Running Spring Boot project:
1. Open Eclipse ide or any other ide.
2. Import the whole Spring boot folder into ide.
3. Make sure while running the code that the port number inside (Crossorigin is the same port number of angular project).
4. How to run Producer consumer simulator:

1- Run Angular Code while Running Spring boot program to be able to receive data from the front end (http://localhost:4200/).

2- As shown the picture this page will appear in the browser which contains simulator interface as shown in fig.1
![](https://lh6.googleusercontent.com/RZ9ZzNHlhjPMlZp6NZB6-jfwyq0825SplXcC_yqonEPa3RLSaC0rRYXV6frBdWchfMnMHzjlclbV2e1lmZ7dY3l86TN8s82uoRMzOAcay0R7pHXhvbSfnjQnY3VtLbdi8C4z0fGz)

### Snapshots of the UI and a User Guide:
1- for adding the Queue component which is the place that product waits according to predominant waiting time, just click on the place you want to add the queue into then click on Add Queue button (like shown in the figure 1).
![](https://lh4.googleusercontent.com/CE5zXI0UesObV8ErpMT_muMuZZ1lDoH1v_yNS9TdeFsq2FeDJqDtWOFnJK29N1Gedu2zonX6AXl9-ndjp9mAvWX_T1nPhsJtWiKT58BldqUYZEYSuxveaGRIoOX1W8qZdbCu0TPa)

2- Adding Machine is the same process as Adding queue. Choose the wanted place then click on Add product button the machine will appear on the screen.
3-  To make a connection between queue and machine, you must choose the product according to the wanted flow. If you want the product to go from the machine first then goes to the queue you must click first on the wanted machine then the queue then click on Connect button. The Opposite also accepted (from the queue to the machine ). It is not acceptable to make a connection between the same kind of diagrams like two queues or two machines.
![](https://lh4.googleusercontent.com/CJXD-AySPJHxjN5SSLQnV5ilMGFL8__nWghxf5wewloRguizmqTCQV1UhPGGjbyyxTTlGxm7jCquaSFhLHlKy4JmSOFzjygCrLrb-IM7GCaVXh_XK3sQcuvxatk9kvI8xajM3Bhg)
![](https://lh5.googleusercontent.com/6PX_T96IwUL5gmfFVloodDoq1qaeFI9euelF3ccxQyTs9aYbRLmz_1wSXq8jWCw-E5y3ss4YB5L09JV7ylV1FcykmwNRT0AIv8WjQMqqe6b0J3TGpsswyWU-URDgHjYmVRFxX2HS)




4- To start the simulation after adding all machines ,queues and connections between them ,you must enter the number of products and then press the button of Run.
![](https://lh5.googleusercontent.com/4g-LjSLoEEaMybaec3coRLbl9RxnHzUnZxEtlHBfohbB-UglDBVYH7EGpZZqJxhQSyGY1a6H-nLhLHxVaP7oxrOzsdTY14cb_aRVmx7LGIHwKl2Pg6_vrccCbrAgveNcqwlBfjf_)

5-To start up a new simulator from scratch, just click on the clear button and everything on the screen will be deleted.
6- If you want to stop the simulation at any time, just click on the button of Stop. 
7- If you want to replay the same simulation, just click on the button of Replay.

Decisions and Assumptions:
The user can’t connect 2 machines or 2 queues.
A machine can’t have 2 queues destinations.
The user should be aware when connecting as the first clicked object (queue or machine) is set to be the start point of the connection and the second clicked object will be the destination (end point). And both are treated differently.
A machine can’t be either the first thing in the simulation or the final destination of the simulation.
The time of each machine to process product is randomed (5 seconds at max).
The rate of products entering the queues is also randomed (3 seconds at max).
To start a new simulation means the previous simulation and design will be deleted permanently.
### For better UML resolution open the following link:[Visual Paradigm Online Shared Diagram (visual-paradigm.com)](https://online.visual-paradigm.com/share.jsp?id=313637343335352d31).
## Contributers:
* [Bassant Yasser](https://github.com/Bassantyasser043)
* [Mai Ahmed Hussein](https://github.com/MaiAhmedHussein)
* [Habiba Osama](https://github.com/habibaosama)
* [Toka Ashraf](https://github.com/TokaAshraf12)
