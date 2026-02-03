# Linux Notes 

## 🐧 Basic Commands
| Command | Description |
| :--- | :--- |
| `whoami` | Shows the current logged-in user. |
| `pwd` | Prints the current working directory. |
| `ls -la` | Lists all files (including hidden) with details. |
| `find / -name "file.txt"` | Searches system for a specific file. |

## Shells & Configuration
**What are commands?** Text instructions that tell the OS what to do.
* **Check Shell:** `echo $SHELL`
* **Install ZSH:** `sudo apt-get install zsh`
* **Reload Config:** `source ~/.zshrc`

## File Permissions
Permissions follow the `rwx` (Read, Write, Execute) format.

> **Tip:** Use `chmod +x script.sh` to make a file executable.

* **Change Owner:** `sudo chown user:group file`
* **Modify Rights:** `chmod 755 file`

## 📝 Vim Cheat Sheet
* `i` -> Insert mode
* `Esc` -> Exit mode
* `:wq` -> Save and quit
* `:q!` -> Quit without saving
