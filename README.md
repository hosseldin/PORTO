# PORTO
This is a Repo for my Portofolio

Setup github repo first on the machine

for credentials, 
1. Create an ssh key using:
    ssh-keygen -t TYPE_HERE_NAME -C "your_email@example.com"
2. Start the SSH agent and add your key:
    eval "$(ssh-agent -s)"
    ssh-add ~/.ssh/id_TYPE_HERE_NAME
3. Copy the public key to your clipboard:
    cat ~/.ssh/id_TYPE_HERE_NAME.pub
4. Add it to GitHub:
    Go to GitHub → Settings → SSH and GPG keys
    Click New SSH key → paste your key → Save
5. Test your connection:
    ssh -T git@github.com
6. Now you can use SSH in your repos:
    Make sure your repo’s remote uses the SSH URL instead of HTTPS:
      git remote -v
    If you see something like:
      origin  https://github.com/username/repo.git (fetch)
      origin  https://github.com/username/repo.git (push)
    Change it to SSH:
      git remote set-url origin git@github.com:username/repo.git

That was for configuring git from local





