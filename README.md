# Analysis of Chicago ShotSpotter data


# How to Use GitHub

First to get the code on your computer, use your terminal to navigate to the directory where you want this repository to be stored. The repository will create a new directory for itself within whichever directory you navigate to.

On the [repository website page](https://docs.github.com/en/authentication/connecting-to-github-with-ssh/adding-a-new-ssh-key-to-your-github-account), press the green button that says "Code". Make sure SSH is selected, and copy the key. It should look something like "git@github.com:mfgeary/..."

You might have to set up an SSH key with your GitHub account. [Here](https://docs.github.com/en/authentication/connecting-to-github-with-ssh/adding-a-new-ssh-key-to-your-github-account) is a short tutorial about how to do this - it takes about 2 minutes.

Now go back to your terminal and enter the command `git clone git@github.com:mfgeary/...`.

The files should now be downloaded on your device. Edit them however you want. When you are ready to commit your changes to the GitHub repository, go back to the terminal and enter `git add *.ipynb`. Then enter `git commit`. A VIM editor will probably open on your computer. Add a commit message - give a brief explanation of the changes that you have made to the files. To edit on VIM, press `I` and then you can type. Save your commit message! (Press `ESC` and type `:wq` if using VIM).

Now you are ready to push your changes! Since this is a group project, first enter `git pull` to pull any changes made by other group members. Then enter `git push` to push your code to the GitHub repository.

Whenever you start working on the code again, start with `git pull` to get all the changes that have been made to the repository by other group members.

If you have more questions about GitHub, feel free to ask me or check out the GitHub documentation.
