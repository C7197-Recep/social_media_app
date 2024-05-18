# social_media_app

Do you need some cheatsheet info for beginning your MERN project? Find it below.

#Simple Reminders for Github

If you are yet to start your project, do not forget to bind it to your github.

1.  Install Git to your local: https://git-scm.com/downloads
2.  Click Settings button on the right down of VS Code, search for "Git Enabled", and make sure that it is enabled.
3.  Open your project folder on VS Code.
4.  Create a repo for your project on Github, and copy the Git URL from Github under Code button.
5.  Go to "Source Control" side menu, click "Initialize Repository", paste the Git URL you copied.
6.  Make changes to your project, go to Source Control, write your message and click Commit.
7.  Go to menu View->Command Pallette, write your project name, paste Git URL

Now, you can pull and push your changes

If you already started your project on your local and want to publish it to your Github,
you can do it with the following steps.

1. Create a new repo on Github
2. Open your project folder on VS Code
3. Open a new Terminal
4. Setup the connection. 

    a.  Add remote repo URL with the name "origin" or with the name of your repo
        You can find the repo "url" clicking green Code button on your Github repo and type

        git remote add origin <repository url>

        Here, you will need to login to Github if you are not so.

    b.  Set the main branch with the name "main"

        git branch --set-upstream-to=origin/main main

    c.  Pull the repo first

        git pull origin master --allow-unrelated-histories

    d.  Now, you can stage, commit and sync or publish the changes 
        using the menu under the Source Control side menu of VS Code.


MERN Stack Application
