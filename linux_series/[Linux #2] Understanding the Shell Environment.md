Originally published on Medium: https://medium.com/@aarya-sarfare/linux-2-understanding-the-shell-environment-8366cc22703d

[Linux #2] Understanding the Shell Environment

Disclaimer: This article documents my personal learning journey in cybersecurity. It is for educational purposes only and not professional advice or guidance for real-world systems. Content reflects my current understanding and may evolve as I learn more.

In the following article, I introduce to shell basics, and how to get comfortable with using the shell via learning very basic yet helpful commands. Let’s get started,

help
Whenever I get stuck a command or exploring a new command, I do what any person would do i.e. ask for help. Help provides the necessary information to learned about the options and arguments possible with the command. Help is used to fast annd quick access to the information.

mv --help #syntax
2. man (manual)

man command basically provides the entire manual to the command and provides all the information about the command. Unlike, man is used to get all the information about the command.

man ls
3. whatis

whatis command tells in a one liner about a command, great for remembering what does the command do.

whatis ls
4. alias

Used to give an alias to a command, useful for executing long and repetitive commands. To set an alias,

alias alias_name='command' 
unalias alias_name #to remove the alias

<img width="446" height="112" alt="image" src="https://github.com/user-attachments/assets/bb185877-9a8b-4c04-aebd-f3ebdaa117ac" />

To set the alias that’ll remain even after closing the current session, we need to edit the ~./bashsrc file.

5. exit

To close the GUI terminal or log out of a shell.

I’ll here conclude understanding the shell environment, I have explained about helpful bash commands. Next part I’ll start with another set of generic linux commands.

Resource: linuxjourney.com

Previous: Getting Started with the Bash Shell | Next: Starting with linux Commands
