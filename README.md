# 📄 Mini Guide: Working with Files in Linux Terminal

## 🔍 Check if File Exists
```bash
ls file_name
````

> List the file if it exists.

---

## ➕ Create a File

```bash
touch file_name
```

> Create an empty file or update its timestamp if it exists.

```bash
echo "Hello World" > file_name.txt
```

> Create a file with initial content (overwrites if file exists).

```bash
echo "More text" >> file_name.txt
```

> Append text to an existing file.

---

## 📂 View File Content

```bash
cat file_name
```

> Show whole content of the file.

```bash
less file_name
```

> View file content page-by-page (scrollable).

```bash
head file_name
```

> Show first 10 lines (use `head -n 5` for 5 lines).

```bash
tail file_name
```

> Show last 10 lines (use `tail -n 5` for 5 lines).

---

## ✏️ Edit File

```bash
nano file_name
```

> Open file in Nano editor (simple terminal editor).

```bash
vim file_name
```

> Open file in Vim editor (advanced terminal editor).

---

## 🗑️ Delete File

```bash
rm file_name
```

> Delete the file.

---

## 📋 Copy File

```bash
cp source_file destination_file
```

> Copy file to a new location or name.

---

## 🔀 Move or Rename File

```bash
mv old_file_name new_file_name
```

> Rename or move file.

---

## 📊 File Info and Permissions

```bash
ls -l file_name
```

> Show file details (size, permissions, date).

```bash
stat file_name
```

> Detailed file info.

---

## 🌟 Extra Tips

* Use wildcard `*` to work on multiple files, e.g., `rm *.txt` removes all `.txt` files.
* Use `file file_name` to check file type.
* Use `chmod` to change file permissions, e.g., `chmod +x file.sh` to make executable.
* Use `file file_name` to determine file type.

---

# 📋 Quick Reference Table

| Action                   | Command                           | Emoji |
| ------------------------ | --------------------------------- | ----- |
| Check file exists        | `ls file_name`                    | 🔎    |
| Create empty file        | `touch file_name`                 | ➕     |
| Create file with content | `echo "text" > file_name`         | ✍️    |
| Append text to file      | `echo "text" >> file_name`        | ➕     |
| View file content        | `cat file_name`                   | 📄    |
| View file page-wise      | `less file_name`                  | 📖    |
| View first lines         | `head file_name`                  | 🔝    |
| View last lines          | `tail file_name`                  | 🔚    |
| Edit file (nano)         | `nano file_name`                  | ✏️    |
| Edit file (vim)          | `vim file_name`                   | 🖋️   |
| Delete file              | `rm file_name`                    | 🗑️   |
| Copy file                | `cp source_file destination_file` | 📋    |
| Move/Rename file         | `mv old_file_name new_file_name`  | 🔀    |
| Show file info           | `ls -l file_name`                 | ℹ️    |
| Detailed file info       | `stat file_name`                  | 🧐    |

---

😊🚀
