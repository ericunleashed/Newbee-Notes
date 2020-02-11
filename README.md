# Newbee-Notes
## Tech
### Generate and add ssh key
* Type command `$ ssh-keygen -t rsa -b 4096 -C "your_email@example.com"` in cmd, press enter to use default file location to save the key and enter passphrase.
* Type command `$ eval $(ssh-agent -s)` to start ssh-agent
* Type command `$ ssh-add ~/.ssh/id_rsa` to add ssh key to agent
* Type command `$ clip < ~/.ssh/id_rsa.pub` to copy ssh key to clipboard
* Go to github Settings -> SSH and GPG keys -> New SSH key, add the key to github account

## Team
