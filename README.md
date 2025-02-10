Here are the commands I used for this project and their outputs. 

mkdir -p projects/week1 projects/week2   # Create a directory structure with subfolders
touch projects/week1/hello.txt           # Create an empty file named hello.txt
cp projects/week1/hello.txt projects/week2/hello_copy.txt  # Copy hello.txt to week2 and rename it
rm projects/week1/hello.txt              # Delete the original hello.txt from week1
vim projects/about_me.txt                # Open Vim text editor to create and edit a file
mv terminal_log.txt projects/            # Move terminal_log.txt to the projects directory
git init                                  # Initialize a new Git repository
git add .                                 # Stage all files for commit
git commit -m "Initial commit"           # Commit changes with a message
git branch -M main                        # Rename the default branch to 'main'
git remote add origin https://github.com/MisolaInTheCloud/command-line-basics.git  # Link local repo to GitHub

