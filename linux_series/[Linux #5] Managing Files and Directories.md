Originally published on [Medium](https://medium.com/@aarya-sarfare/linux-4-managing-files-and-directories-a88786afaf79)

<h1>[Linux #5] Managing Files and Directories</h1>

Disclaimer: This article documents my personal learning journey in cybersecurity. It is for educational purposes only and not professional advice or guidance for real-world systems. Content reflects my current understanding and may evolve as I learn more.

I am going to cover another set of essential commands in linux in the following article.

<h2>1. touch</h2>
We use touch to create files. The command is very simple and useful. Refer to the below example:
<br>
<img width="487" height="117" alt="image" src="https://github.com/user-attachments/assets/030c1ec0-fc15-44ce-8204-c8ce5e632185" />

We can also create multiple files in the same command, for example,
<br>
<img width="597" height="132" alt="image" src="https://github.com/user-attachments/assets/3d553af4-456c-4d65-8a38-94e19bcf7e2d" />

Another cool trick one can use with touch, is creating ’n’ number of files, by using the following method:
<br>
<img width="572" height="158" alt="image" src="https://github.com/user-attachments/assets/0ce5ea39-72e7-4196-9af4-97ef072d319c" />

<h2>2. file</h2>

Extremely useful command during ctfs to know which type of file has been presented to us.
<br>
<img width="752" height="169" alt="image" src="https://github.com/user-attachments/assets/281a4f2f-949f-40e3-84c6-f644d5834fc5" />

<h2>3. mkdir</h2>

Used to make directories or multiple directories at once. Similar to touch, mkdir can be used to create multiple sub-directories in one command.
<br>
<img width="564" height="532" alt="image" src="https://github.com/user-attachments/assets/0b309244-dcdf-4c02-98b8-f4b18470a123" />

-p option is used to create parent directories
<h2>4. cp</h2>

Used to copy a file or a set of files or an entire directory from one place to another.
<br>
<img width="610" height="296" alt="image" src="https://github.com/user-attachments/assets/057147d1-2a69-49de-a868-a2ccaaa8acb3" />
<br>
Oops messed up the syntax a bit!
Another useful concept to use here is of wild cards, as using the wild card * we can easily copy a certain type to files to another location without bothering with other files.

One needs to be careful during copying files, as let’s say, we are copying ‘file1' from source to destination and the destination also has a file named ‘file1’. If one carelessly copies the files, the destination file1’s data would be overwritten leading to data loss, so we can use -i flag.

<h2>5. rm</h2>

To remove file or directories. To remove a file we can simply use,

`rm file_name`
But for directories we need to use the -r (recursive flag), as a directory may have multiple files, we can also make things interactive by combining the -r flag with -i flag, leading to the terminal prompting us every time.

If we want to force remove files we can use -f flag to force remove files.

<h2>6. mv</h2>

The command can be used in two ways one to move files from one place to another and the other being to rename files.

For moving the files, we have the same syntax as the cp command. And for renaming the files, the syntax is as follows:

`mv old_name.txt new_name.txt #pretty simple and straightforward!`
This concludes the managing files and directories commands, In the next part I’ll focus on Viewing and Inspecting Files.

Resource: [linuxjourney.com](https://linuxjourney.com/)

Previous: Understanding the ls and cd commands | Next: Viewing and Inspecting Files
