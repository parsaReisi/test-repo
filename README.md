# Demo

command: git clone "https url in <>code section of you'r github repository"


.git folder(its hidden in dir you should type dir -h to be able to see it) actually stores all of the files that save your commits or your code changes over time. It has all of changes recorded in the history of the repository

to save the changes in .git folder, use the commands:

1. git status: all of the files that where updated or created or deleated, but havn't been saved in a commit yet.

2. before you can save the file to git you need to tell git to track the file to use that you need to use "git add ." command. the "." meanes track all the files that have not been tracked

3. to save: git commit -m "this is the message" -m "some description"

(message ideally should contain what and why of the commit you'r making.)

4. now we have saved the changes localy, so we need to push them to github.

5. inorder to be able to push to github you need to prove to github that you are the owner of the acount. so you have to connect your local machine to you'r github acount.

6. to do so you need to use ssh(Secure Shell, is a network protocol that provides a secure way to access and manage remote computers or servers over an unsecured network) keys:
6.1. ssh-keygen -t rsa -b 4096 -C "emailaddress"
6.2. search for the key you just generated
6.3. print the public key and copy it
6.4. paste it in a new ssh key in github
6.5. follow the instructions to let .git to know the secret key.

7. push

some discription !!
