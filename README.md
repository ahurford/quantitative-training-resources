## Why Github?
These materials are hosted on Github to promote openness and collaboration to capitalize on a diversity of skills and interest in quantitative training within the department.

## Facts about Github
1. Github hosts repositories: collections of documents organized in folders.
2. What am I looking at? You're looking at a files organized into folders (left column; the middle column can be ignored; the right column is the date files were last updated). Navigate throught the folders to the document you want to read. Some files my have confusing extensions like .md or .gitignore. The .md files are text files: you can open them in a text editor, but they are easy to read and edit on the github website. The .gitignore file can be ignored. Sometimes a folder will contain many files that are used to compile a .pdf. For such folders, begin by just reading the .pdf.
3. Github is like having your Dropbox files open to the public, while allowing the public to edit your Dropbox files. This is the power of Github in facilitating collaboration.
4. What if someone deletes all the files or messes them up? There are two reasons this can't happen:
  - contributors can only recommend changes to the repository, for the changes to be adopted they need to be approved by the owner or a collaborator; and
  - if a 'bad' change is accidently approved, the history of all commits to the repository are logged anyway. If a file is deleted it is possible to trace back through the commit history and restore a deleted the file.
5. If the power of Github is in facilitating open collaboration, everything 'complicated' about Github arises from the need to keep track of, and control, who makes what changes to which version of the repository. 
6. Github is designed with the idea that you want to download all the files, however, you can work around this and download individual files. Should you want to maintain an up-to-date version of the entire repository, Github Desktop can be helpful (https://desktop.github.com/).


## How can I contribute?
1. If do not wish to use github yourself, then you can email me ahurford@mun.ca and please indicated if you give permission for your contributions to be added to the repository. If you're ready to give github a try then go to 2.
2. You need a github account. This is to keep track of who is recommending changes.
3. If you just have comments, then submit these as an `issue`.
4. If you want to make edits you can watch this video for an introduction: https://www.youtube.com/watch?v=2VC9pCMuvfU&feature=youtu.be
5. To practice forking the repository and submitting a pull request (necessary for 4. and 5. above), here is a repository that you can practice on https://github.com/octocat/Spoon-Knife
  
### 3a. Editing directly on the github website
1. Some files, notably .csv, .md, and .txt formats, can be edited directly on github.
2. Fork the repository by clicking <img src="images/Fork.png" width="250">. This means you are starting your own `branch`. You do this because you don't have permission to edit the `master` (main) version of this repository. Requiring branch creation ensures that the owner and collaborators stay in control of the `master` repository's contents. You can skip this step and go to 3., but then you will be forced to make a `branch`.
3. Navigate to the file you want to edit and click on the `pencil` icon on the righthand side of the page.
4. You will now see raw text that you can edit as you please. You can save your work by clicking the big green `Propose file change` button. Note that you haven't changed the `master` version of the repository, just your personal copy: your `branch`.
5. When you are ready for your changes to be reviewed by a collaborator or the owner, then you need to submit a `pull` request.  You will  need to click the big green `Create Pull Request` button twice. 
6. If a long time passes between when you `fork` the repository and when you submit the `pull` request, there may be conflicts and this may make it more difficult to merge your changes into the `master` branch. This this becomes a problem you may wish to read about syncing your `fork`, and you may wish to consider using the Github Desktop application.

If you get stuck see:
https://github.com/aragon/hack/blob/master/docs-internal/github-guide.md
https://help.github.com/en/github/getting-started-with-github/fork-a-repo

### 3b. Download and edit files using your own software
1. Navigate through the folder system to the file you want to suggest edits on.
2. If the file is a .pdf or a .docx you should see a button to download the file. If the file is .md, .txt, or .csv then you won't see the download button. Instead on the righthand side of the page you should able to select the `Raw` tab. Copy and paste all the text from the `Raw` file into a text editor (Microsoft Word, TextEdit, etc).
3. Make your edits to the file on your computer. If the file is an .md, .txt, or .csv you need to keep to keep it simple (i.e., don't add figures).
4. When you are finished your edits, try to save the file in it's original format: same name and same extension (if you are not able this is not a big deal).
5. Open a web browser and go to the Github repository online. Log on to Github. You will need to fork the repository, i.e. create your own `branch`. See 2. in Section 3a. above.
6. Navigate through the file system to find the folder you wish to submit your file to (i.e. the location of the original file you downloaded).
7. You should see the option to `Upload file`. If you do not:
 - you may need to log in to Github
 - maybe you forgot to fork the repository (see 2. in section 3a)
 - or you might need to navigating to a higher level of the folder structure.
Alternatively, if the file is .md or .txt you might click the `pencil` icon, then delete the existing text and copy and paste in your revised text.
8. To save the changes to your `branch` you need to `commit` them (big green button).
9. To have your changes reviewed for potential inclusion on the `master` branch you need to submit a `pull` request. This might be a big green button or a white button near the top.

## 4. Add a file to the repository
1. Log on to Github, go to the repository you want to add a file to, and `fork` the repository: see 2. in Section 3a.
2. Near the top of the page you should see a the option to `Upload a file`. 
3. Make the `commit` (See 4. in Section 3a).
4. Submit a `pull` request.

If you are having trouble, see the _How to contribute_ section.
