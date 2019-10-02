# A03
A03, the one and only FOSS for just $4.99


**Here's a cohesive tutorial on how to get Git, Github and WebStorm running in tandem on your PC**

1. In order to use services such as Git, Github, and WebStorm, you must create accounts for Github and Jetbrains, respectively.
You can sign up for Github at https://github.com/join and Jetbrains at https://jetbrains.com

2. The first program you'll want to install is Git, which can be found here:

3. Next, you'll want to install WebStorm, which can again, be found at https://jetbrains.com
                                                                       
4. If you've installed Git beforehand, WebStorm should automatically detect where your Git path is, but in case it doesn't, 
you can go to File > Settings > Version Control > Git and specify the path to git.exe manually.

5. Now you're ready to create a repository. On the Github homepage, hit the "+" on the upper right corner, and select 
"Create new repository" This will set you up with a new repository you can name and make public that has a blank README.md file.

6. In order to view and make changes to your repository with WebStorm, open it up and navigate to "Check Version Control" then "Git"

7. From this menu, you are able to enter the URL of your repository.

8. if you've followed the steps correctly, you will now be able to edit files within the repository. When you're ready to push
your file, you can commit to the repository using the "Commit" button at the top of the WebStorm window, or Ctrl + K. Be sure
to add meaningful descriptions to tell people exactly what you're committing to the project.

9. To finalize the changes in the project on GitHub, you can "Push" the commits. In order to do this, navigate to VCS -> Git -> Push
or hit Ctrl + Shift + K. 

**Term Definitions:**

Git - A free distributed version control system for viewing, editing, and keeping track of changes to an open source project.

GitHub - A web-based Git repository hosting service. Projects on GitHub can be accessed through the Git command line,
and they can be managed by users with GitHub accounts. The structure of GitHub promotes collaboration by allowing projects to have
multiple collaborators.

Repository - The file storage where all the files of an individual project are stored. Users can freely access, copy and 
edit said files.

Clone - A command that allows a user to make a copy of a repository or a file within a repository

Commit - This is a command that allows users to make changes to files within a repository. This change will be saved locally, 
and if the user wants to get it pushed to the Repository, he must request for the owner of the repository to pull the commit
into the full project.

Push - This is a command that allows you to send your committed changes to a remote repository hosted on Github, 
allowing others to see the changes, access them, and comment on them.

Pull - This is a request from a collaborator for the owner of a repository to add their changes to collaborator's local storage

Branch - A fork of a repository that creates two repositories for individuals to make separate changes and additions to

Merge - Applies the changes from one fork or branch of a repository to another fork or branch of a repository

Merge Conflict - This occurs when changes are made to the same file or line of code that someone else is working on

Fetch - Receives the latest changes from an online repository without overwriting your local files

Remote - Separate versions of files hosted on a service like GitHub that allow you to create changes locally that automatically 
update online