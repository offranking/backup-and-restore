# backup-and-restore
backup and restore file on a linus server using ansible


### to update your terminal "sudo apt update"

<img width="1109" height="400" alt="Screenshot 2025-09-26 at 3 48 40 pm" src="https://github.com/user-attachments/assets/ae644331-82a9-4e8c-a79d-6291d2bcf22f" />


### Now install your ansible by running "sudo apt install ansible -y"

<img width="718" height="110" alt="Screenshot 2025-09-26 at 3 49 16 pm" src="https://github.com/user-attachments/assets/893b3309-fa65-4c95-9200-fc21b2052e18" />

### run ansible -version
<img width="1050" height="182" alt="Screenshot 2025-09-26 at 3 49 43 pm" src="https://github.com/user-attachments/assets/1f0b39c0-9034-4bb2-9ce4-3922729c91b7" />

### run ssh-keygen
<img width="1018" height="421" alt="Screenshot 2025-09-26 at 3 50 10 pm" src="https://github.com/user-attachments/assets/6b7b68e5-7cd1-4d7b-bfe9-d232998375c0" />


### Open a back up file  run this command nano "backup.yml"

<img width="996" height="852" alt="Screenshot 2025-09-26 at 4 06 59 pm" src="https://github.com/user-attachments/assets/e4762e87-7d72-4e2a-937f-cfa217b77e91" />

### Open a back up file  run this command "nano restore.yml"


<img width="996" height="852" alt="Screenshot 2025-09-26 at 4 07 55 pm" src="https://github.com/user-attachments/assets/93545dbc-b489-4d63-a6e4-df2ad5aacff7" />

### run the backup playbook "ansible-playbook -i inventory.ini backup.yml"


<img width="1219" height="571" alt="Screenshot 2025-09-26 at 4 13 01 pm" src="https://github.com/user-attachments/assets/e0a15a92-74e5-4371-b5a7-ba09f273b6d3" />

### run the restore playbook "ansible-playbook -i inventory.ini restore.yml"

<img width="1160" height="334" alt="Screenshot 2025-09-26 at 4 13 29 pm" src="https://github.com/user-attachments/assets/49ce44d1-2929-424c-a286-68c67703205b" />

### verify the backup directory and files on the target server
<img width="1215" height="65" alt="Screenshot 2025-09-26 at 4 19 00 pm" src="https://github.com/user-attachments/assets/ac613c8a-dfcc-4ce4-b458-f6c007451f61" />

### verify the restore path in the original located on the target server
 
<img width="1304" height="66" alt="Screenshot 2025-09-26 at 4 20 52 pm" src="https://github.com/user-attachments/assets/32d52dd0-011c-4712-8352-48536abeda3f" />








