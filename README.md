# Linux--List
List of Commands for all 
USER  MANAGEMENT  LINUX  COMMANDS

1. useradd username
Creates a new user account.

2. useradd -m username
Creates a new user with a home directory.

3. useradd -d /custom/home username
Specifies a custom home directory for the user.

4. useradd -s /bin/zsh username
Assigns a specific shell (e.g., ZSH) to the user.

5. useradd -u 1050 username
Creates the user with a specific user ID.

6. useradd -g developers username
Sets the primary group for the user.

7. useradd -G wheel,audio username
Adds the user to additional groups.

8. useradd -c "Full Name" username
Sets a comment (usually full name) for the user.

9. useradd -e 2025-12-31 username
Sets an account expiration date.

10. useradd -f 7 username
Sets the number of days after password expiry until account is disabled.

11. passwd username
Sets or changes the password for a user.

12. passwd -l username
Locks a user account.

13. passwd -u username
Unlocks a locked user account.

14. usermod -l newname oldname
Changes a username.

15. usermod -d /new/home -m username
Changes and moves the user's home directory.

16. usermod -s /bin/bash username
Changes the user’s default shell.

17. usermod -aG sudo username
Adds the user to the sudo group (append mode).

18. usermod -e 2025-01-01 username
Sets the expiration date for the user account.

19. usermod -L username
Locks the user’s account.

20. usermod -U username
Unlocks the user’s account.

21. deluser username
Deletes a user from the system (Debian-based systems).

22. userdel username
Deletes a user account (Red Hat-based systems).

23. userdel -r username
Deletes the user account and their home directory.

24. chage -l username
Lists password aging information.

25. chage -E 2025-12-31 username
Sets account expiration date.

26. chage -M 90 username
Sets maximum days between password changes.

27. chage -m 7 username
Sets minimum days between password changes.

28. chage -W 14 username
Sets the number of days before password expiration to warn the user.

29. id username
Displays the UID, GID, and groups for a user.

30. groups username
Shows the groups a user belongs to.
