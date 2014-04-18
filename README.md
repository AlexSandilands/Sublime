Sublime
=======

NOTE:   If you are trying to save settings, or changing files in the sublime-text-2 folder and
        you are getting things like "You lack the permissions to do that", this is likely because
        the first time you ran Sublime as root (ie sudo sublime ...)
        Simply rm -rf ~/.config/sublime-text-2 , then run sublime (not as root) to generate the config
        files again.

Some settings I prefer to change, to make usability nicer.

Default.sublime-theme is an edit to the default theme. I have made the side bar a darker theme,
rather than the default white. I also made a dark red png to use when highlighting selected rows
such as in the folder tree (on the side bar) or the auto completion table. See the screenshots.

Default (Linux).sublime-keymap has some changes to keybindings. They are listed
in Changed_Key_Bindings.txt

Preferences.sublime-settings has some changed user settings. They are listed in
Changed_User_Settings.txt


Theme:
--------
Note: If the highlighted row in the folder tree or auto complete table is a strange
fluorescent colour then the png is not being found.

Make sure it is called:

- row_highlight_darkred.png

and is in the correct directory:

- Linux: ~/.config/sublime-text-2/Packages/Theme\ -\ Default/
- Windows: "C:Users/User/AppData/Roaming/Sublime Text 2/Packages/Theme - Default/"


Installation:

For Windows:

- Just copy the files into "C:Users/User/AppData/Roaming/Sublime Text 2/Packages/Theme - Default/".
Make a backup file of Default.sublime-theme if you want.


For Linux:

- Make a backup of default theme:

        $ cd ~/.config/sublime-text-2/Packages/Theme\ -\ Default/

        $ cp Default.sublime-theme Default.sublime-theme.backup


- Go back to where the git folder is and copy edited theme and png into packages:

        $ cp Theme/Default.sublime-theme ~/.config/sublime-text-2/Packages/Theme\ -\ Default/

        $ cp Theme/DarkRed.png ~/.config/sublime-text-2/Packages/Theme\ -\ Default/

Key Bindings and User Settings:
--------------------------------
For windows:

Just copy the file into "C:Users/User/AppData/Roaming/Sublime\ Text\ 2/Packages/Default"
and make a backup file somewhere if you like.


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
