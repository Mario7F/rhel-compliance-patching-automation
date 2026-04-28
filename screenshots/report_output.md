
## Creating a compliance report to display status of SELinux, firewall, auditd status 

<img width="1430" height="814" alt="Screenshot 2026-04-27 at 9 44 10 PM" src="https://github.com/user-attachments/assets/ea157725-d439-449a-85eb-1307979656b9" />

<img width="1343" height="839" alt="Screenshot 2026-04-27 at 9 44 24 PM" src="https://github.com/user-attachments/assets/6d31ab1b-f891-4956-90ff-412e42ecdaa0" />

<img width="1368" height="714" alt="Screenshot 2026-04-27 at 9 43 56 PM" src="https://github.com/user-attachments/assets/a78bfbf5-13fe-4fac-b75a-ba54c9031f88" />

## Playbook ran as expected however when I cat the txt file nothing is populated

<img width="1350" height="188" alt="Screenshot 2026-04-27 at 9 47 27 PM" src="https://github.com/user-attachments/assets/af1f9122-44ce-408a-903a-3ae8d8fff884" />

## Found the culprit in the playbook - I had to updated the lineinfile to "copy" 

<img width="1396" height="269" alt="Screenshot 2026-04-27 at 9 49 51 PM" src="https://github.com/user-attachments/assets/76b1de30-c201-4e0c-ab9c-5f60669abc91" />

## After rerunning playbook, only one server provided the report

<img width="1418" height="200" alt="Screenshot 2026-04-27 at 9 53 45 PM" src="https://github.com/user-attachments/assets/36b0533f-e1a8-42c7-aa20-8e52fdcfdd70" />

## Was not able to find a solution via ansible-doc so I used CHATGPT to figure out another solution to resolve the issue

<img width="1419" height="229" alt="Screenshot 2026-04-27 at 9 55 38 PM" src="https://github.com/user-attachments/assets/466b4082-5f1e-49cf-9c7d-c53413e1c5fc" />

## I documented this in my notes so I can utilize in future playbook creations - all is working as expected

<img width="1392" height="92" alt="Screenshot 2026-04-27 at 9 56 49 PM" src="https://github.com/user-attachments/assets/75b57582-9955-4011-aef5-50d1621333a7" />

<img width="1450" height="468" alt="Screenshot 2026-04-27 at 9 57 35 PM" src="https://github.com/user-attachments/assets/b052ac2b-8ae0-4075-bee9-6801ea0126bc" />









