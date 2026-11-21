# linux-file-editing-vim-nano
Hands-on Linux project exploring file creation and editing using Vim and Nano on an Amazon Linux EC2 

#Project Overview

This project explores file creation and editing in a Linux environment using two popular command-line text editors: Vim and Nano.

As part of my AWS and Linux learning journey, I connected to an Amazon Linux EC2 instance using SSH and practised creating, modifying, saving and managing files through the terminal.

The exercise helped me understand how Linux administrators and engineers interact with files without relying on graphical interfaces.

# Project Objectives

- Connect to an Amazon Linux EC2 instance using SSH.
- Understand basic Vim editor operations.
- Create and edit files using Vim.
- Practise saving and exiting files in Vim.
- Create and edit files using Nano.
- Understand the differences between Vim and Nano.

# Tools and Technologies

- Amazon Web Services (AWS)
- Amazon EC2
- Amazon Linux
- SSH
- Vim
- Nano
- Linux Command Line

# Task 1: Connect to the Linux EC2 Instance

I connected to an Amazon Linux EC2 instance using SSH.

For key-based authentication, the command format was:

```bash
ssh -i labsuser.pem ec2-user@PUBLIC-IP
```

For Windows users, the lab also provides instructions for connecting with PuTTY and a PPK key file.

# Task 2: Explore Vim Using Vimtutor

I launched the interactive Vim tutorial using:

```bash
vimtutor
```

The tutorial introduced basic Vim navigation and editing operations.

I worked through the assigned lessons to understand how to navigate and interact with files using Vim.

To exit the tutorial:

```vim
:q!
```

If Vim was not installed, the lab provided this installation command:

```bash
sudo yum install vim
```

# Task 3: Create and Edit a File Using Vim

I created a file named `helloworld` using:

```bash
vim helloworld
```

To begin editing, I entered Insert Mode:

```text
i
```

I added the following content:

```text
Hello World!
This is my first file in Linux and I am editing it in Vim!
```

To save the changes and exit:

```vim
:wq
```

I reopened the file and added another line:

```text
I learned how to create a file, edit and save them too!
```

I also explored some additional Vim commands:

| Command | Function |
|---|---|
| `i` | Enter Insert Mode |
| `Esc` | Exit Insert Mode |
| `:w` | Save changes |
| `:wq` | Save and quit |
| `:q!` | Quit without saving changes |
| `dd` | Delete the current line |
| `u` | Undo the last change |

# Task 4: Create and Edit a File Using Nano

I created a file named `cloudworld` using:

```bash
nano cloudworld
```

Unlike Vim, Nano allows you to start typing immediately without entering a separate Insert Mode.

I entered the following text:

```text
We are using nano this time! We can simply start typing! No insert mode needed.
```

To save the file:

- Press `CTRL + O`.
- Press Enter to confirm the filename.
- Press `CTRL + X` to exit.

I reopened the file to confirm that the changes had been saved successfully.

# Key Differences Between Vim and Nano

| Vim | Nano |
|---|---|
| Uses different editing modes | Allows direct typing |
| Has a steeper learning curve | Beginner-friendly interface |
| Uses commands such as `:wq` | Uses keyboard shortcuts |
| Supports advanced editing operations | Provides straightforward text editing |

# Key Learnings

Through this exercise, I gained practical experience in:

1. Connecting to Linux environments through SSH.
2. Navigating the Vim text editor.
3. Creating and editing files using Vim.
4. Saving and managing files through terminal commands.
5. Using Nano for basic file editing.
6. Understanding the differences between two Linux text editors.

# Conclusion

This exercise strengthened my 
understanding of Linux command-line operations and introduced me to two essential text editors used in Linux environments.

I am continuing to build my practical Linux, Cloud and DevOps skills through hands-on exercises and documenting my progress.
Learning in public. Building one project at a time.**

#Linux #AWS #CloudComputing #DevOps

