# Long-line-bed
**Determining operational performance measures**

**Capacity, Process capacity, and Flow Rate**

Equation function under value library is used for estimating capacities of stations, process capacity, and finally for determining flow rate of the process. Following command has to be typed. Assuming demand to be 26 segments per month.

![image](https://user-images.githubusercontent.com/103962807/167248883-e4b236b8-8f9c-44d5-b4fe-9a6d197ea783.png)

**Utilization**

Utilization at station is obtained by dividing flow rate of the process with the capacity of that station. Following command will give utilization values.

![image](https://user-images.githubusercontent.com/103962807/167249069-4c4cd58b-106c-4428-9f7a-125543485863.png)

**Cycle time and total idle time**

Cycle time value is obtained for each of the process by simulation variable and set block. And finally using maximum function under equation block, to determine cycle time of the overall process. Idle time at station is the difference between overall cycle time and processing time at station. Total idle time is the sum of the idle time at all stations.

![image](https://user-images.githubusercontent.com/103962807/167249115-66798f41-ea08-4f21-a6f4-17193e7f3b57.png)

![image](https://user-images.githubusercontent.com/103962807/167249117-a5cb77dd-119b-402e-b0f2-46e5075001ae.png)

**Direct labor content and Direct Labour Utilization**

Following command will be give values for DLC and DLU.

![image](https://user-images.githubusercontent.com/103962807/167249143-df25fce8-e987-4a83-94ca-02e448266461.png)

Note: Demand value is obtained from the erection schedule. Demand value varies from project to project and mainly depends upon the project’s scope and duration. 
