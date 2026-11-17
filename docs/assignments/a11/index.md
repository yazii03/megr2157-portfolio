# A11 – Motor Selection

## Objective
The objective of the assignment is to select a motor that is appropriate for our purposes. The motor needs to help deliver up to 2kN or 450lbf on a piece of material to be stretched to failure. Within this selection, it was important to consider the aforementioned parametes and other related specifications within a safety factor of 4 (already included in the diameter selection of the screw, affecting all related measurements).

## Motor Selection

Based on the calculations from the last assignment, the required torque is 19.62 lb-in and the speed range is 0.3937-19.685RPM. 19.62lb-in is 313.92in-oz (Calculation: 19.62lb-in*16oz/lb).

Inspecting the stepper motors on McMaster-Carr, the strongest only goes up to 175.6in-oz.

<img width="1429" height="591" alt="image" src="https://github.com/user-attachments/assets/2dd4c407-a4b5-423f-8e48-c568644b06b7" />

The DC gearmotors have a much higher maximum torque:

<img width="1345" height="723" alt="image" src="https://github.com/user-attachments/assets/57d25450-151e-4915-bc1c-cf131d595134" />

However, after closer inspection, these motors only supplied a continuous operating torque at a certain speed. We need a speed range.
Going over to the compact DC motors, torque-speed charts are provided. Selecting the weakest motor:

<img width="766" height="583" alt="image" src="https://github.com/user-attachments/assets/f5f28200-e626-4b3b-883e-3f9cff68420d" />

This motor is NOT appropriate. It cannot reach the required ~20RPM with a ~20lbf-in or ~315RPM. We need less torque and higher RPM.

<img width="1371" height="451" alt="image" src="https://github.com/user-attachments/assets/6f8295f2-1e04-412d-91ad-7b280a03c60d" />

This motor is the first out of the list that goes above 20RPM. So it fulfills that requirement. We now inspect the speed-torque curve.
## Motor Mount Bracket Housing Design

## Coupler

## Frame 

## FEA

## Bearing Mount Design

## Costs

## Lessons Learned

## Drawing
