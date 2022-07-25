Introduction to Git Version Control System
What is Git?
Git is a free and open sourced software used to track, make changes to coding/programming projects and to encourage collaboration among developers.
What is Version Control?
Version is the process or practice of monitoring and tracking changes to software code. It enables developers to have remote access to projectsnfor easy tracking and access.Version control is also known as source control.
How to commit a project to github repository
The following steps/procedures should be followed to sucessfully commit a project to github repository. They include:
Visit www.github.com
Download and install git for the specific operating system
Sign up on Github by inputing email and log in details
Download Visual Studio Code used for writing codes
Write a HTML and/or CSS code and save in a folder on your local machine
To commit the project, the folder name of the project on the local machine should be the same with the folder name on github.
Go to github, create new repository
Name the repository the same name of the folder name on the local machine. 
Follow the specific command lines on VS Code:
git init
git add README.md
git commit -m "first commit"
git branch -M main
git remote add origin https://github.com/anochiliin/sample.git
git push -u origin main
Go back to github, refresh to confirm that the project has been sucessfully commited to github repository