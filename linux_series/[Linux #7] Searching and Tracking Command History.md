Originally published on [Medium](https://medium.com/@aarya-sarfare/linux-7-searching-and-tracking-command-history-cc02694a9e24)

<h1>[Linux #7] Searching and Tracking Command History</h1>

Disclaimer: This article documents my personal learning journey in cybersecurity. It is for educational purposes only and not professional advice or guidance for real-world systems. Content reflects my current understanding and may evolve as I learn more.

Below, I’ll cover simple commands which help to find a file or a direcotry and keep track on which commands we have been running, and how to easily use them again.

<h2>1. find</h2>
We use the ‘find’ to find a file or directory in our system. To find a file in the current directory we can simply run,
<br>
<img width="370" height="83" alt="image" src="https://github.com/user-attachments/assets/07061544-7c5b-4bb4-854e-db3eb28f1960" />
<br>
But we won’t find all the entries of file1.txt in that entire directory, just on surface level, not in sub-directories. To find all the files named file1.txt in a directory, we need to include the path and ‘-name’ option with the file name, so we can run,
<br>
<img width="511" height="105" alt="image" src="https://github.com/user-attachments/assets/532af1d3-b7d2-4b09-96e9-31bb7d705099" />
<br>
Now, to find a directory, we need to include the ‘-type’, ‘-name’ option and path, so we can run,
<br>
<img width="598" height="120" alt="image" src="https://github.com/user-attachments/assets/5c08202c-1ca8-4b21-b74f-55957b039b8c" />
<br>

<h2>2. history</h2>

‘history’ command is simply to display the history of commands we have used so far.

If we simply type history, it’ll print a long list of commands, of course we don’t want that, so we can specify the number of commands we can see, for example,
<br>
<img width="338" height="189" alt="image" src="https://github.com/user-attachments/assets/1bf61a90-4abc-4102-b3b7-a9df2761df09" />
<br>
Further, if can also access the previous commands we have used via pressing the up arrow key and to return to the latest we can press the down arrow key.

<h3>Conclusion</h3>
This concludes the Searching and Tracking Command History, In the next part I’ll focus on Mastering Linux I/O Streams: stdin, stdout, and stderr.

Resource: [linuxjourney.com](https://linuxjourney.com/)

Previous: [Viewing and Inspecting Files](https://github.com/aarya095/cyber-blog/blob/main/linux_series/%5BLinux%20%236%5D%20Viewing%20and%20Inspecting%20Files.md)
