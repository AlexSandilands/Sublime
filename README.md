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

$ cd ~/.config/sublime-text-2/Packages/Theme\ -\ Default/

$ cp Default.sublime-theme Default.sublime-theme.backup


-- Go back to where the git files are

$ cp Default.sublime-theme ~/config/sublime-text-2/Packages/Theme\ -\ Default/


Key Bindings and User Settings:
--------------------------------

$ cd ~/.config/sublime-text-2/Packages/User

$ cp Default\ (Linux).sublime-keymap Default\ (Linux).sublime-keymap.backup

$ cp Preferences.sublime-settings Preferences.sublime-settings.backup


-- Go back to where the git files are

$ cp Default\ (Linux).sublime-keymap ~/.config/sublime-text-2/Packages/User

$ cp Preferences.sublime-settings ~/.config/sublime-text-2/Packages/User