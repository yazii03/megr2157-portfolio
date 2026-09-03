# A2 – Truss Stress Analysis

## Objective
Come up with a truss design and CAD model.

## Analyze

<img width="4032" height="1599" alt="IMG_1" src="https://github.com/user-attachments/assets/2ec056bf-fce6-4f1d-bdba-501b43420152" />

I began by coming up with a simple truss. I decided on this truss design because it is pretty simple and a common form of truss. It is only made up of triangles and has 5 joints. I labeled everything and added a joint E to connect the middle triangle. 

<img width="3356" height="1417" alt="IMG_2" src="https://github.com/user-attachments/assets/314fb768-4e84-4c53-993f-991e520b6f27" />

I found the length of the elements that did not have a length already specified. The truss has symmetry, if cut down the middle both sides will be the same. Therefore finding the length of C would equal the length of D. I labeled them and also labeled the reactionary forces. 

<img width="2346" height="3107" alt="IMG_3" src="https://github.com/user-attachments/assets/9927c2dc-5ab4-4a72-ab5f-8c192ddcfba8" />

After labeling everything that was needed and missing. I decided to go ahead and find the value of the reactionary forces. I used the equilibrium equations to find both AX and Ay. I then used the moment to find By. Since Ax was the only force in the x axis without any corresponding force it is equal to 0. 

<img width="2346" height="3107" alt="IMG_3" src="https://github.com/user-attachments/assets/c6d7c05e-67e7-4f1e-8c6e-95d95e94cc43" />

I then sketched the FBDs of all my joints including the reactionary forces in the diagrams. I did this in order to use the method of joints to solve for the internal forces. I did this step after finding the reactionary forces because i wanted to include them in the diagrams and be able to visualize the forces on the joints. 

<img width="3428" height="1556" alt="IMG_5" src="https://github.com/user-attachments/assets/52d500ff-2097-4def-ac86-470712b3435f" />

I decided to start with joint B. I thought this joint would be easier to start with because it has one of the reactionary forces and would allow me to find forces that i could use in joint C as well. Solving at joint B i was able to find Fbc and Fbe.

<img width="2965" height="2151" alt="IMG_6" src="https://github.com/user-attachments/assets/512cb3cf-3b9e-4b56-984d-8e12098930c6" />

I then decided to follow down the truss and solve for the internal forces at joint C. I believed it to be easier to solve two joints one one side since like i said the truss has symmetry having some forces equal one another. Solving for internal forces at joint C i was able to use Fbc to find Fce and Fcd.

<img width="2793" height="1526" alt="IMG_7" src="https://github.com/user-attachments/assets/89f7163a-ffaf-4dda-b1f1-f960fd614e23" />

I put all the forces that would equal one another together so i could have a chart to use having everything. A lot of the internal forces share the same internal force and show tension except for one. I calculated that  Fcd showed compression and was the only one that did not equal any other internal force on another element. 

<img width="3683" height="1550" alt="IMG_8" src="https://github.com/user-attachments/assets/7dbdbc1a-0a94-41e8-a068-48b31470338a" />

I began to work on finding the cross-sectional area of my truss. This is a list of the unknowns and knowns that i was given or calculated like the largest internal force. 

<img width="4032" height="1309" alt="IMG_9487" src="https://github.com/user-attachments/assets/87319326-8576-4ddc-abcc-ad5ae31c3dd1" />

I was able to find the minimum cross-sectional area using the information given to me. 

<img width="4007" height="1590" alt="IMG_9" src="https://github.com/user-attachments/assets/1a01a4fb-bd29-41fd-b05b-ec17524fc043" />

In order to find the weight of the truss i had to calculate the total length of the truss and  found it was 3.222m. I researched the density of A500 steel which is the metal used for the truss and found its density. I used my minimum cross-sectional area with the total length and density to find the weight of the truss. 

<img width="2770" height="2535" alt="IMG_10" src="https://github.com/user-attachments/assets/7bb799e3-d435-4fc8-9dd2-26e3f1e7de70" />

In order to find the shear in the pin with the most load. I made a list of all my knowns and unknowns to look back at when doing my calculations. I had to convert some knowns into other units so that it would match the units i was already using and wouldn't create a problem later on. I wasn't really sure how to find the shear on the pin so i looked at the notes and examples provided in the assignment and was able to find the cross-sectional area of the pin. 

<img width="4030" height="1667" alt="IMG_11" src="https://github.com/user-attachments/assets/55fe48d9-4a53-4d15-9bb1-a3341ca1d177" />

IN order to find the total weight of the pins in the truss i needed to give my pins a length. I decided to change my units to mm and grams because i wanted to keep the numbers small. I decided to make my pins 15mm in length. I had to change the units in the density given to match my new units. I multiplied the shear in the pin the density and my decided pin length and found the wight of each pin. I multiplied that by 5 since i have 5 pins in my truss and found the total wight of all the pins.

<img width="960" height="504" alt="Screenshot 2026-09-03 033213" src="https://github.com/user-attachments/assets/de0996a3-71ec-4777-814b-ef534329de9b" />

I began working on my truss in solid works. I gave myself two lines that intersected to help and decided to mark everything out first and make my pins to visualize the truss without adding in the lines yet. 

<img width="960" height="504" alt="Screenshot 2026-09-03 034646" src="https://github.com/user-attachments/assets/65ef675d-d68b-4a72-a594-c701482048d5" />

I then added the lines and connected my joints fully creating the sketch of my truss. 

<img width="960" height="504" alt="Screenshot 2026-09-03 042250" src="https://github.com/user-attachments/assets/7c3eb0c7-4ad7-439e-b909-7761bb745b6f" />

I offset the lines to fully cover the beams and have them be inside the elements like they would be connecting them in a truss. I added my measurements to show the length of the elements. I converted them all to mm to show it in a bigger scale. I couldnt turn it into a 3d model and i couldn't figure out why it wouldn't let me fix it or change it into one. I left it like that but will figure out how to fix it and update this once it is done. 





Engineering lesson learned-

I learned to really pay attention to detail when working on making a design. I learned new ways to calculate the area of a truss and its pins during this assignment as well and the shear in pins which i wasn't exactly sure how to do. It really helped me get a better understanding of how to go about it. 

  Likelihood of failure Modes in Truss Components

The expected failure in the elements experiencing compression is buckling. If the load becomes to much for the element it will start buckling and fail. On the other hand the elements that experience too much tension will start yielding and fail. The material used for this truss in A500 constructible steel which is a ductile material. A design change that could prevent these failures could be adding members where needed in order to prevent too much tension or compression on a single element. 

Pin connections

An expected failure of the pin in a truss is for it to snap or break which can be caused by an excess in shear load. if the pin experiences more load than it can take acting on it, it could snap in half. A modification that could be made is making the diameter of the pin bigger to allow it to hold more load. Making it a double shear pin could also help it prevent snapping and distribute the load. 

  Work cited
  
 AEP, EVstudio. “Structural Failures to Watch out for While Designing.” EVstudio, 3 Aug. 2017, evstudio.com/structural-failures-to-watch-out-for-while-designing/.
 
 Staff, Fire Engineering. “Construction Concerns: Truss Failure.” Fire Engineering: Firefighter Training and Fire Service News, Rescue, 30 Aug. 2024, www.fireengineering.com/fire-safety/construction-concerns-truss-failure/. 
 
 “7 Dowel Pin Shear Strength Facts – Load Formula & Failure Limits Guide.” Rajal Industries, 29 Apr. 2026, rajalindustries.com/dowel-pin-shear-strength-chart-load-formula-failure-limits-explained/. 

 

