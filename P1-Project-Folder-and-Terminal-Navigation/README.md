# P1 - Project Folder and Terminal Navigation

## Aim
To create a project folder and use terminal commands to move between folders and manage files.

## Steps

1. Open the terminal.
2. Check the current location.
3. Create a folder for the web development lab.
4. Move into the folder.
5. Create a few files and a folder for project assets.
6. List the contents and practise moving back to the previous directory.

## Commands used

| Command | Purpose |
| --- | --- |
| `pwd` | Shows the current directory |
| `mkdir Web_Dev_Project` | Creates the project folder |
| `cd Web_Dev_Project` | Moves into the project folder |
| `mkdir assets` | Creates an assets folder |
| `touch index.html style.css script.js` | Creates three empty files (macOS/Linux) |
| `ls` | Lists the files and folders |
| `cd ..` | Goes back to the parent directory |
| `cd Web_Dev_Project` | Enters the project folder again |

## Procedure

Run the commands one by one in the terminal:

```bash
pwd
mkdir Web_Dev_Project
cd Web_Dev_Project
mkdir assets
touch index.html style.css script.js
ls
cd ..
pwd
cd Web_Dev_Project
ls
```

If you are using Windows Command Prompt instead of macOS/Linux, use `type nul > index.html`, `type nul > style.css`, and `type nul > script.js` in place of the `touch` command.

## Expected folder structure

```text
Web_Dev_Project/
├── assets/
├── index.html
├── style.css
└── script.js
```

## Result
The project folder and its basic files were created. The terminal commands were used to view the current location, enter a folder, list its contents and return to the parent directory.
