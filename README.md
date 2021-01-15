# GitTest
This is a Git Repository for learning about Git.

I will suggest to follow the blog post at https://foreverprogrammer.wordpress.com/2021/01/08/starting-with-git/.<br/>
Post describes about the following Git concepts:
  1. Creating a Git repository
  2. Cloning a remote repository
  3. Committing files to a local repository
  4. Committing files to a remote repository
  5. Creating and switching a branch
  6. Merging two branches
  
Following is a summary of commands used for these tasks:
  1. Initializing a local directory as repository:<br/><code>git init</code>
  2. Cloning a remote repository:<br/><code>git clone repository-link</code><br/><code>git clone https://github.com/prajyotnaik3/GitTest.git</code>
  3. Checking status of the files in a local repository:<br/><code>git status</code><br/><code>git status -s</code>
  4. Start tracking files / Staging files:<br/><code>git add file-name</code><br/><code>git add file-name-1 file-name-2 ... file-name-n</code><br/><code>git add .</code><br/><code>git file test1.txt</code>
  5. Committing changes in staging area to local repository:<br/><code>git commit -m "Text messsage"</code>
  6. Create a remote:<br/><code>git remote add remote-name remote-repository-url</code><br/><code>git remote add [-t branch-name] remote-name remote-repository-url</code>
  7. Pushing local commits to remote repository:<br/><code>git push</code><br/><code>git push --set-upstream remote-name branch-name</code><br/><code>git push --set-upstream origin master</code>
  8. Switching between branches:<br/><code>git checkout branch-name</code><br/><code>git checkout -b new-branch-name</code><br/><code>git checkout -b main</code>
  9. Merging two branches:<br/><code>git merge second-branch-name</code></br><code>git merge main</code>
  
Note that these commands come with a lot more variants than mentioned above. For more information one can always use command <br/><code>git-command --help</code><br/>that will open a new tab in you browser with the help regarding the respective git-command. Following is an example of this command:<br/><code>git add --help</code>
