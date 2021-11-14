# Honeypot Assignment
**Time spent: 11 hours spent in total

**Objective:** Create a honeynet using MHN-Admin. Present your findings as if you were requested to give a brief report of the current state of Internet security. Assume that your audience is a current employer who is questioning why the company should allocate anymore resources to the IT security team.

### MHN-Admin Deployment (Required)
**Summary:**  I used the GCP terminal to download and initialize all the required scripts/files/etc.... I just followed the Milestone steps until Milestone 3 where I had to use the admin panel to create new VMs and add honeypots to them.

### Dionaea Honeypot Deployment (Required)
**Summary:**  Dionaea honeypot is basically a way to retreive the malware that is coming through to the user. In other words it tracks and takes the malware coming from a network and traps it. 

![HoneyPot2](https://user-images.githubusercontent.com/73257917/141664600-0703ecd0-7264-4553-946f-c2d16bd1a12d.gif)


### Database Backup (Required) 
**Summary:** The json file that uploaded had all the infromation about the incoming attacks, their IPs and which honeypot trapped them. The RDBMS that MHN-Admin uses is probably SQL database.


Both the Gifs use the same method to initialize the VM and set up the honeypot. I skipped the downloading phase because it took up time and it made the gifs larger.
The ones that I used were
- 2 Dionaea
- 2 Amun
- 1 Cowrie

![HoneyPot1](https://user-images.githubusercontent.com/73257917/141664575-68c3e32a-225b-462b-a6f8-bc51100d94e7.gif)

Some of the Malware that I did find is by using virus total and pasting the Src IP. Both of the malwares were caught by Dionaea.
![Malware Part](https://user-images.githubusercontent.com/73257917/141664708-91942409-ea5e-4ceb-a147-34b958a2da52.gif)

Another one was from this IP where it found 4 Malwares. This one I just uploaded as a png instead of making a whole gif for it.
![Done 0](https://user-images.githubusercontent.com/73257917/141664812-2bed1b64-b01a-4dec-b80d-b98ba362ac8a.png)

Challenges Doing this: 
- The instructions can get confusing and most of the time I spent was trying to figure out why the code/scirpt that I was given was not working, even though I followed instructions precisely.
 

