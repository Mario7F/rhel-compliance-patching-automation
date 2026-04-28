
## Getting started with folders and file creation was my first goal 

<img width="1097" height="421" alt="Screenshot 2026-04-26 at 10 42 21 PM" src="https://github.com/user-attachments/assets/60f7cd96-290c-4fa5-8819-35fe256a2680" />

### After the file creation, I ssh'd into both of my host to retrieve the IP's to put into the inventory.yml 

<img width="1048" height="347" alt="Screenshot 2026-04-26 at 10 47 20 PM" src="https://github.com/user-attachments/assets/c627c66c-0273-4be2-8e2e-1cb8ce508668" />

### Once wrote into the yml, I ran ansible all -m ping to make sure they were reachable 

<img width="1063" height="569" alt="Screenshot 2026-04-26 at 10 58 26 PM" src="https://github.com/user-attachments/assets/712172df-e21d-4557-b00c-a7ea4209985c" />

### Running into the "unreachable error message" I ssh into each host to validate they were still up since I just retreived their IP (which later I remembered just consoling into them and not actually using the terminal to reach them) 

### Validated I was able to reach them via ssh and checked systemctl status sshd to look at the recent log history to figure out why I wasn't able to get in using ansible.

### Once I realized it was due to how to set up ansible.cfg, I went ahead and edited the way I would normally run the playbook by adding the flag -k -K which resolved the error message


<img width="1063" height="330" alt="Screenshot 2026-04-26 at 11 03 34 PM" src="https://github.com/user-attachments/assets/a906928d-34e2-4ca0-b784-65ef5c5dd97a" />

## Noticing one server was pinged but the other didn't show as unreachable was a sign that server two was nested under server one so I had to adjust the formatting in order for it to ping both

<img width="1086" height="273" alt="Screenshot 2026-04-26 at 11 08 47 PM" src="https://github.com/user-attachments/assets/62138a35-0e06-41e2-9f45-cb3c1fedf4e0" />

<img width="1052" height="311" alt="Screenshot 2026-04-26 at 11 10 57 PM" src="https://github.com/user-attachments/assets/ca2baca4-b06f-403c-a002-0f456539444f" />







