# Lab 4

## Q.1: List the user commands and redirect the output to `/tmp/commands.list`?

![question 1](./imgs/lab4-1.png)

## Q.2: Count the number of user commands?

![question 2 answer](./imgs/lab4-2.png)

## Q.3: Get all the users names whose first character in their login is `g`?

![question 3 answer](./imgs/lab4-3.png)

## Q.4: Get the logins name and full names (comment) of logins starts with `g`?

![question 4 answer](./imgs/lab4-4.png)

## Q.5: Save the output of the last command sorted by their full names in a file?

![questioni 5 answer](./imgs/lab4-5.png)

## Q.6: Write the next 2 commands and save their outpu and error in 2 different files and sent the to background?

1. **Search for all files on the system that named `.bash_profile`**

    ![question 6 part 1 answer](./imgs/lab4-6-a.png)

1. **Sort the output of `ls` command on `/` recursively?**

    ![question 6 part 2 answer](./imgs/lab4-6-b.png)

## Q.7: Display the number of users who is logged not to the system?

![question 7 answer](./imgs/lab4-7.png)

## Q.8: Display lines 7 to line 10 of `/etc/passwd` file?

![question 8 answer](./imgs/lab4-8.png)

## Q.9: What happens if you execute

1. **`cat filename1 | cat filename2`**

    ![question 9 part 1](./imgs/lab4-9-a.png)

    * the output of the first command is discarded and the second command output is printed to the screen

1. **`ls | rm`**

    ![question 9 part 2](./imgs/lab4-9-b.png)

    * rm needs arguments to operate and doesnt read from stdout

1. **`ls /etc/passwd | wc -l`**

    ![question 9 part 3 (last part) answer](./imgs/lab4-9-c.png)

    * 2nd command will print the number of lines results from 1st command whch will be 1 line

## Q.10: Issue the command sleep 100

![question 10 answer](./imgs/lab4-10.png)

## Q.11: Stop the last command?

![question 11 answer](./imgs/lab4-11.png)

## Q.12: Resume the last command in the background?

![question 12 answer](./imgs/lab4-12.png)

## Q.13: Issue the jobs command and see its output?

![question 13 answer](./imgs/lab4-13.png)

## Q.14: Send the sleep command to the foreground and send it again to the background?

![question 14 answer](./imgs/lab4-14.png)

## Q.15: Kill the sleep command?

![question 15 answer](./imgs/lab4-15.png)

## Q.16: Display your processes onle?

![question 16 answer](./imgs/lab4-16.png)

## Q.17: Display all processes except yours?

![question 17 answer](./imgs/lab4-17.png)

## Q.18: Use the `pgrep` command to list your processes only?

![question 18 answer](./imgs/lab4-18.png)

## Q.19: Kill your processes only?

![question 19 answer](./imgs/lab4-19.png)
