#Git Walkthrough

###Step 1
Go to your Github profile.
  

###Step 2
Select the 'Repositories' tab.
  
![Click Repo][https://github.com/SkillDistillery/public/tree/master/imgs/click_repo.png]

###Step 3
Click the 'New' button.
  
![Click New][https://github.com/SkillDistillery/public/tree/master/imgs/click_new.png]

###Step 4
Name your repository 'javaHardWay', click create.
  
![Name Repo][https://github.com/SkillDistillery/public/tree/master/imgs/name_repo.png]

###Step 5
Use the clipboard icon to copy the link to the repository.
  
![Copy Link][https://github.com/SkillDistillery/public/tree/master/imgs/copy_link.png]

###Step 6
Open a Terminal, and navigate to your 'Desktop'.
  
![cd Desktop][https://github.com/SkillDistillery/public/tree/master/imgs/cd_desktop.png]

###Step 7
Use the `git clone https://github.com/...` command to clone a local copy of the repository you just created to your desktop.
  
![Clone Repo][https://github.com/SkillDistillery/public/tree/master/imgs/clone_repo.png]

###Step 8
Change directory into your local repository (`cd javaHardWay`)
  
![cd Java Hard Way][https://github.com/SkillDistillery/public/tree/master/imgs/cd_javaHardWay.png]

###Step 9
Write your solutions to the first 'Java the Hard Way' exercise in this repository.
  
![ls][https://github.com/SkillDistillery/public/tree/master/imgs/ls.png]

###Step 10
Each time you complete an exercise, you'll update your remote repository (the one you see when you go to Github), with the code in your local repository.

###Step 11
Use `git status` to identify which files are currently staged to be committed. File names that appear in red are either modified, new, or untracked and will need to be staged in order to commit. Green files have already been staged.  
  
![git status][https://github.com/SkillDistillery/public/tree/master/imgs/git_status_pre.png]

###Step 12
Use `git add FirstProg.java` to stage the FirstProg.java file. `git add filename` is the command to tell git to stage changes to a file. Now run `git status` again, and FirstProg.java should appear in green.
  
![git status][https://github.com/SkillDistillery/public/tree/master/imgs/git_status_post.png]

###Step 13
Now that your changes are staged you can commit them. Committing changes is a lot like saving them. Git creates a new commit that can be rolled back to if something goes wrong. In order to commit your staged changes you also need to include a commit message, this should be something short but descriptive like "add exercise 1". The command for this would be `git commit -m "add exercise 1"`.
  
![git commit][https://github.com/SkillDistillery/public/tree/master/imgs/git_commit.png]

###Step 14
Almost done!  
  
Now that you've committed your changes locally you can update your remote repository (Github) with your new code. To accomplish this we do what's called a 'push'. In order to push we need to specify the server to push to as well as the branch we wish to push to. For now the server's name is 'origin' and the branch's name is 'master'. The sum of all of these parts is the command `git push origin master.
  
![git push][https://github.com/SkillDistillery/public/tree/master/imgs/git_push.png]

###Step 15
That's it, now if you go to your Github profile and then select the 'javaHardWay' repository, you should see the file you just pushed up is there.
  
![finished][https://github.com/SkillDistillery/public/tree/master/imgs/finished.png]
