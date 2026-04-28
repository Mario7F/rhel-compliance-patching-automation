


### The remediation part was by far the trickiest step in this effort - not only did I run into syntax issues, I was too busy debugging that I forgot to screenshot the process

### Below are a few things I did to figure out why I was running into the issue

### Basically my yaml formatting was off and the output didn't point to exact error however I was able to see there was a misspelling - Below I used a --syntax-check flag on they book during debugging and after

### Also a cat -n on the playbook to make sure the format was correct

<img width="1309" height="836" alt="Screenshot 2026-04-28 at 8 03 16 AM" src="https://github.com/user-attachments/assets/743357b4-1867-49e6-905f-a0ab6de35bf6" />


### The culprit was the ansible.builin.debug instead of ansible.builtin.debug which gave the error message, after corrected I was able to run the playbook successfully.

<img width="1402" height="381" alt="Screenshot 2026-04-28 at 8 12 12 AM" src="https://github.com/user-attachments/assets/8ff7c124-7ea0-4190-8bfd-cd3fbb37d5b1" />

------------------------------------------------------------------------------------------------------------------------------------------------------------------

<img width="1318" height="108" alt="Screenshot 2026-04-28 at 8 12 39 AM" src="https://github.com/user-attachments/assets/82c71c16-77cf-45fb-ac92-078d91b64b76" />

------------------------------------------------------------------------------------------------------------------------------------------------------------------

<img width="1353" height="853" alt="Screenshot 2026-04-28 at 8 13 33 AM" src="https://github.com/user-attachments/assets/16331422-2fad-46f5-ace9-984908a796ac" />
