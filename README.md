# OPEN-SOURCE-EX-3

#### NAME: Jayasree R
#### REG NO: 212223040074
#### DEPT: CSE

## AIM:
To create a group named admin, add users harry and natasha to the group as secondary members, create a user sarah without interactive shell access, and set passwords for all three users in Red Hat Enterprise Linux.

## ALGORITHM:
Step 1:
Start the Terminal. Open the terminal in the Red Hat Linux environment with administrative privileges.

Step 2:
Create a New Group. Create a group named admin to manage administrative users.

Step 3:
Create User Accounts with Group Assignments. Add a user named harry and make admin his secondary group. Add another user named natasha with admin as her secondary group as well.

Step 4:
Create a User Without Shell Access. Create a user named sarah who should not have access to an interactive shell (assign /sbin/nologin as the shell). She should not be a member of the admin group.

Step 5
Assign Passwords to All Users. Set the password redhat for users harry, natasha, and sarah.

Step 6:
Verify Group Memberships. Display the groups of each user to confirm the correct group assignments.

Step 7:
Verify Non-Interactive Shell Access. Check the user details of sarah in the /etc/passwd file to confirm that the shell is set to /sbin/nologin.

## OUTPUT:

<img width="907" height="604" alt="image" src="https://github.com/user-attachments/assets/492e2de7-e71f-4649-a7a0-09d451299159" />


## RESULT:
Thus, the users, groups, and memberships were successfully created and verified in Red Hat Enterprise Linux using appropriate administrative commands.


