## Streamlining SSH Configuration
![Image](https://i.ibb.co/zPtzyRT/Screen-Shot-2022-05-06-at-6-18-03-PM.png)

* The above image is the config file in the .ssh folder. It was edited through the terminal using the command `nano config`.

![Image](https://i.ibb.co/ZSxMGz0/Screen-Shot-2022-05-06-at-6-17-28-PM.png)

* The above image shows the command `ssh sven` being run. "sven" is the alias I set in the config file.

![Image](https://www.linkpicture.com/q/Screen-Shot-2022-05-15-at-4.48.43-PM.png)

* As you can see above, I created a random file, and used the `scp` command to copy it over to ieng6.

## Setup Github Access from ieng6

![Image](https://i.ibb.co/hCNj92s/Screen-Shot-2022-05-06-at-6-49-52-PM.png)

* From above, you can see the public key I added to GitHub.

![Image](https://i.ibb.co/JHcRGg9/Screen-Shot-2022-05-06-at-6-50-49-PM.png)

* Looking at the .ssh folder, you can see the private key id_rsa and the public key id_rsa.pub

![Image](https://i.ibb.co/ByKxQpp/Screen-Shot-2022-05-08-at-2-49-59-PM.png)

* This shows I was able to commit and push changes to a github repository in my ieng6 account. In this example, I simply added a file called hi.md to the repository. [Link to commit](https://github.com/SathyaVen/markdown-parser/commit/0907a07d1b8c34ee26d35df558354441b7a795dc)

## Copy Whole Directories with `scp -r`

![Image](https://i.ibb.co/VLSQRJF/Screen-Shot-2022-05-08-at-4-35-51-PM.png)

* First I used the `scp -r` command to copy the directory to my ieng6 account.

![Image](https://i.ibb.co/XZL4Jbx/Screen-Shot-2022-05-08-at-4-35-30-PM.png)

* Then I ran the program.

![Image](https://i.ibb.co/9c47PR7/Screen-Shot-2022-05-08-at-4-27-47-PM.png)

* This is the command I would use to do all of the commands in a single line.

