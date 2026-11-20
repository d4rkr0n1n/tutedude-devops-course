# Assignment 1 Linux Basics

## Links

- [GitHub](https://github.com/d4rkr0n1n/tutedude-devops-course)
- [Assignment 1 Solution GDrive](https://drive.google.com/drive/folders/1oWsVNgEzFYKAC_6CsPifxXm57y8N7hJN?usp=drive_link)
- [All Files](https://github.com/d4rkr0n1n/tutedude-devops-course/tree/bceee8a4a464940591edb77785b04b6e2c461111/Assignment_1_Linux_Basics/Docs)
- [Documented Solution](https://github.com/d4rkr0n1n/tutedude-devops-course/blob/eef478fecb981225518b271cc931017a8c0abd8d/Assignment_1_Linux_Basics/Docs/Assignment_1_Linux_Basics_Solution.docx.pdf)

## Commands

### 1. Creating and Renaming Files/Directories
1. Create a directory named test_dir using mkdir: `mkdir test_dir`
2. Inside test_dir, create an empty file called example.txt: `touch test_dir/example.txt`
3. Rename example.txt to renamed_example.txt using mv: `mv test_dir/example.txt test_dir/renamed_example.txt`

### 2. Viewing File Contents
1. Use cat to display the contents of /etc/passwd: `sudo cat /etc/passwd`
2. Display only the first 5 lines of /etc/passwd using head: `sudo cat /etc/passwd head - 5`
3. Display only the last 5 lines of /etc/passwd using tail: `sudo cat /etc/passwd tail - 5`

### 3. Searching for Patterns
1. Use grep to find all lines containing the word “root” in /etc/passwd: `cat /etc/passwd | grep root`

### 4. Zipping and Unzipping
1. Compress the test_dir directory into a file named test_dir.zip using zip.: `zip -r test_dir.zip test_dir`
2. Unzip test_dir.zip into a new directory named unzipped_dir: `unzip test_dir.zip -d unzipped_dir`

### 5. Downloading Files
1. Use wget to download a file from a URL (e.g., https://example.com/sample.txt): `wget https://raw.githubusercontent.com/d4rkr0n1n/tutedude-devops-course/refs/heads/main/prereq/sample.txt`

### 6. Changing Permissions
1. Create a file named secure.txt and change its permissions to read-only for everyone using chmod: `chmod a+r secure.txt && chmod a-wx secure.txt`

### 7. Working with Environment Variables
1. Use export to set a new environment variable called MY_VAR with the value “Hello, Linux!”: `export MY_VAR="Hello, Linux!"`
