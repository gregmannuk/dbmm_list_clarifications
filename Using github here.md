# Guidance for those unfamiliar to GitHub

## What is GitHub
GitHub is an online collaboration tool mainly used by software developers to manage software code. It's a professional level tool and for personal use it is free. As it os a tool promarily for software developers you may not be familiar with the terms used. The key ones are covered in the guidance below.

## What do I need to use it?
### Get a github account
If you want to make a contribution to this repository you will need to create a github account. It's free. It is stronly advised to add some form of 2 facotr authentication to your account for added security.

### Install github desktop.
Although you can just use the github website to make updates to files it's generally considered best practice to:

1. Make a local copy of the repository (clone the master).
2. Make the updates on the local copy.
3. Push the changes back to the repository.

There are command line tools (gitbash) that can do this but I've found the easiest tool to use is github desktop  - https://desktop.github.com/.


## Getting a local copy
In guthub desktop:
1. Use menu option File -> Clone repository. 
2. Select the url option and enter the url for the repository (https://github.com/gregmannuk/dbmm_list_clarifications) and location where the copy will be placed.
		![create a clone](https://user-images.githubusercontent.com/76245811/103282147-b42df980-49cc-11eb-841d-2a0e913d54d9.png)
3. Click on the clone button.

You can now make the changes you want to the local copy.

## How will my changes get updated to the main repository?

Once you are happy with your changes you need to confirm you are happy with then by committing them locally. In the bottom left hand corner of github desktop there is a section to add a comment and commit locally. You must adda summary of the change and it's really useful to add some more detail to help thise who will approve the the change.

![Commit change](https://user-images.githubusercontent.com/76245811/103280813-3c120480-49c9-11eb-8661-e14217ffe7af.png)

Once the local commit has been made the following or similar will appear on the github desktop to push the proposal to the main repository. Possibly you will be asked to bring other changes to the main repository down to merge locally first.
![push to master](https://user-images.githubusercontent.com/76245811/103280874-5a780000-49c9-11eb-881e-7c348172ee13.png)

For most people this will create what is termed a pull request. This allows the administrators of the repository to accept or reject your proposed changes, They may also make suggestions for changes for tyou to make before they will approve.

