## Obscure Linux Gems
Here, we introduce useful and lesser-known Linux tools that are not easily found with a simple search. Our goal is to familiarize you with tools that can make your Linux experience more engaging and efficient.

<details>  
<summary>Hidden Utilities</summary>  

| Command | Description | Use Case | Installation | Usage | Output |  
| --- | --- | --- | --- | --- | --- |  
| [`shuf`](#shuf) | Randomly shuffle lines of a file. | Shuffle the lines of a file to randomize their order. | Pre-installed in most distributions. | <pre>shuf file.txt</pre> | Randomly shuffled lines from `file.txt`. |  
| [`tldr`](#tldr) | Simplified man pages for common commands. | Get quick, community-driven simplified examples of command usage. | `sudo apt install tldr` | <pre>tldr tar</pre> | A simple, quick summary of how to use the `tar` command. |  
| [`chattr`](#chattr) | Change file attributes on a Linux file system. | Make a file immutable (unable to be modified). | Pre-installed in most distributions. | <pre>sudo chattr +i file.txt</pre> | The file becomes immutable, preventing modifications. |  
| [`nl`](#nl) | Number the lines of a file. | Add line numbers at the beginning of each line in a file. | Pre-installed in most distributions. | <pre>nl file.txt</pre> | File with line numbers at the beginning of each line. |  
| [`rev`](#rev) | Reverse the lines of a file. | Reverse the characters of each line in a file. | Pre-installed in most distributions. | <pre>rev file.txt</pre> | The content of `file.txt` reversed character by character. |  

</details>

<details>  
<summary>System Secrets</summary>  

| Command | Description | Use Case | Installation | Usage | Output |
| --- | --- | --- | --- | --- | --- |
| [ncdu](#ncdu) | Disk usage analyzer with a text-based interface. | Quickly analyze disk usage to identify large files and directories. | sudo apt install ncdu | <pre>ncdu /</pre> | A navigable interface showing disk usage by folder and file. |
| [htop](#htop) | Interactive process viewer for Unix systems. | Monitor system processes, memory usage, and CPU load in real-time. | sudo apt install htop | <pre>htop</pre> | A color-coded, interactive display of system processes and resource usage. |
| [inotifywait](#inotifywait) | Command-line utility to watch for file system changes. | Monitor file or directory changes in real-time, such as file creation or modification. | sudo apt install inotify-tools | <pre>inotifywait -m /path/to/dir</pre> | Lists events such as file creation, modification, or deletion. |
| [lsblk](#lsblk) | Lists information about all available block devices. | View detailed information about your storage devices, partitions, and file systems. | Pre-installed in most distributions. | <pre>lsblk</pre> | Displays a tree-like structure of your block devices, partitions, and mount points. |
| [auditd](#auditd) | Linux audit daemon for logging system events. | Record system events, especially changes to critical files or directories. | sudo apt install auditd | <pre>auditctl -w /etc/passwd -p wa</pre> | Logs all changes made to /etc/passwd, including writes and attribute changes. |

</details>  


<details>  
<summary>Network Ninja</summary>  

TBA

</details>

<details>  
<summary>Shell Sorcery</summary>  


</details>

<details>  
<summary>Fun and Terminal Delights</summary>  

TBA

</details>


