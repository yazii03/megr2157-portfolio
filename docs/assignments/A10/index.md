# A10 – Lead Screw Translating System

## Objective

The task was to assemble a quasi-tensile tester by designing a screw-drive crosshead and selecting the required components. The assignment puts stress on selecting components based on the required force applied, stresses caused and geometries affecting the overall behavior of the materials. We had to evaluate the cost of the parts selected as well.


## Lead Screw - Yazahira

1) In order to select my leadscrew I first have to find the minimum diameter needed for the leadscrew. I used the axial stress analysis equations to find the minimum diameter needed. We did end up choosing steel as the material and used the yield strength and friction factor for this material in order to solve for the values. 

   <img width="871" height="606" alt="image" src="https://github.com/user-attachments/assets/a5b5b9e6-8b75-49af-995c-00d7af011560" />

The determined minimum diameter is 0.1380in.


2) After finding the diameter I needed I followed by calculating the range of the rotational speed my leadscrew would have. I used the linear speed provided in order to find my range. 

   
<img width="814" height="517" alt="image" src="https://github.com/user-attachments/assets/ec102cf6-cb0e-4864-91c8-70d2c4ff7649" />

The determined range of rotational speed for the screw is 0.3937-19.685RPM.


3) Now i need to follow up by calculating the torque that would provide the load needed of 2kN. This would help me select my leadscrew. 
   

<img width="885" height="532" alt="image" src="https://github.com/user-attachments/assets/6391fbc2-7cf6-4d1b-9ba1-a35db46b18a6" />

The determine torque at this speed


6) After finishing  up all my calculations and finding all my missing values I was able to select my screw. Based on the minimum required height of 18 in. and my minimum diameter I decided to choose the acme leadscrew below made of carbon steel. I thought it'd be the best fit for the assignment. 


<img width="960" height="436" alt="Screenshot 2026-11-11 171830" src="https://github.com/user-attachments/assets/fcc72e62-cb8e-440b-bcde-d1204f3debd5" />



## Nut and Flange - Yazahira

In order to select the Nut/Flange for this assignment I had to the minimum amount of threads that'd be able to support the load required of 2kN. After finishing the calculations i choose the Nut Flange that i thought would be the best fit. 


<img width="472" height="323" alt="Screenshot 2026-11-11 173143" src="https://github.com/user-attachments/assets/de87cc28-de04-40b1-a928-5d1618dfb1f4" />


<img width="958" height="437" alt="Screenshot 2026-11-11 172810" src="https://github.com/user-attachments/assets/1cbe162d-16ba-4353-a196-08e982eb0aeb" />



## Crosshead - Milena
1) Size + Material: Simple Beam Stress

2) Size + Material: Deflection Analysis

3) Multiview Paper Sketch


<img width="455" height="201" alt="Screenshot 2026-11-11 180225" src="https://github.com/user-attachments/assets/8a92cbe6-8947-4cf8-aec4-0bbf0e5db1fd" />


## Costs - Milena
Table

---------------------------------------------------------------------------------------------------------------------------------------------------
| Item Number | Quantity           | Name               | Cost/Item          | Cost               | Purchase Link      |
|--------------------|--------------------|--------------------|--------------------|--------------------|--------------------|
|98935A911 |2 |Carbon Steel Acme Steel Screw| $6.95 |$13.90 |https://www.mcmaster.com/98935A911/ |
|97790A110 |2 |932 Bearing Bronze- Flange Nut |$170.60 |$341.2 |https://www.mcmaster.com/97790A110/
|804T38 |1 |T-Slot Framing System |$202.12 |$202.12 |https://www.grainger.com/product/80-20-T-Slot-Framing-System-15-Series-804T38 
|LC103B-200 |1 |Load Cell| $349.56| $349.56| https://www.digikey.com/en/products/detail/omega/LC103B-200/25641942?gclsrc=aw.ds&gad_source=1&gad_campaignid=20243136172&gbraid=0AAAAADrbLlgO0kpqYMPhThlLdTwOcFLcR&gclid=Cj0KCQiAnsvXBhCqARIsAHKgGNbBoN82Wys6nRpzejUwxvXapOkhnu5bYxU6HeHkMHgI7gQFWMUO5JcaAgmxEALw_wcB 
||||Total Cost|$906.78
---------------------------------------------------------------------------------------------------------------------------------



## CAD Model - Milena
During the CAD model design process, we reduced the scale of thre T-



<img width="950" height="485" alt="Screenshot 2026-11-11 130505" src="https://github.com/user-attachments/assets/7d4f72a9-30fe-416c-ad41-3107aa0e6c7f" />


<img width="950" height="485" alt="Screenshot 2026-11-11 130516" src="https://github.com/user-attachments/assets/8ddd9f37-246a-4b86-8029-5efd373c2274" />



## MEGR 2157 - FEA - Yazahira

For the FEA I  took the crosshead that was designed by Milena and added the load and proper fixed features on it. 


<img width="960" height="504" alt="Screenshot 2026-11-11 164231" src="https://github.com/user-attachments/assets/1ffe74d8-705d-430e-9c20-d945e19b3ea0" />


I created a medium coarse mesh to run the first FEA on this part. 


<img width="960" height="504" alt="Screenshot 2026-11-11 164442" src="https://github.com/user-attachments/assets/7f4d2d1f-4801-4610-b4a1-4d5549ba0494" />

After running my simulation these where the graphs provided for Von Misses stress and Deflection. Based on the the values derived the safety factor is 9.5.



<img width="960" height="504" alt="Screenshot 2026-11-11 164650" src="https://github.com/user-attachments/assets/6c58754a-7cc9-404c-b7f8-1d52104c1710" />


<img width="960" height="504" alt="Screenshot 2026-11-11 164719" src="https://github.com/user-attachments/assets/fa2b748e-f2bc-47a0-869d-e7fe6e23e9ab" />



I followed by running a second study this time with a finer mesh. Below are the graphs provided after running the study. The safety factor after this study is 2.4. 


<img width="960" height="504" alt="Screenshot 2026-11-11 165452" src="https://github.com/user-attachments/assets/b2a8a476-55bf-4b79-a0d8-6f02c0c7ac5f" />


<img width="960" height="504" alt="Screenshot 2026-11-11 165530" src="https://github.com/user-attachments/assets/4f2e74dc-fb38-4ec8-a931-ff0e8c8024e9" />


<img width="960" height="504" alt="Screenshot 2026-11-11 165538" src="https://github.com/user-attachments/assets/ffaea6bc-7d7b-421d-9d97-aaef74507d33" />


After calculating the values for convergence 

Stress = 1.18%

Displacement = 0.12%

SF = 1.19%

They are all below 7% which means they converged. 


Even though there was convergence I decided to make my piece thick from 1 in to 1.5 inches. I though this would change the max stress in the middle of the part. I did make sure that after this change the part still met the constrains required. 


I created a fine mesh to begin the simulation.


<img width="960" height="504" alt="Screenshot 2026-11-11 170017" src="https://github.com/user-attachments/assets/64299d17-402d-4053-887a-6270ba12ffce" />



After running the simulation these were my final graphs for stress and displacement. 



<img width="960" height="504" alt="Screenshot 2026-11-11 170053" src="https://github.com/user-attachments/assets/92ef460c-d7a3-4e23-9af7-292e2c6e7df2" />


<img width="960" height="504" alt="Screenshot 2026-11-11 170100" src="https://github.com/user-attachments/assets/e7abbeac-5795-4895-bc67-f9269ad3829d" />





## Lessons Learned - Yazahira

We learned a lot of important lessons with this assigment. The most important lesson we learned was how to properly distrubute the work load and work as a team to assemble everything. We also learned how to use axial stress analysis to find the diameter of our leadscrew and choose one that would align with our design. We learneed how to use thread bending stress analysis to choose a nut that wouldfit our leadscrew properly. Learning how to properly assemble all of these parts and make them work togther was also a big lesson and skill that we got to practice on since we havent done many assembly assignments. We spent a lot of time selecting a proper material for the crosshead and we learned how many aspects go into that selction such as loading force, longevity and availability. Finally we spent approximatly 15 hrs on this assigment as a whole. 



## Links to Assembly and Components

Crosshead-

[A10-Crosshead.zip](https://github.com/user-attachments/files/34715581/A10-Crosshead.zip)

Assembly- 

[A10_Assembly.zip](https://github.com/user-attachments/files/34715612/A10_Assembly.zip)
