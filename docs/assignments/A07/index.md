# A7 – FEA on Bracket 

## Objective

Use FEA to improve brackets design. 

Ensure high stiffness strength and lightweight optimization in design. 

Refine the bracket geometry based on FEA results to enhance performance.

Identify max stress, displacement, and safety factors.

Document the entire process. 


Bracket:

For this assignment I used the Bracket CAD model I made for my past assignment.


Inner Loop Design 1:


Before I started to do anything I began by making sure i had a material set for my model. 


<img width="612" height="483" alt="Screenshot 2026-10-16 194315" src="https://github.com/user-attachments/assets/46596f83-8a3d-4233-be61-25b024d9547d" />


Once I made sure my material was set. I started a simulation on my model. I added the fixed featured and the load on it. I also created a high coarse mesh on my model before running the simulation. 


<img width="950" height="500" alt="Screenshot 2026-10-16 193509" src="https://github.com/user-attachments/assets/52c6c508-80ba-4dff-baa7-2af06f48a69f" />



When I ran the simulation these were resulting Stress, displacement, and strain graphs. 


<img width="1414" height="2000" alt="Add a subheading" src="https://github.com/user-attachments/assets/05fb0b0f-3ca1-4204-bc14-7be162ebc7e4" />


I then created another mesh but this time the mesh was right in between a coarse and fine mesh. 


<img width="950" height="500" alt="Screenshot 2026-10-16 193317" src="https://github.com/user-attachments/assets/a72171b8-752c-436a-a54f-df79c425e672" />


I ran the simulation again and these where the resulting graphs. 


<img width="1150" height="1171" alt="medium design 1" src="https://github.com/user-attachments/assets/6ecd0430-dee3-4faa-8349-d64ec131ebac" />


After running the simulation I tested the convergence between the results. They were very far off the 7% needed for convergence so I ran another simulation with highly fine mesh.

<img width="219" height="98" alt="Screenshot 2026-10-17 224117" src="https://github.com/user-attachments/assets/b059355f-26e6-47ff-bfd6-bce215a27337" />

These where the resulting stress and displacement graphs of the simulation with
the fine mesh. 

<img width="1414" height="2000" alt="Add a subheading (1)" src="https://github.com/user-attachments/assets/6a68c8de-0757-4f2e-8d00-e103fb64e130" />

I calculated the the difference between the test 2 and 3 but the results showed no convergence again. 

<img width="235" height="107" alt="Screenshot 2026-10-17 224128" src="https://github.com/user-attachments/assets/b1b9e15e-bdfa-4556-86a3-a23b5337e7bf" />


Chart with values:

<img width="486" height="140" alt="Screenshot 2026-10-17 231649" src="https://github.com/user-attachments/assets/8680c76a-5ffd-4e7c-a0fa-fc1c6f0dbfa3" />


Second loop: Design Optimization. 

I decided to make part C of the bracket thicker since the max stress was happening on that part. This was the new design. 


<img width="950" height="500" alt="Screenshot 2026-10-16 203420" src="https://github.com/user-attachments/assets/943bf97d-6af4-4829-982e-efabbaa30747" />


 I added the load and the fixed features on the bracket and created a coarse mesh on the bracket.
 
 <img width="950" height="500" alt="Screenshot 2026-10-16 203715" src="https://github.com/user-attachments/assets/89f19c93-7579-4bd6-a015-0bff176382d4" />

<img width="950" height="500" alt="Screenshot 2026-10-16 203739" src="https://github.com/user-attachments/assets/31c99e69-67db-4205-b722-da1a1a0ca6ab" />

<img width="950" height="500" alt="Screenshot 2026-10-16 204341" src="https://github.com/user-attachments/assets/3c35470e-6adf-4fbd-8269-8e0be2aa8a2f" />


I ran the simulation and these were the graphs that were created. 


<img width="1414" height="2000" alt="coarse design 2" src="https://github.com/user-attachments/assets/48a97c48-9997-403c-98c8-8537c9d1f553" />


I created another mesh once again in between coarse and fine on the bracket. 


<img width="950" height="500" alt="Screenshot 2026-10-16 213353" src="https://github.com/user-attachments/assets/9c9aa7bc-4b99-472e-8b4e-ff69488f5a37" />


I ran the simulation these were the resulting graphs. 


<img width="1414" height="2000" alt="medium design 2" src="https://github.com/user-attachments/assets/3c600bdd-5cf0-4034-b51e-404c463fee90" />


 I tested the convergence on the first between the first and second simulation and these were my calculations. The results were not near the 7% needed so I ran another simulation with a finer mesh.
 
 
 <img width="210" height="92" alt="Screenshot 2026-10-17 230859" src="https://github.com/user-attachments/assets/fff8e703-e3f6-479a-9dca-b5650751bf73" />


<img width="950" height="500" alt="Screenshot 2026-10-16 215012" src="https://github.com/user-attachments/assets/4137e21d-3162-41b5-856e-59c88211660d" />


After running the simulation these were the resulting graphs. 


<img width="1414" height="2000" alt="fine design 2" src="https://github.com/user-attachments/assets/adf4b4ac-78f2-42d3-a4c5-c088bb2c24e2" />


After testing the convergence these were the results. Meaning they did not converge. 

<img width="231" height="103" alt="Screenshot 2026-10-17 230914" src="https://github.com/user-attachments/assets/6ac6473e-6968-419d-b437-1c54295dec32" />


Chart with values:

<img width="491" height="142" alt="Screenshot 2026-10-17 231635" src="https://github.com/user-attachments/assets/34739f76-bcc9-44dc-be85-fc6c8e960bbc" />


Third loop: Design optimization


I decided to increase the thickness at the top of the bracket instead this time and take some material off of part B as well as rounding of the edges in the bracket to try and optimize the design. I followed by starting a simulation and created a high coarse mesh on the bracket. 


<img width="950" height="500" alt="Screenshot 2026-10-16 222105" src="https://github.com/user-attachments/assets/86cd948d-ce61-431f-baec-5d80b248c2c1" />

<img width="950" height="500" alt="Screenshot 2026-10-16 222114" src="https://github.com/user-attachments/assets/02e97c5d-9a55-4ad4-af5a-6c0de1b7de33" />

<img width="950" height="500" alt="Screenshot 2026-10-16 222152" src="https://github.com/user-attachments/assets/5dcc5ab0-0743-4a39-a738-b8b61b1f8539" />


After running the simulation these were my resulting graphs. 


<img width="1414" height="2000" alt="coarse design 3" src="https://github.com/user-attachments/assets/a874946a-54ad-4b97-9635-2f141d230965" />


I then created another simulation but this time with a medium coarse mesh and ran the simulation again. 


<img width="950" height="500" alt="Screenshot 2026-10-16 222852" src="https://github.com/user-attachments/assets/45a9da3a-0836-4dc8-be27-562f3e7f0733" />

These were my resulting graphs. 


<img width="1414" height="2000" alt="medium design 3" src="https://github.com/user-attachments/assets/b62a6ed5-39c0-4b32-98bc-bc03a1b3e1de" />


I tested the convergence but the results showed there was no convergence since the results weren't near 7%. 

<img width="220" height="95" alt="Screenshot 2026-10-17 234030" src="https://github.com/user-attachments/assets/f1131b9f-0674-4052-a0e2-16c9150c2a24" />


Since there was convergence i ran another simulation but this time with a fine mesh. 


<img width="950" height="500" alt="Screenshot 2026-10-16 224232" src="https://github.com/user-attachments/assets/0c89c96b-a5e7-42fc-b2ef-1db940508dd2" />


I ran the simulation  and these were the resulting graphs. 



<img width="1414" height="2000" alt="fine design 3" src="https://github.com/user-attachments/assets/aa9ef122-3dc5-4989-930e-a2fa88297954" />


I tested the convergence and my results showed there was no convergence once again. 


<img width="229" height="100" alt="Screenshot 2026-10-17 234039" src="https://github.com/user-attachments/assets/727d6a7e-7bbc-4b80-a65e-b46bd6edfa05" />


This is the chart with the values: 

<img width="492" height="140" alt="Screenshot 2026-10-17 234721" src="https://github.com/user-attachments/assets/40eaa9d2-b7dc-43dd-ac5e-784a40cd5d58" />


This is the final design after the 3 inner loops and change in geometry of the model.


<img width="950" height="500" alt="Screenshot 2026-10-16 221832" src="https://github.com/user-attachments/assets/94ec597e-8e88-43b2-aaea-3eb631e2d993" />


Reflection: 


I learned how to to work the FEA a lot better. I got a lot pf practice using it during this assignment and it helped me learn more amount how to use it and how changing just a small aspect of my model could affect things like the stress, displacement, and strain by a lot. I also learned how the finer the mesh in a simulation helps get more accurate results in the graphs during an FEA so it'd be best to use fine mesh for simulations. I spent around 3-4 hrs completing this assignment. 












































