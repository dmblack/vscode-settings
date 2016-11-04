# vscode-settings
This is just a repository for my VS Code favorite settings, which then allows me to properly communciate them between all my development devices and environments.

Simply click -> File -> Preferences -> User Settings (Or Workspace, should you want them project specific), and paste the file settings in.

VSCode stores user settings.json in ~/.config/Code/User - however it should be empty to begin with.

    mv ~/.config/Code/User ~/.config/Code/User.temp
    git clone https://github.com/dmblack/vscode-settings.git ~/.config/Code/User
    cp -Rpv ~/.config/Code/User.temp/snippets ~/.config/Code/User/
    cp -Rpv ~/.config/Code/User.temp/workspaceStorage ~/.config/Code/User/