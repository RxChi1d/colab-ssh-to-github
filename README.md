# colab-ssh-to-github

## Generate Key
- Please run the shell script with your email, username, and the path to backup the key (in your Drive).  
- When you run the command, it will ask you some problems, please make them as default. (Enter again and again)
```
!sh /content/colab-ssh-to-github/key-generator.sh "email" "username" "path/to/save/key"
```
- After running, it will show you the key, please copy it, and set the Github. (tutorial: https://docs.github.com/en/authentication/connecting-to-github-with-ssh/adding-a-new-ssh-key-to-your-github-account)  
![]('./key.png')  

## Copy the Key
If you have the key, you just need to copy the key before running your own code.  
```
!sh /content/colab-ssh-to-github/copy-key.sh "path/of/key"
```