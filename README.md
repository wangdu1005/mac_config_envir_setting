# mac_config_envir_setting
This is jiro9611 mac environment setting, which including software tools install and system setting

## Where is my .nvm? (.nvm is a hidden folder)
/Users/jiro9611/.nvm


## How to setting the .nvm path into ~/.bashrc_profile?
https://github.com/creationix/nvm/issues/576

Add these two line into ~/.bashrc_profile file
'''
export NVM_DIR=~/.nvm
source ~/.nvm/nvm.sh
'''

## Where is my ~/.bashrc_profile?
you should create this file under ~ (root file)
