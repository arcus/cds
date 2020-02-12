# cds

### February 13th, 2020

1. do you have a GitHub account?    
1. ssh keys    
1. From terminal: ls -al ~/.ssh    
1. Look for one of these:        
      * id_rsa.pub        
      * id_ecdsa.pub        
      * id_ed25519.pub
1. If you don't have an existing key    
      * ssh-keygen -t rsa -b 4096 -C "your_email@example.com"
      * Accept the default file location    
      * Create a secure passphrase
1. see https://help.github.com/en/github/authenticating-to-github/generating-a-new-ssh-key-and-adding-it-to-the-ssh-agent#generating-a-new-ssh-key for more about adding keys.

1. git init -b cds    
1. touch my_initials_file 
1. git add my_initials_file
1. git commit -m "touched a file"    
1. git remote add origin https://github.com/arcus/cds.git    
1. git push -u origin master    
1. Look at it from GitHub's perspective     

### Or

1. git clone git@github.com:braunsb/afraid-to-commit.git
