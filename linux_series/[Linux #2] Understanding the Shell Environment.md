Originally published on Medium: https://medium.com/@aarya-sarfare/linux-2-understanding-the-shell-environment-8366cc22703d

<h1>[Linux #2] Understanding the Shell Environment</h1>

Disclaimer: This article documents my personal learning journey in cybersecurity. It is for educational purposes only and not professional advice or guidance for real-world systems. Content reflects my current understanding and may evolve as I learn more.

In the following article, I introduce to shell basics, and how to get comfortable with using the shell via learning very basic yet helpful commands. Let’s get started,

<h2>1. help</h2>
Whenever I get stuck a command or exploring a new command, I do what any person would do i.e. ask for help. Help provides the necessary information to learned about the options and arguments possible with the command. Help is used to fast annd quick access to the information.

mv --help #syntax

<h2>2. man (manual)</h2>

man command basically provides the entire manual to the command and provides all the information about the command. Unlike, man is used to get all the information about the command.

man ls

<h2>3. whatis</h2>

whatis command tells in a one liner about a command, great for remembering what does the command do.

whatis ls

<h2>4. alias</h2>

Used to give an alias to a command, useful for executing long and repetitive commands. To set an alias,

alias alias_name='command' 
unalias alias_name #to remove the alias
<br>
<img width="446" height="112" alt="image" src="https://github.com/user-attachments/assets/bb185877-9a8b-4c04-aebd-f3ebdaa117ac" />

To set the alias that’ll remain even after closing the current session, we need to edit the ~./bashsrc file.

<h2>5. exit</h2>

To close the GUI terminal or log out of a shell.

I’ll here conclude understanding the shell environment, I have explained about helpful bash commands. Next part I’ll start with another set of generic linux commands.

Resource: [linuxjourney.com](https://linuxjourney.com/)

Previous: [Getting Started with the Bash Shell](https://github.com/aarya095/cyber-blog/blob/main/linux_series/%5BLinux%20%231%5D%20Getting%20Started%20with%20the%20Bash%20Shell.md) | Next: [Starting with linux Commands](https://github.com/aarya095/cyber-blog/blob/main/linux_series/%5BLinux%20%233%5D%20Starting%20with%20linux%20Commands.md)
