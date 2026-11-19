# A11 – Motor Selection

## Objective
The objective of the assignment is to select a motor that is appropriate for our purposes. The motor needs to help deliver up to 2kN or 450lbf on a piece of material to be stretched to failure. Within this selection, it was important to consider the aforementioned parametes and other related specifications within a safety factor of 4 (already included in the diameter selection of the screw, affecting all related measurements).

## Motor Selection

Based on the calculations from the last assignment, the required torque is 19.62 lb-in and the speed range is 0.3937-19.685RPM. 19.62lb-in is 313.92in-oz (Calculation: 19.62lb-in*16oz/lb).

Inspecting the stepper motors on McMaster-Carr, the strongest only goes up to 175.6in-oz.

<img width="1072" height="443" alt="image" src="https://github.com/user-attachments/assets/2dd4c407-a4b5-423f-8e48-c568644b06b7" />

The DC gearmotors have a much higher maximum torque:

<img width="1009" height="542" alt="image" src="https://github.com/user-attachments/assets/57d25450-151e-4915-bc1c-cf131d595134" />

However, after closer inspection, these motors only supplied a continuous operating torque at a certain speed. We need a speed range.
Going over to the compact DC motors, torque-speed charts are provided. Selecting the weakest motor:

<img width="383" height="292" alt="image" src="https://github.com/user-attachments/assets/f5f28200-e626-4b3b-883e-3f9cff68420d" />

This motor is NOT appropriate. It cannot reach the required ~20RPM with a ~20lbf-in or ~315RPM. We need less torque and higher RPM.

<img width="1028" height="339" alt="image" src="https://github.com/user-attachments/assets/6f8295f2-1e04-412d-91ad-7b280a03c60d" />

This motor is the first out of the list that goes above 20RPM. So it fulfills that requirement. We now inspect the speed-torque curve.

<img width="374" height="287" alt="image" src="https://github.com/user-attachments/assets/cb4d3078-c1ee-4bbd-9019-0ea044364fe0" />

Inspecting the possible ranges, this motor fulfills the required range and load based on torque.

Just to make sure, inspecting the previous motor in the list, it is observable that this motor cannot reach the ~315in-oz at an RPM of 20. 

<img width="377" height="290" alt="image" src="https://github.com/user-attachments/assets/16562909-8c2b-49c4-824b-8315692de7b1" />

Considering that the previous motor that has the correct range is around $73, which is affordable compared to higher-end options, we shall select that motor:

<img width="1439" height="680" alt="image" src="https://github.com/user-attachments/assets/4fc24422-8e27-4193-b623-a29b49886887" />

Which has the following torque-speed chart:

<img width="765" height="585" alt="image" src="https://github.com/user-attachments/assets/f670b268-19a8-4163-bfb1-91977dacc257" />

Link to Part: https://www.mcmaster.com/6409K17/



## Motor Mount Bracket Housing Design

## Coupler

## Analyze and Design a Frame (Yazahira)

The Frame 

Before working on the FEA i had to analyze the twist caused by the motors and find the forces required to stabilize the top of the frame. 

After analyzing the twist caused by the motor on the frame I confirmed that the frame would be able to handle the stressed caused by the motors. I also found the force on each side of the frame where the motors would be. 


<img width="557" height="280" alt="Screenshot 2026-11-18 103852" src="https://github.com/user-attachments/assets/66d535a8-a9ba-41aa-8975-eb14cdf4e4c6" />



 Based on the information I have I decided on this frame connector. 


<img width="921" height="398" alt="Screenshot 2026-11-18 200101" src="https://github.com/user-attachments/assets/b7521f91-0250-49a9-82ab-082e823d62a0" />


 The FEA

Top frame

The first FEA I will run will be on the Top frame. I began by adding the torque and the fixed geometry on the top frame before starting the analysis. I ran an analysis with a medium coarse mesh and followed by a fine mesh in order to test for convergence.




|   | SF    | Stress    |Deflection|
|---|-----|--------------|-----------
|1  |0.27| 1.496x10^4 psi |6.912 mm|
|2  |0.25|1.584x10^4 psi|  6.913 mm|
|Convergence| 0.1%|  0.1%| 0%|


Vertical Components

Now that I've run the FEA on the top frame I will run an FEA on a side frame. The frame material will remain the same. As the top frame. I added the axial and transverse load to the frame as well as the fixed geometry. 


<img width="951" height="500" alt="Screenshot 2026-11-18 142458" src="https://github.com/user-attachments/assets/5fafa718-421e-439e-92a6-a6f4137edf81" />


<img width="535" height="320" alt="Screenshot 2026-11-18 142707" src="https://github.com/user-attachments/assets/4838094b-dba5-4be7-9f8d-d590c5283598" />


I ran the first simulation with a medium coarse mesh. These were the resulting graphs for Von Misses Stress and deflection. The graphs also graph where the maximum stress and deflection points are and their value. 


<img width="551" height="343" alt="Screenshot 2026-11-18 143758" src="https://github.com/user-attachments/assets/f6c6e5c2-80ab-4c61-b543-7b9decc85a4d" />


<img width="578" height="328" alt="Screenshot 2026-11-18 143914" src="https://github.com/user-attachments/assets/7e547545-b346-45ce-939f-774a22a36fcd" />


I then ran another simulation everything staying the same but this time with a fine mesh. 


<img width="767" height="365" alt="Screenshot 2026-11-18 150100" src="https://github.com/user-attachments/assets/58d19e3b-3950-4170-ac63-28206c509265" />



<img width="497" height="326" alt="Screenshot 2026-11-18 145933" src="https://github.com/user-attachments/assets/20f2b80b-71fa-40f7-906e-fe3ac50bb426" />

After finishing up both simulations I checked for convergence and these were my values. All the values did converge on the after the first two simulations with different sized mesh. However the safety factor is too low.


|   | SF    | Stress    |Deflection|
|---|-----|--------------|-----------
|1  |0.27| 1.496x10^4 psi |6.912 mm|
|2  |0.25|1.584x10^4 psi|  6.913 mm|
|Convergence| 0.1%|  0.1%| 0%|


Since the safety factor is way to low that being below 1. This would main our frame would most likely fail. A change that we propose could help the frame from failing would be a changing the material. A material with a higher yield strength would help the frame hold despite the forces acting on it currently. The locations of the maximum stress and deflection didn't change and the values didn't change much either. I believe changing the material would lead to better results. 

## Bearing Mount Design (Yazahira)


<img width="444" height="352" alt="Screenshot 2026-11-18 213641" src="https://github.com/user-attachments/assets/b95717c4-ca6b-4feb-8a28-c2757e89ac91" />
<img width="466" height="280" alt="Screenshot 2026-11-18 213543" src="https://github.com/user-attachments/assets/842c5811-ea4f-4665-aaa1-3f3f975416cc" />


This is what my design for the bearing mount looks like.I made the mount 3x3 because the width of the frame we used is 3 in. I made the middle hole where the screw would go .5 in diameter since that is the diameter of the lead screw. According to the Machinery Handbook the clearance for this hole for an RC3 fir is +.6 - 0. I decided to use  1/4 in bolts that are 2 in apart for his mount. Based on the book i made the holes for the bolts 0.266 in in diameter. 



<img width="683" height="346" alt="Screenshot 2026-11-18 205308" src="https://github.com/user-attachments/assets/c45c3c5c-d76a-43a1-b1d4-62a61652dfe5" />


<img width="443" height="248" alt="Screenshot 2026-11-18 215037" src="https://github.com/user-attachments/assets/34eabbbc-9b6b-4644-883a-3da8b9822307" />


## Costs

## Lessons Learned


With this assignment we learned more about motors. We learned how to correctly read a motor graph and choose a mottor based on that graph that would correctly fit our needed torque and rpm. With this assignment I struggled a lot with the FEA and adding the correct loads to the frames. Our safety factor for the frames were both terribly low. The top frame completly twists. Im not sure if its the way i added the torque on the frame or the material. But i learned I  need more practice running FEAs to correctly add all the parts and have then run how they should. Both our vertical and top frame failed but i learned more about running FEAs. 

## Drawing






Links/ Files:

Bearing Mount:

[Bearing Mount.zip](https://github.com/user-attachments/files/35063638/Bearing.Mount.zip)


Frame connectors-

https://www.grainger.com/product/80-20-Inside-Corner-Bracket-Inside-2RCW7

