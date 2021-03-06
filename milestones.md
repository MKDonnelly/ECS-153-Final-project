# ECS 153 Group Project Milestones

For everyone in the group include one sentence on each of these:  
	1. What you did last week.  
	2. What you plan to do this week.  
	3. Anything you are stuck on.  
Also include links to any PRs you committed or design docs you wrote.

### Final Presentation 

https://docs.google.com/presentation/d/1m-L4UyamrVWhJimGO6wXxyu8sKUGd8Na68ly7h_1W2o/edit?usp=sharing

### Weekly Meeting Notes

https://docs.google.com/document/d/1lMMOIgBwF_SALd7GjLDgtXYJT7MnasdrnKQc54uMntg/edit?usp=sharing

## Week of May 18th

### Video
   https://youtu.be/nQ-TIus6fSo

### Weekly Summary for Group Members

- Matthew Donnelly
	1. A few commits to milestones.md.  I finished most of my part early on since it's the first piece that needed to get done.  At this point, I am just in maintenance mode if any problems come up with the networking code.
	2. Start thinking about the final project, presentation, video, etc.
	3. Nothing  

- Jose Antonio Alvarez Ocete  
	1. Finished onion routing for the conversation protocol. Will be easily reused in the Dialing protocol aswell. The API given in TorzelaUtils.py should be bug-free and easy to use for everyone.  
	2. Implement the mixnets as a priority. If time allows it, I'll also implement noise addition before the final presentation.  
	3. Nothing.  
	**Commits**:  
	https://github.com/Ocete/ECS-153-Final-project/commit/e91e5555d3bd2d1f6f5ab17b3c294639f1529378  
	https://github.com/Ocete/ECS-153-Final-project/commit/3d0bf11cd70658424483d02b9ca6dd4f7967b762  
	https://github.com/Ocete/ECS-153-Final-project/commit/8ecf6319a67fe5e93af9444845ad431eb5a85444  
	https://github.com/Ocete/ECS-153-Final-project/commit/5cf9cda033156e0b23b013db4a56ecf914fa8c2b  
	https://github.com/Ocete/ECS-153-Final-project/commit/8814c16f3aff74f5542fa59addeaeb992dd49a29  

- Edric Tom  
	1.  Finished a general framework of the server rounds. Completed the Milestone 3 video. Worked to 95% of total completion on the Dead Drops subsystem design doc, filling in my work from this week.         
	2.  Finish implementing the server rounds. If we can send messages between more than one client, then implement message matching.     
	3.  Currently stuck on 3 things: forcing users to send messages only within a server round, retrieving a shared key between two clients in order to calculate the new dead drop location after the end of a round, and message matching. My portion of the project does not have extensive coding, so most of the time is being spent trying to figure out how to implement everything correctly, ensuring that there are no bugs with the network code and nothing breaks as a result of my code.            
	**Commits**:         
	https://github.com/Ocete/ECS-153-Final-project/commit/15d6e785f5c08bbc907abaaf205e48c9f414a7a4          
	https://github.com/Ocete/ECS-153-Final-project/commit/f91466709972961900813a481fdbe3bd0da8886a           
	**Design Docs**:          
	https://docs.google.com/document/d/1UwTi2pzKUIhbZcCzO_i3td9yvJVwlYcYBza1qwFD8DY/edit?usp=sharing          

- Skyler Bala  
	1. Getting up to speed w/ codebase  
	2. Beginning of implementation of dialing protocol (protocol used to initiate conversations)  
	3. AR: Refactoring of end-to-end test to use the dialing protocol w/ invitation dead drop instances to initiate conversations  


## Week of May 11th

### Video

https://youtu.be/57an9dxj568

### Weekly Summary for Group Members
- Matthew Donnelly  
	1. Pushed roughly 500 lines of networking code. This is a significant portion of the networking subsystem. Also made 3 minute video for project overview and networking subsystem design doc.
	2. I have already finished most of what I need to do in this project, so at this point I am mainly in maintenance mode for the networking subsystem and helping my group members as needed.
	3. None  
	**PRs**:  
		https://github.com/Ocete/ECS-153-Final-project/commit/2cf0ec6b185240c0d70ed2b7a00f1fe4947b1d98
		https://github.com/Ocete/ECS-153-Final-project/commit/2ad150037b52b7a376514ad3bce240fd526dbcd2
		https://github.com/Ocete/ECS-153-Final-project/commit/a8af6d5fea6a8d15c0aca721bc86f4cd854be7fb
		https://github.com/Ocete/ECS-153-Final-project/commit/56c90df5da0ba4f69aef4563e7d393ee5c880413
		https://github.com/Ocete/ECS-153-Final-project/commit/3307cac28d91cf767b217e97bac6a7890aeaaaf8
		https://github.com/Ocete/ECS-153-Final-project/commit/e7ca1472099a8696272843d6957b0e8bcb1bcb14
		https://github.com/Ocete/ECS-153-Final-project/commit/918f3b4e058612e2f1b88deed913459a0dfb7a0b
		https://github.com/Ocete/ECS-153-Final-project/commit/fcf7bd9907f55f8e300eb0f34f7e41c5f26c4772  
  **DDs:**
		https://docs.google.com/document/d/1ahEHM-SRMf0zXW8gQfC6h4ikLVPCOtSuqnsOtEQ36Nk/edit?usp=sharing  

- Jose Antonio Alvarez Ocete  
	1. Working on the onion routing section for the client.
	2. Finish onion routing and mixnet. The noise addition will be also added if I have the time.
	3. Bytes/strings conversions in python is giving me some headaches. Not sure if this is because the encryption is wrong so I've been adding some basic tests to make sure those functionalities are okay.  
	**PRs:**  
		https://github.com/Ocete/ECS-153-Final-project/commit/f24694897a056ca33c324be078197272de6202c4  
		https://github.com/Ocete/ECS-153-Final-project/commit/29d6f8555d167bb7bdf47d470e021a764946c9af  
  **DDs (forgot to link them last week):**
		https://docs.google.com/document/d/1VZZLnERFplL6Zhgi-mZC8WDIzLizYSsjkA2ecijUYr0/edit#heading=h.iy904ins94pq
		https://docs.google.com/document/d/1JHVycZ2zotkthxrbSYLup1sxdetJZ5CLNzX9JL5hSAc/edit#heading=h.iy904ins94pq

- Edric Tom  
	1. Began implementing the dead drop subsystem, halfway done with dead drop design doc, and started implementing the server rounds.  
	2. Finish implementing the dead drop subsystem and server rounds, in addition to completing the design doc.   
	3. Translating the Vuvuzela code from Go to Python is giving me minor issues, as I'm only familiar with the basics of Python. Understanding how the code is written for each subsystem and how they interface with each other is also taking some time.  
	**PRs:**  
		https://github.com/Ocete/ECS-153-Final-project/commit/a669d31aa2b1d1e880759695da4be1c44dc9044f    
		https://github.com/Ocete/ECS-153-Final-project/commit/67afbd680fac03cec4491832e58c55876c902df0      
 	**DDs:**
		https://docs.google.com/document/d/1UwTi2pzKUIhbZcCzO_i3td9yvJVwlYcYBza1qwFD8DY/edit?usp=sharing

- Skyler Bala  
	(In case he shows up...)


## Week of May 4th

### Video Overview of Project

https://www.youtube.com/watch?v=GLXdrHr1E7A

### Weekly Summary for Group Members

- Matthew Donnelly  
	1. Initial work on networking code  
	2. Continue to refine network code  
	3. Nothing  
	**PRs**:  
		https://github.com/Ocete/ECS-153-Final-project/commit/6f4f1aa57c9cb7072c28b70ed487c0569a2f45f9  
		https://github.com/Ocete/ECS-153-Final-project/commit/d1fa714e9d75e36d150b8850c4d76a7f3b14dc7c  
		https://github.com/Ocete/ECS-153-Final-project/commit/52119700760c94db97852cf910714a635f21e178  

- Jose Antonio Alvarez Ocete  
	1. Wrote Conversation Protocol Subsystem design doc and General Overview design doc.  
	2. Complete Conversational Protocol Subsystem to work as Vuvuzela.  
	3. How to implement the recovery of the system when a server dies without giving away information of which users where connected to which dead drop.

- Edric Tom  
	1. Wrote initial version of the project proposal, with the others editing and changing it as they see fit  
	2. Begin studying and mapping out code for the dead drops, start writing code if ready  
	3. Nothing  

- Skyler Bala  
