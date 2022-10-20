# GitTest
This is a guide of how to use the main functions of Git in a simple way.

First, I used this guide:
https://www.youtube.com/watch?v=J_Clau1bYco
Most of the things in this guide were helpful, but not everything was correct.

Here is the full process I did that allowed me to use Git successfully with GitHub:
1. Download Git from here - https://git-scm.com/downloads
2. Install Git
3. Create a new folder on the computer where you want to mangage your project
4. Open the Git Bash
5. use the "cd" command to navigate to the folder you created
6. Run the following command - git config --global user.name <username> # Write your GitHub username instead of <username>
7. Run the following command - git config --global user.email <email> # Write your email instead of <email>
8. Run - git clone <link> # copy the share link from GitHub, and replace <link> by this link
Now the folder you created should contain the content of your GitHub repository.
9. Navigate to your repository (cd <repository name>)
10. Make some changes on the files/create new ones
11. Run - git add <newFiles> # Instead of <newFiles>, write the file names of new files created to add them to Git.
12. Run - git status # To make sure the files weres added
13. Run - git commit -m <commit comments> # this way you commit the changes
14. Run - git push origin main # This way you push the changes back to GitHub
15. Login to your account if needed to apply the  commit.

And that's all!
