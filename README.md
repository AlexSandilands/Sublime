Sublime
=======

Some settings I prefer to change, to make usability nicer.

Default.sublime-theme is a slight edit to the default theme. The difference
is that I had made the side bar a darker theme, rather than the default white

Default (Linux).sublime-keymap has some changes to keybindings. They are listed
in Changed_Key_Bindings.txt

Preferences.sublime-settings has some changed user settings. They are listed in
Changed_User_Settings.txt


Theme:
--------
- Make a backup of default theme:

$ cd ~/.config/sublime-text-2/Packages/Theme\ -\ Default/

$ cp Default.sublime-theme Default.sublime-theme.backup


- Go back to where the git folder is and copy edited theme into packages:

$ cp Theme/Default.sublime-theme ~/config/sublime-text-2/Packages/Theme\ -\ Default/


Key Bindings and User Settings:
--------------------------------
For windows just copy the file into C:Users/User/AppData/Roaming/Sublime\ Text\ 2/Packages/Default
and make a backup file somewhere if you like


For Linux:
- Backup Key bindings:

$ cd ~/.config/sublime-text-2/Packages/Default

$ cp Default\ \(Linux\).sublime-keymap Default\ \(Linux\).sublime-keymap.backup

- Backup settings:

$ cd ../User

$ cp Preferences.sublime-settings Preferences.sublime-settings.backup


- Go back to the git folder and copy settings and key bindings into packages:

$ cp KeyBindings/Default\ \(Linux\).sublime-keymap ~/.config/sublime-text-2/Packages/Default

$ cp Settings/Preferences.sublime-settings ~/.config/sublime-text-2/Packages/User