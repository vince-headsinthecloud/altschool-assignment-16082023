# Cloud Assignment by Valentine Madu on 16-08-2023
## Creating and Modifying Users and Groups Using the Linux Command Line Interface






### 1. Create a user
A new user named 'Vincent' was created by using the `useradd` CLI command. This was confirmed by running the `id vincent` command
![image](https://github.com/vince-headsinthecloud/altschool-assignment-16082023/assets/126173984/dd8a654d-99fb-452e-b72e-06c8f123f6b5)
![image](https://github.com/vince-headsinthecloud/altschool-assignment-16082023/assets/126173984/e28e70fe-2a6e-407b-bbf8-188d9b82cd41)



### 2. Set an expiry date of 2 weeks for Vincent
This was achieved by using the `usermod -e` command and was confirmed by using the `chage -l` command as seen below.
![image](https://github.com/vince-headsinthecloud/altschool-assignment-16082023/assets/126173984/4dceb443-8a7c-4e7e-9f5f-a739d2458622)

### 3. Prompt 'Vincent' to change password on login. 
The existing password for 'Vincent' was made to expire using the `passwd -e` command and was confirmed using `chage -l`. On next login, 'Vincent' was prompted to change password.
![image](https://github.com/vince-headsinthecloud/altschool-assignment-16082023/assets/126173984/eba7e63d-2f14-4150-bf10-cd3f6818e74a)
![image](https://github.com/vince-headsinthecloud/altschool-assignment-16082023/assets/126173984/38bcd56f-299f-4728-b2f2-499cbeb57503)

### 4. Attach 'Vincent' to 'Altschool' group.
This was done using the `usermod -a -G` command.
![image](https://github.com/vince-headsinthecloud/altschool-assignment-16082023/assets/126173984/542db5c3-9df6-4d58-8cb9-516ab934fa1f)

### 5. create another user without home directory
![image](https://github.com/vince-headsinthecloud/altschool-assignment-16082023/assets/126173984/06e04ad6-4f0b-4e2e-9933-c96b4e6e213e)







