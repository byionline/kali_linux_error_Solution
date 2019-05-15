# kali_linux_error_Solution


## 1. sudo apt-get update error public key is not available: NO_PUBKEY
### solution:  

### gpg --keyserver pgp.mit.edu --recv-keys YOUR KEY DISPLAYED ON CONSOLE

### gpg --armor --export YOUR KEY DISPLAYED ON CONSOLE | sudo apt-key add -
