## Obscure Linux Gems

| Command | Description | Use Case | Installation | Usage | Output |
| --- | --- | --- | --- | --- | --- |
| [`shuf`](#shuf) | Randomly shuffle lines of a file. | Shuffle the lines of a file to randomize their order. | Pre-installed in most distributions. | <pre>shuf file.txt</pre> | Randomly shuffled lines from `file.txt`. |
| [`tldr`](#tldr) | Simplified man pages for common commands. | Get quick, community-driven simplified examples of command usage. | `sudo apt install tldr` | <pre>tldr tar</pre> | A simple, quick summary of how to use the `tar` command. |
| [`chattr`](#chattr) | Change file attributes on a Linux file system. | Make a file immutable (unable to be modified). | Pre-installed in most distributions. | <pre>sudo chattr +i file.txt</pre> | The file becomes immutable, preventing modifications. |
| [`nl`](#nl) | Number the lines of a file. | Add line numbers at the beginning of each line in a file. | Pre-installed in most distributions. | <pre>nl file.txt</pre> | File with line numbers at the beginning of each line. |
| [`rev`](#rev) | Reverse the lines of a file. | Reverse the characters of each line in a file. | Pre-installed in most distributions. | <pre>rev file.txt</pre> | The content of `file.txt` reversed character by character. |
