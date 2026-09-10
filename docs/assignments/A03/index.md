# A3 – Parametric and FEA

## Objective- Designing a bars dimensions using axial deflection modeling. Using the design to determine the length of a bar with a circular cross section. As well as an introduction to using and understanding Finite Element Analysis. 

Part 1:

<img width="3414" height="1266" alt="IMG_1" src="https://github.com/user-attachments/assets/45dc146e-98e8-44b1-a0f4-d8d6daa93c09" />


I began by choosing the applied load on the bar as well as the diameter of the bar. I wrote down all the given values as well as my chosen values in a list to make sure I had everything correct. I was able to calculate the cross area of the bar using my chosen diameter.


<img width="2970" height="1350" alt="IMG_2" src="https://github.com/user-attachments/assets/f6e70576-9744-47fc-8deb-c59b7b27488c" />


I used the direct tension elongation equation from the Machinery's Handbook to calculate the length of the bar using my applied force, cross area, deflection and Youngs Modulus. 


<img width="960" height="504" alt="Screenshot 2026-09-09 004501" src="https://github.com/user-attachments/assets/0244765c-b441-4aa4-afab-cabb10684744" />


I used these parameters and entered them into Solidworks under equations. I used my parameters to derive the length once again but this time in the software itself.


<img width="960" height="504" alt="Screenshot 2026-09-09 004714" src="https://github.com/user-attachments/assets/6bd7f515-c304-486c-97f9-0dec77ecf9d1" />


With the parameters in Solidworks and the derived length I used them to create my bar with the correct dimensions and measurements in place. 


Part 2:


<img width="612" height="483" alt="Screenshot 2026-09-09 100322" src="https://github.com/user-attachments/assets/4db32d0c-1cec-41c5-a837-aa6cdf6d3b85" />


In order to begin working on conducting a FEA on the bar i began by assigning a material to the bar which is and Aluminum alloy. 


<img width="960" height="504" alt="Screenshot 2026-09-09 010557" src="https://github.com/user-attachments/assets/d1ad5d50-6e23-40bc-890c-974ec97b9c10" />


I then added the load on the right side of the bar as well as its support on the left side. 


<img width="960" height="504" alt="Screenshot 2026-09-09 010622" src="https://github.com/user-attachments/assets/200c6967-96af-4084-9bf4-c35667dd1d97" />


Before I ran my study to generate a deflection and von Misses Stress map i created a mesh that covered all of the bar. 


<img width="960" height="504" alt="Screenshot 2026-09-09 101159" src="https://github.com/user-attachments/assets/5d0a68bc-0194-46ce-87ea-f40d7e13eb3f" />

<img width="960" height="504" alt="Screenshot 2026-09-09 101147" src="https://github.com/user-attachments/assets/1b1e3cc8-df3b-4e89-8e8a-93252ce7f095" />


Once I ran the study my deflection and von Mises Stress maps were created and you could see the the stress along the bar as well as the deflection at different points along the bar. 


<img width="960" height="504" alt="Screenshot 2026-09-09 202259" src="https://github.com/user-attachments/assets/c39d3022-2847-420d-936a-d9f5b69782e6" />

<img width="3448" height="1325" alt="IMG_3" src="https://github.com/user-attachments/assets/10e8943e-5bbd-4341-8933-3032bf46d3cb" />


The map showed the maximum stress on my bar which is lower than the Sy factor of Aluminum 40,000 psi. Using the max stress from my map and the yield strength of Aluminum i was able to calculate my safety factor. 


Part 3:

a.

  
<img width="960" height="504" alt="Screenshot 2026-09-09 203303" src="https://github.com/user-attachments/assets/8c55b4b7-8315-4305-9123-90f9558929ae" />

<img width="4030" height="1512" alt="IMG_4" src="https://github.com/user-attachments/assets/6a72b35a-e91d-4420-be45-74605c90bce8" />


My deflection map showed me my max deflection on the bar. I used the value from my map and compared it to the deflection given of 0.009 in. I used both to calculate the percentage difference between the two which turned out to around 6%. There's isn't a significant difference between them but the difference is also not that small. I believe my hand calculations along with material property inputs could be the cause for them not being a little more of the same. I would trust 0.009 in more as a deflection for the design because it is a smaller value meaning there was a smaller change in the bar. This would mean the bar is more stable and stronger. 


b.


<img width="3707" height="1678" alt="IMG_6" src="https://github.com/user-attachments/assets/b1489eb7-a707-46ed-af82-76be1a344cdb" />


I calculated an estimate of the max stress at a hole on the left side of the bar if a pin where to be in it. I found the stress concentration factor Kt for a hole in a flat bar to be 2.0. I used the Kt and my max stress on the bar given to me by my von Mises stress map to do so. I found it to still pass my safety factor. 

Part 4. 

I learned to be a lot more careful with using solidworks and pay attention to the order in which I do things  when using it. I had to pay good attention to the numbers I was typing when plugging in my parameters because if I had missed a number the whole thing could end up being wrong. I also learned how to create a stress and deflection map on a piece which is something i hadnt done before. The total time spent on this assignment would be around 6 hours total. 


2157 Students 

Modifying Design Parameters:

For this step I kept the given Young's Modulus, and deflection I changed my force and my diameter which also changed my cross area for the bar. 

 My given are :
 E= 10.5*10^6 psi
 e= 0.009 in.

New values:

F= 350 lbf
d= .35 in
A= 0.0962 in^2

With the changes I decided to make to the parameters I believe that the length of the bar will decrease because not only did I decrease the load on the bar i also decreased the diameter which led the cross sectional area to decrease. If both are decreasing the length is bound to decrease as well. 


<img width="599" height="263" alt="Screenshot 2026-09-09 213507" src="https://github.com/user-attachments/assets/e5a8c5c1-28be-481e-9ac6-a840324e699d" />


I typed in my new values in Solidworks under equations to calculate the new length of my bar. The new length was calculated to be 25.98 in which coincides with my guess of the bars length decreasing due to my changes. 


My Solidworks File :


[A3_zip.zip](https://github.com/user-attachments/files/32035785/A3_zip.zip)




