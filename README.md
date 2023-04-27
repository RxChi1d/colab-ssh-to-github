# colab-ssh-to-github

## Outline
- Clone this Repository  
- Generate Key
- Copy the Key
- Clone the Private Repository

## Clone this Repository
```
!git clone https://github.com/RxChi1d/colab-ssh-to-github.git
```

## Generate Key
- Please run the shell script with your email, username, and the path to backup the key (in your Drive).  
- When you run the command, it will ask you some problems, please make them as default. (Enter again and again)
```
!sh /content/colab-ssh-to-github/key-generator.sh "email" "username" "path/to/save/key"
```
- After running, it will show you the key, please copy it, and set the Github. (tutorial: https://docs.github.com/en/authentication/connecting-to-github-with-ssh/adding-a-new-ssh-key-to-your-github-account)  
![Image text]('https://github.com/RxChi1d/colab-ssh-to-github/blob/ea1dc56328ff2bd65d6cb0eeb8826a81e5b885e6/picture/key.png')  

## Copy the Key
If you have the key, you just need to copy the key before running your own code.  
```
!sh /content/colab-ssh-to-github/copy-key.sh "path/of/key"
```

## Clone the Private Repository
You only can clone the Private Repository through "SSH", so please copy the ssh link. (ssh instead of https)
![Image test]()