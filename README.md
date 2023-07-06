# Working Incidents and Incident Response- Brute Force Success (Windows)

![pt 1](https://github.com/garrick8jackson/Lab-9/assets/38325200/7ba99ac4-f2c4-47c7-84ff-083f3e1dad07)

Here after looking at the incidents dashboard for my windows virtual machines i assigned the owner, status, and severity of the incident.

![pt 2](https://github.com/garrick8jackson/Lab-9/assets/38325200/2be1dfcb-4547-4375-bd8e-34edcfe2e379)

Here I am viewing the full details of the incident i assigned to myself to see 
how many alerts were triggered and from what entities.

![pt 3](https://github.com/garrick8jackson/Lab-9/assets/38325200/071e23b4-10cc-4510-92f1-fb139ffd7f3b)

Viewing the log activity to see how or why the alerts were triggered for the incident

![pt 4](https://github.com/garrick8jackson/Lab-9/assets/38325200/4a041538-eda7-43a4-8e25-e12e537fb60b)

Checking the entities of the incident to get the full details on where and who successfully brute forced my windows virtual machine.

![pt 5](https://github.com/garrick8jackson/Lab-9/assets/38325200/19f4c5fd-31e2-485e-ae49-bc14550135d6)

![pt 6](https://github.com/garrick8jackson/Lab-9/assets/38325200/dbf4352d-c9f3-4cff-80ae-aa1321314672)

Investigating the incident I can see a diagram of my windows virtual machine, the attacker’s IP Address, and the brute force attempts alerted. 

![pt 7](https://github.com/garrick8jackson/Lab-9/assets/38325200/fd723054-81f9-4898-a641-a14c947aa1af)

After a thorough investigation I identified the incident as a false alert as the traffic that was alerted should not have been able to reach the virtual machine in the first place. In my notes I added the next steps I will take after closing out the incident.

![pt 8](https://github.com/garrick8jackson/Lab-9/assets/38325200/5140573d-987d-4225-b0ea-3f0101c15c63)

After closing out the incident I hardened the network security groups to deny any traffic unless it comes from the specified IP Address. 



