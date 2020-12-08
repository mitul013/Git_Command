# for set user's name and mail_id

 git config --global user.email "mitul.adroja13@gmail.com"
 git config --global user.name "mitul013"


# for staging files
git add -add


# for getting last commited file 
git checkout contact.html

# for all logs
git log

# last some number of commit log
git log -p -3 (last 3 commit)

# for seeing what are changes in file 
git diff (compare working file to staging file)
git diff --staged (compare staging file to last commit)

# if we want direct commit files without staging files
git commit -a -m "commit meassage"

# remove files
git rm filename.txt(remove from git and local)
git rm --cached filename.txt ( only remove from git )

# for create .gitignore file
touch .gitignore

# add remote githubb url (origin is just a name for that url)
git remote add origin url

# show how many remote added
git remote -v

# generate ssh key to your github account
'''https://docs.github.com/en/free-pro-team@latest/github/authenticating-to-github/generating-a-new-ssh-key-and-adding-it-to-the-ssh-agent'''

# copy ssh key to clipboard
cat ~/.ssh/id_rsa.pub

# add that ssh key to github

# codewithharry github video link
'''https://www.youtube.com/watch?v=gwWKnnCMQ5c'''