# Lsrcr Redesign Repository

## About
This is a repository that will contain some information as well as suggestions/ideas to improve Ls-rcr. Ls-rcr is a Cops and Robbers theme server for the Grand Theft Auto : San Andreas multiplayer modification known as SA:MP. So far this is done unoficially but should ideally provide some order for developers or anyone who's interested to contribute in how things would be adjusted. 

## Why this? Why not use the forums?
This repository allows for an easier, more organized way to keep track of everyone's input and every suggestion on a large scope. It would be hard to address things in a specific forum post since comments can easily add up as well as unnecessary additions/ "I agree" statements that just clog up the post. To be able to contribute into this repository, a user would have to go through some (very minor) hurdles such as learning how to register an account on github, downloading and installing git on their machine, and learning how to clone and submit a pull request. Please check the corresponding contribution section for a rundown on how to contribute.

## How is this organized?
This high level structure contains three folders: data, information and suggestions. 

* The [**data directory**](data/) contains images and other files that are used in the repository itself, *thou shall not touch*. 
* The [**information directory**](information/) contains information (such as class, skill, etc) 
* The [**suggestions directory**](suggestions/) contains suggestion information (such as ongoing suggestions, etc)

When contributing, make sure that you are in the **correct subdirectory** for the suggestion you're trying to make (i.e don't make your suggestion file about cops in the economy subdirectory). The subdirectories will be adjusted as more suggestions come in, but the high level directory (as in the one you're reading this file from) should remain relatively untouched. Please visit the directory you want to learn more about and read its corresponding readme file for more information.

## How to contribute
There's two ways you can contribute as a player: you can make suggestions yourself or you can comment on others' suggestions. Each of these are handled differently.

**Note: for those unwilling to read text, there's a [**video tutorial online**](https://youtu.be/DkxURx_GQBw)

### Making a suggestion
To make a suggestion, you have to folow the [**suggestion format**](data/format.txt). When you first open it up, it will have some fields with a REPLACE_HERE text next to them. You are to fill in those details in those areas. For example, I will now show how you'd contribute a suggestion. **Note: this assumes you have created a github account, installed git on your computer, and configured it**

1. Fork the repository from the [**original repo's base url**](https://github.com/sysbloat/Lsrcr-Redesign/) by clicking on the "Fork" botton at the top right of your screen. 

2. Once you've forked it, you will be redirected to your fork of the repo. You can think of this fork as your own custom "copy". Copy the url on your browser of your repo (should look something like https://github.com/YOUR_USER_NAME/Lsrcr-Redesign/).

3. Once you've copied the link, go to a location where you'd want to save a local copy of the repo. Enter a git bash and run `git clone https://github.com/YOUR_USER_NAME/Lsrcr-Redesign/` (replace the link with a valid one). If successful, change directory into the repository you just cloned.

4. Open the folder up on your File Explorer (what you use to browse your files). Once in the suggestions directory, browse for an appropriate subdirectory. **Note: if there's no appropriate subdirectory, pick the directory that is most accurate and I'll move it to the right place.**

5. Once you're in the appropriate subdirectory, create a textfile. Give it a **meaningful and descriptive name**. The example we'll do as a walkthrough is "car_roof_shooting.txt". 

6. Copy the appropriate portion of the [**suggestion format**](data/format.txt), and paste it inside the file you create it. Save the file.

7. Modify the file accordingly with your suggestion, and save it when done.

8. Go back to your repository directory, and run `git status`. If everything went right, the output should list the files/directories you've created/changed/deleted. 

9. Once you're satisfied, run `git commit -m <YOUR_COMMIT_MESSAGE>`. Please make sure to make a correct commit message. A good example is something like "Add car roof shooting suggestion."; a bad example is "Added suggestion". Good commit messages help to keep stuff better organized and easier to filter through. 

10. Once the commit command runs successfully, run `git push origin master`. This will "push" your commited changes to your repository, effectively "updating it". 

11. Once you've pushed your changes, get back to your [**copy repository in Github**](https://github.com/YOUR_USERNAME/Lsrcr-Redesign/) (use a valid link). You'll see that on the "latest commit" line, there'll be a notice that says that your branch is "X" commits ahead of my branch (sysbloat/master). You may want to review your changes below, and then click "Pull request". 

12. You'll be taken to a screen that asks for a description of the changes and a title. As long as the commit message you used was fine, you shouldn't need a specific description. **Make sure the tickbox next to "Allow edits from maintainers" is enabled.** Once this is done, click "Create Pull Request".

13. You're done, your suggestion is up for review of everyone. Can keep rechecking to see the status for it, and you'll be notified when people tag you in responses. Thanks for taking the time to make a suggestion!

### Commenting on a suggestion

1. Go to the [**pull requests section**](https://github.com/sysbloat/Lsrcr-Redesign/pulls).

2. Select the suggestion you'd want to comment on. 

3. Visit the [**suggestion format**](data/format.txt) and copy the appropriate text.

4. Scroll down in your browser until you see a "Leave a comment" section. 

5. Paste the contents of the format there, and modify them accordingly. *Hint: you can review your message before posting it by clicking on "Preview"*.

6. Once happy with the message, click the "Comment" button. 

7. That's it, from that point on your opinion can be heard and addressed by the rest of us! Thanks for sharing your feedback.
