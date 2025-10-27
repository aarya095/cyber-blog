Originally published on [Medium](https://medium.com/@aarya-sarfare/linux-6-viewing-and-inspecting-files-5379b65bb15f)

<h1>[Linux #6] Viewing and Inspecting Files</h1>

Disclaimer: This article documents my personal learning journey in cybersecurity. It is for educational purposes only and not professional advice or guidance for real-world systems. Content reflects my current understanding and may evolve as I learn more.

<h2>Introduction</h2> Viewing a file in the terminal is something one does everyday, so knowing how to view a file and search for what we want in the file is essential to know.

<h2>1. cat (concatenate)</h2>
`cat` command is primarily to used to view a file’s content, another task by which its name is given is concatenation i.e. joining two or multiple files and displaying them.

<br>
<img width="578" height="158" alt="image" src="https://github.com/user-attachments/assets/76b06bb2-cef2-4662-81e0-d7026eb06843" />
<br>

<h2>2. less</h2>

Let’s say we have a long file with multiple pages, reading it with ‘cat’ command would be a headache so linux has the ‘less’ command which displays the file content on the entire terminal screen, further ‘less’ provides the feature of pages, as a user can go through those pages and view the file’s content.

Another great feature ‘less’ provides is the option to search for a text in the file, which is super useful. We can search for a string by pressing ‘/’ and typing in what we want to search. For example,
<br>
<img width="392" height="121" alt="image" src="https://github.com/user-attachments/assets/5918b667-f8a5-4d4e-bcee-b4e525bb9aec" />
<br>
<img width="392" height="121" alt="image" src="https://github.com/user-attachments/assets/dfa03744-9b9b-4363-a78f-6f5f576aa762" />
<br>

Following are a set of instructions which help use to ‘less’ command better:

  Press ‘q’ to go back to the shell  
  Use arrow keys to move around  
  Press ‘g’ to go to the beginning of the file  
  Press ‘G’ to go to the end of the file

This concludes the viewing and inspecting files, In the next part I’ll focus on Searching and Tracking Command History.

Resource: [linuxjourney.com](https://linuxjourney.com/)

Previous: [Managing Files and Directories](https://github.com/aarya095/cyber-blog/blob/main/linux_series/%5BLinux%20%235%5D%20Managing%20Files%20and%20Directories.md) | Next: [Searching and Tracking Command History](https://github.com/aarya095/cyber-blog/blob/main/linux_series/%5BLinux%20%237%5D%20Searching%20and%20Tracking%20Command%20History.md)
