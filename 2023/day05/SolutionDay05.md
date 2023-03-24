# Day 5 Task: Advanced Linux Shell Scripting for DevOps Engineers with User management

### Tasks
1) You have to do the same using Shell Script i.e using either Loops or command with start day and end day variables using arguments.
   
   ![Q1 nano](https://user-images.githubusercontent.com/77112379/227472881-b1f2474c-0d42-4797-a239-d830f6ab50cb.jpg)

   ![Q1](https://user-images.githubusercontent.com/77112379/227472985-7d4fce1f-92ea-4b72-8b88-942724d28d14.jpg)

2) Create a Script to backup all your work done till now.
   
   ![Q2 nano](https://user-images.githubusercontent.com/77112379/227473406-be8af3e9-d07e-4121-9184-40673dda1319.jpg)

   ![Q2](https://user-images.githubusercontent.com/77112379/227473600-960652e6-68b1-45b5-9279-4f8defa9df0b.jpg)

3) Cron and Crontab to automate backup script.
   
   Cron is the system's main scheduler for running jobs or tasks unattended.
   A command called crontab allows the user to submit, edit or delete entries to cron.
   A crontab file is a user file that holds the scheduling information.
   
   Below is the syntax of crontab job definition :
   
   ![crontab scheduling](https://user-images.githubusercontent.com/77112379/227475138-d2124eaf-e280-4c2d-8d2f-0982b488f085.jpg)
   
   Below is the crontab job definition of backup.sh script created in Task 2 :
   
   ![Q3](https://user-images.githubusercontent.com/77112379/227475747-5d5fa9b2-cef8-40d7-a52f-dee0e528d1a2.jpg)
   
   0 : The minute when the command should run.
   
   0 : the hour when the command should run.
   
   1 : This number denotes the date of the month when the command will run.
   
   ![Q3 shell](https://user-images.githubusercontent.com/77112379/227475823-b345013e-92dd-4fdf-a3e7-993184fabc15.jpg)
   
4) Read about User Management.
   
   In Linux, user management involves creating, modifying, and deleting user accounts and groups. Here are some commonly used commands for user management in Linux:

    useradd: The "useradd" command is used to create a new user account.

    passwd: The "passwd" command is used to set or change a user's password.

    Here are some common options for the "passwd" command:

        "-l": Lock the user's account.

        "-u": Unlock the user's account.

        "-d": Remove the user's password.
        
   The ID 0 is assigned to the root user and the IDs 1 to 999 (both inclusive) are assigned to the system users and hence the ids for local user begins from 1000 onwards.

5) Create 2 users and just display their Usernames.
   
   Creating new users:
   
   ![Q5 a](https://user-images.githubusercontent.com/77112379/227478787-29be8719-2dce-46e1-aa4e-688e717a0eba.jpg)
   
   All user information is stored in /etc/passwd. To display all the users we use cat command.
   
   ![Q5 b](https://user-images.githubusercontent.com/77112379/227478801-1a526e71-7ac1-45e9-a1f4-c798d1bda249.jpg)
   
   All 1003 users are listed but below is the screenshot of only the ones we need.
   
   ![Q5 c](https://user-images.githubusercontent.com/77112379/227478821-44bf6bc1-bfbc-4ce0-9ead-9b0d0dc46eb3.jpg)

  ### READY FOR DAY 06
  
