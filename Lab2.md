## Lab 02

- Name: Stephan Smith 
- Email: smith.3174@wright.edu

## Part 1 Answers

Command to SSH to AWS instance:
```
ssh -i C:\Users\Stephan\Documents\ceg2350.pem ubuntu@98.85.210.115
```

## Part 2 Answers

1. `chmod u+r bubbles.txt`
    - Means: Adds a permission to read for the user.
2. `chmod u=rw,g-w,o-x banana.cabana`
    - Means: allows the user to read and write, Removes write permission from the group and removes execute permission from others.
3. `chmod a=w snow.md`
    - Means: All users can write only.
4. `chmod 751 program`
    - Means: Users can read, write, and execute, Group can read and execute and Others execute.
5. `chmod -R ug+w share`
    - Means: user and group can write in share directory 

## Part 3 Answers

1. Command to create new user: useradd
2. Path to user's home directory: C:\home\usernameTheyHave
3. Evaluate if `ubuntu` can add files to user's home directory:
4. Command to switch to user: su
5. Command(s) to go to user's home directory: cd
6. Evaluate if user can add files to user's home directory: The user should have write permissions so they can add files to the home directory
7. Command to switch to `ubuntu`: sudo su ubuntu
8. Command to return to `ubuntu` home directory: cd ~ubuntu

## Part 4 Answers

For each, write the command used or answer the question posed.

1. Command to create group named `crew`:
2. Command(s) to add `ubuntu` & user to group `crew`:
3. Command to modify `share` to have group ownership of `crew`:
4. Command to switch to user:
5. Command to add file to `share`: 
6. Evaluate why these steps allowed the above action:

## Part 5 Answers

For each, write the command used or answer the question posed.

1. Command to create file using `sudo`: 
2. Evaluate (in plain text) the permission of the file: 
3. Provide a method to edit the file without modifying permissions: 
4. Command(s) to modify permissions:

## Citations

To add citations, provide the site and a summary of what it assisted you with.  If generative AI was used, include which generative AI system was used and what prompt(s) you fed it.

