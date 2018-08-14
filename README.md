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

### Making a suggestion
To make a suggestion, you have to folow the [**suggestion format**](data/format.txt). When you first open it up, it will have some fields with a REPLACE_HERE text next to them. You are to fill in those details in those areas. For example, I will now show how you'd contribute a suggestion. **Note: this assumes you have created a github account, installed git on your computer, and configured it**

**Note: for those unwilling to read text, there's a [**video tutorial online**](REPLACE_THIS_LINK)

1. Clone the repository from the [**base url**](https://github.com/sysbloat/Lsrcr-Redesign/). This is done on either the command prompt or git bash prompt. First, change into a directory you'd want to keep the repository copy in (for example, Desktop). Once you're in the directory you want the repo to be created in, run the following command: `git clone https://github.com/sysbloat/Lsrcr-Redesign/`.

2. Once you've cloned it, open the folder up on your File Explorer (what you use to browse your files). Once in the suggestions directory, browse for an appropriate subdirectory. **Note: if there's no appropriate subdirectory, pick the directory that is most accurate and I'll move it to the right place.**

3. Once you're in the appropriate subdirectory, create a textfile. Give it a **meaningful and descriptive name**. The example we'll do as a walkthrough is "car_roof_shooting.txt". 

4. Copy the appropriate portion of the [**suggestion format**](data/format.txt), and paste it inside the file you create it. Save the file.

5. Modify the file accordingly with your suggestion, and save it when done.

6. Go back to your repository directory, and run `git status`. If everything went right, the output should list the files/directories you've created/changed/deleted. 

7. Once you're satisfied, run `git commit -m <YOUR_COMMIT_MESSAGE>`. Please make sure to make a correct commit message. A good example is something like "Add car roof shooting suggestion."; a bad example is "Added suggestion". Good commit messages help to keep stuff better organized and easier to filter through. 

8. Once the commit command runs successfully, run `git push origin master`. This will "push" your commited changes to your repository, effectively "updating it". 

9. Once you've pushed your changes, get back to the [**original repository in Github**](https://github.com/sysbloat/Lsrcr-Redesign/) and click on the "New pull request" button. Select the original master branch as the base, and your own repo's branch as the compare target, and create a pull request.

10. That's it, from that point on you will have published a suggestion. Other people will be free to comment on it, etc. It will be tagged according to its status (accepted, review, denied, etc.) but this is more of a developer intended feature. Thanks for taking the time to make a suggestion!

### Commenting on a suggestion

1. Go to the [**pull requests section**](https://github.com/sysbloat/Lsrcr-Redesign/pulls).

2. Select the suggestion you'd want to comment on. 

3. Visit the [**suggestion format**](data/format.txt) and copy the appropriate text.

4. Scroll down in your browser until you see a "Leave a comment" section. 

5. Paste the contents of the format there, and modify them accordingly. *Hint: you can review your message before posting it by clicking on "Preview"*.

6. Once happy with the message, click the "Comment" button. 

7. That's it, from that point on your opinion can be heard and addressed by the rest of us! Thanks for sharing your feedback.
