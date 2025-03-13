# Laboratory Work No. 5

**Discipline:** Operating Systems    

**Topic:** “Familiarization with Navigation Commands in the File System and File and Directory Management”

---

## Objectives of the Work: 
1. To acquire practical skills in working with the Bash command line.
2. To familiarize with basic navigation commands in the file system.
3. To learn basic commands for managing files and directories.

---

## Preliminary Preparation Tasks

### Glossary of Basic Terms

| Terms               | Definition                                                                  |
|---------------------|-----------------------------------------------------------------------------|
| Filesystem           | A method of organizing and storing data on a disk                          |
| Root directory       | The highest level of the file system ("/")                                 |
| Home directory       | The user's home directory ("/home/username")                               |
| Absolute path        | The full path to a file/directory, starting with "/"                       |
| Relative path        | A path that indicates the location relative to the current directory       |
| cd                   | Command to change the current directory                                     |
| ls                   | Displays the contents of a directory                                        |
| cp                   | Copies files and directories                                                |
| mv                   | Moves or renames files                                                     |
| rm                   | Deletes files and directories                                              |
| mkdir                | Creates a new directory                                                    |
| touch                | Creates an empty file                                                      |
| rmdir                | Deletes an empty directory                                                 |

---

### Answers to Theoretical Questions

1. **Comparison of File Structures in Windows and Linux:**
   - Windows uses drives (C:, D:), while Linux organizes everything in a single hierarchy of directories, starting from the root directory `/`.
   - Windows uses the registry for configurations, while Linux uses text configuration files in `/etc/`.

2. **FHS (Filesystem Hierarchy Standard):**
   - This is a standard that defines the layout of directories in the Linux file system.
   - It specifies key directories such as `/bin`, `/etc`, `/home`, `/var`, `/usr`, `/tmp`, `/proc`, etc.

3. **Basic Commands for Working with Files and Directories:**
   - Creating files: `touch filename`
   - Creating directories: `mkdir directory_name`
   - Copying: `cp file1 file2`, `cp -r dir1 dir2`
   - Moving and renaming: `mv file1 file2`
   - Deleting files: `rm file_name`
   - Deleting directories: `rm -r directory_name`, `rmdir empty_directory`

---

## Practical Part

### Navigating to Home Directory and Creating a New Directory
![image](https://github.com/user-attachments/assets/53b27122-e779-415a-b2cf-3db60af82aad)


### Creating Subdirectories and Files
![image](https://github.com/user-attachments/assets/35562fd0-c2a8-4dd6-83f8-93a0bc97444f)


### Copying and Moving Files
![image](https://github.com/user-attachments/assets/cc4fdbd7-9a2a-4bbc-92b1-97a35f7159d5)


### Updating File Contents
![image](https://github.com/user-attachments/assets/ffe7cba1-d926-4dcf-b733-33a9c81fbd2e)


### Viewing All Created Files and Directories
![image](https://github.com/user-attachments/assets/5b4feb4f-0b07-4061-914d-aed2a26b81ca)


## Control Questions 

1. **Viewing the Path to the User's Home Directory:**
   ```bash
   echo $HOME
   echo ~
   ```

2. **Viewing the Contents of the Root Directory from the Home Directory:**
   ```bash
   ls /
   ```

3. **Adding Information to an Empty File:**
   ```bash
   echo "This is a new file" > file.txt
   ```

4. **Copying and Deleting an Existing Directory:**
   - Copying:
     ```bash
     cp -r directory1 directory2
     ```
   - Deleting (empty directory):
     ```bash
     rmdir directory_name
     ```
   - Deleting (non-empty directory):
     ```bash
     rm -r directory_name
     ```

5. **Moving, Renaming, and Performing Both Actions Simultaneously:**
   ```bash
   mv /work/tech/comp.png /Desktop       # Moving
   mv /work/tech/comp.png /work/tech/my_car.png  # Renaming
   mv /work/tech/comp.png /Desktop/computer.png  # Both moving and renaming
   ```

---

## Conclusions

During the laboratory work, the basic commands for navigation and file management in Linux were studied. The skills acquired in working with the Bash command line will allow for effective operations in the command line interface. Knowledge of basic commands will facilitate the automation of routine tasks and enhance work productivity.

---


