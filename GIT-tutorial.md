## GIT Tutorial :

### Prerequisite :
Install GIT  : https://git-scm.com/downloads

### Verify GIT version after installation
command:
> git version
> 
result:
> git version 2.24.0.windows.2
> 
### Generate SSH Key
reference : https://docs.github.com/en/authentication/connecting-to-github-with-ssh/generating-a-new-ssh-key-and-adding-it-to-the-ssh-agent

command :
>  ssh-keygen -t ed25519 -C "your-email.com"

check generated key :
>  ls  ~/.ssh

view generated public key
> more ~/.ssh/id_ed25519

### Adding SSH Keys to Github account
- go to : https://github.com/settings/keys
- Add new SSH key
- Copy your public key then save it


### GIT Commands
- Clone existing github repository to local with SSH

    command : 
    > git clone git@github.com:userid/repositoryname.git


### Reference:
Markdown cheatsheet : https://www.markdownguide.org/cheat-sheet/
