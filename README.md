# Traffic-Light-Controller-DLD

# Project Name:
4 WAY TRAFFIC LIGHT CONTROLLERS

# Abstract:
Our project is to develop traffic light controller. The purpose of this is to control the flow of rushing cars with the traffic signals.

# Working:
There are total four roads. Each road has two partitions, one for the traffic coming towards the square (traffic in) and the other one for traffic going out of the square (Traffic Out). Each partition has three lanes. The cars at right most lanes go on the road at right side. The cars in middle lane go straight. The cars in left most lanes go on the left side of road.
 
![image](https://user-images.githubusercontent.com/68895316/120934407-c0567980-c717-11eb-939a-0b78b1db7679.png)


# Explanation:
* First of all, we use 8 D- f lip flop to delay the signal of the signals
* The purpose of this flip flops is to delay the signal to count 8. This means that one signal is on for 8 number of count of clock pulse completely and then shift towards the next signal.
* From truth table we make the equations of the signal of red, green and yellow.
* Then, we use further 2 D flip flop which was further attached to four AND gates by the equations and then each AND gate is attached to one traffic signal.
* The equations of all four signals are almost same. The basic differences which differentiate the signal are the clock pulse of 8 counts.
* Each signal has three D flip flops and their respective outputs are supplied to the red, green and yellow lights of one signal.
* Clock pulse operate the signals one by one.

# Requirements:
1-	System should show the flow of cars
2-	Cars will randomly come on Traffic In partitions.
3-	Each lane can have 15 cars at max and you need to display only 4 cars per lane.
4-	There is one traffic signal per road for traffic In. Traffic In will stop if the signal is red and start running when it turns green.
5-	Four signals (one per road) run clockwise i.e. road 1’s signal will be green at start, then road 2’s then road 3’s, then road 4’s and then again road 1’s signal will be green.
6-	Each signal remains green for 16 ticks at max or until there is no car on that road.
7-	Signal will turn yellow for 4 ticks before turning red.

# Circuit Diagram:
![image](https://user-images.githubusercontent.com/68895316/120934500-e9770a00-c717-11eb-86cc-a035d13234c2.png)




