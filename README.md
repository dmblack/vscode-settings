# vscode-settings
This is just a repository for my VS Code favorite settings, which then allows me to properly communciate them between all my development devices and environments.

##Installation:

###Copy / Paste (Easiest)
* Open VSCode
* Click: File -> Preferences -> User Settings (Or Workspace, should you want them project specific)
* Pase in configuration

###Clone to Config Path
    
Note: VSCode stores user settings.json in (Linux) ~/.config/Code/User (Mac) $HOME/Library/Application Support/Code/User - however it should be empty to begin with.
Linux:
* mv ~/.config/Code/User ~/.config/Code/User.temp
* git clone https://github.com/dmblack/vscode-settings.git ~/.config/Code/User
* cp -Rpv ~/.config/Code/User.temp/[ws]* ~/.config/Code/User/

MAC: 
* mv $HOME/Library/Application\ Support/Code/User $HOME/Library/Application\ Support/Code/User.temp
* git clone https://github.com/dmblack/vscode-settings.git $HOME/Library/Application\ Support/Code/User/
* cp -Rpv $HOME/Library/Application\ Support/Code/User.temp/[ws]* $HOME/Library/Application\ Support/Code/User/
