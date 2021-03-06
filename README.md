# ADAPTIVE_TRAFFIC_LIGHT_SYSTEM

# ABOUT REPOSITORY

**what is the problem ?**

Traffic congestion lead to disorder on roads. Currently traffic signals have pre defined timers. Our approach is, to control the signals based on real time vehicle density thus saving time, resources and reducing pollution.One of the main reasons behind today’s traffic problem are the techniques that are used for traffic management. It has no emphasis on live traffic scenario, thus leading to inefficient traffic management systems.

If the traffic light timers are showing correct time to regulate the traffic, then the time wasted on unwanted green signals will be saved. Timer for every lane is the simplest way to control traffic. And if those timers are predicting exact time then automatically the system will be more efficient.


<img src="https://camo.githubusercontent.com/46eeb2384e8f7e1213475d5b1bfdb2404a2c9d81/68747470733a2f2f7777772e7472616e73706f72746174696f6e2e676f762f73697465732f646f742e676f762f66696c65732f322e6a7067"
     alt="https://camo.githubusercontent.com/46eeb2384e8f7e1213475d5b1bfdb2404a2c9d81/68747470733a2f2f7777772e7472616e73706f72746174696f6e2e676f762f73697465732f646f742e676f762f66696c65732f322e6a7067"
     style="float: left; margin-right: 10px;" />

     

# REQUIREMENTS
1. **TENSORFLOW**

2. **NUMPY**

3. **OPENCV**

4. **YOLO**

# DATA

1.[link of input folder](https://drive.google.com/drive/folders/1YVggbYVgH5hJkDFUYalSHz6rMXNl_SzM)

2.[link of output](https://drive.google.com/drive/folders/143wV-efr9zReXmo1BRLkcYUrFhRU5IyB)

# ROADMAP OF COUNTING.

**openCV approach**
Placing a Camera on each side of the intersection and Processing the images to get the number of vehicles on each side of the intersection.

1. Read using OpenCv Library in Python.
2. resized according to need.
3. use opencv dnn module to detect images(use trained weights and config file).
4. get the count of vehicles using label list.

[link of process](https://github.com/vr620/Adaptive_traffic_light_system/blob/master/final_complete_code.ipynb)

<img src="https://github.com/vaibhavsethia/Smart-Traffic-Light/blob/master/IMG/imagenew.jpg"
     alt="https://github.com/vaibhavsethia/Smart-Traffic-Light/blob/master/IMG/imagenew.jpg"
     style="float: left; margin-right: 10px;" />

# How are these Numbers manipulated ??

Once stored in a list the number of cars are manipulated to clear the congestion as soon as possible .

**1st method**
**using variance of cars in all four lens**
1. count vehicles in all four lens.
2. calculate varience.
3. allotment of timings according to the varience.
[link of method](https://github.com/vr620/Adaptive_traffic_light_system/blob/master/varience_based.ipynb)

**2nd method**
**using profit loss method**
1. count vehicles in a single len.
2. calculate timing of that len.
3. calculate the profit gained from this cycle.
4. add the profit to the next len timing if that len is congested.
[link of method](https://github.com/vr620/Adaptive_traffic_light_system/blob/master/profit_loss_based_method.ipynb)


# Future Scope
1. Can be developed for three lanes of each side of the road ( Prototype Extended Version )
2. Can be moulded to be used in situations like mass evacuation
3. Linking of other traffic lights in sync to provide better congestion clearing
Can be developed further to be used by emergency vehicles to provide Green route and decreasing accidents on intersections.
5. repeat.




