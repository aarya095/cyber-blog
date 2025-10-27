Originally published on [Medium](https://medium.com/@aarya-sarfare/understanding-the-ls-and-cd-commands-01298521358a)

<h1>[Linux #4] Understanding the ls and cd commands</h1>

Disclaimer: This article documents my personal learning journey in cybersecurity. It is for educational purposes only and not professional advice or guidance for real-world systems. Content reflects my current understanding and may evolve as I learn more.

In the terminal, navigating the file system is something we do everyday, to access a certain file or directory in the system, further after going to a certain directory we want to see what all files/directories are in it. Learning to navigate and view the file system is essential for anyone learning Linux. Let’s get started,

<h2>ls (list directories)</h2>
Lists all the files and directories in the current directory.  
<br>
<img width="527" height="126" alt="image" src="https://github.com/user-attachments/assets/3a2f87b2-02f0-4b94-88b2-f9535a62af4f" />

We can also check the files/directories in a certain directory in the system via specifying the absolute path, as the example below,  
<br>
<img width="548" height="119" alt="image" src="https://github.com/user-attachments/assets/9aacad52-c976-4737-8107-5e2db54d8cde" />

The most commonly options I have used with ‘ls’ are -l and -a, (useful for CTFs).

`ls -l #Lists all the files and directories in a more detailed format`  

<br>
<img width="617" height="210" alt="image" src="https://github.com/user-attachments/assets/a44ea78a-cbb7-4238-a732-2ae198a4055d" />

`ls -a #Lists all the hidden files i.e. files starting with '.' operator.`  

<br>
<img width="518" height="112" alt="image" src="https://github.com/user-attachments/assets/5f9241e1-941a-4812-880f-08b28291feb5" />

Another amazing feature is of combining options, as the below example,

`ls -al #So we can get results of both -l and -a combined!`  

<br>
<img width="737" height="285" alt="image" src="https://github.com/user-attachments/assets/02324484-94c7-4651-951b-5ae326ffec0e" />

Note: The order of options doesn’t matter, as one can write ‘ls -la’ and it’ll give the same output.

<h2>cd (change directory)</h2>  

<br>
<img width="522" height="203" alt="image" src="https://github.com/user-attachments/assets/d63135e1-e8b5-4773-9f35-7e1d5bb50c6e" />

Firstly, there are two ways to change directories i.e. by Relative Path and Absolute Path.

In Relative Path, we change paths relative to our current directory, as in the example shown above, where we go from folder1 to sub_dir1 directory. Here, we tell where we want to go relative to the current directory (, a step up or down in the file system.)

In Absolute Path, we state the entire path starting from home (~) or root (/), for example,  

<br>
<img width="659" height="169" alt="image" src="https://github.com/user-attachments/assets/97acf16d-699c-42ef-82c5-c782caf94f7c" />

In the above example, we go from ~/folder1/sub_dir1 to ~/folder2/sub_dir2, it is very useful when wanting to teleport to a certain directory on the file system.

Below are essential shortcuts to navigate,

```bash
cd . #nothing happens, as we change the directory effectively to itself, but the dot operator itself is very important, so just keep that in mind
cd .. #Go one level up the file hierarchy
cd - #Go to the previous directory we were at
cd ~ #Go to the home directory
cd / #Go to the root directory
```
We have explored ls and cd command, If you have any doubts feel free to ask in the comments. Feedback or corrections are welcome.

Previous:[Starting with Linux Commands](https://github.com/aarya095/cyber-blog/blob/main/linux_series/%5BLinux%20%233%5D%20Starting%20with%20linux%20Commands.md) | Next: [Managing Files and Directories](https://github.com/aarya095/cyber-blog/blob/main/linux_series/%5BLinux%20%235%5D%20Managing%20Files%20and%20Directories.md)
