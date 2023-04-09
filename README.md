# A Script that can be run to set up your new shiny mac or slaptop unix machine #

## Step 1 ##
You will have to clone this repo which may require you to sighn into github and add your ssh key (this may not be necessary and may automate this at a later stage)

1.) generate ssh key used for github authentication
``` ssh-keygen -t ed25519 -C "your_email@example.com" ```

2.) place ssh key in github keys; following command copies the key you will have to login in browser manually adding the key
```pbcopy < ~/.ssh/id_ed25519.pub ```

3.) install git 

4.) clone the repo
``` git clone git@github.com:ollieellis/newPCwhoDis.git ```

