Boo keyboard layout for macOS
===========

[Boo Layout](https://ballerboo.github.io/boolayout/) packaged as a keylayout bundle includes custom icon, similar in style to the system icons for other layouts like Dvorak or Colemak.

## Installation

 1. Copy the layout(s) to a `Keyboard Layouts` directory. Choose one of the following options:
 
    - Option 1 (recommended). Copy `Boo.bundle` to `/Library/Keyboard Layouts/`. It requires administrator
    rights but this enables the layout system-wide, including the macOS login screen.
    
      To enable input options on the login window, check the option in
      **System Preferences > Users & Groups > Login Options > Show Input menu in login window**.
      
    - Option 2. Copy `Boo.bundle` to `~/Library/Keyboard Layouts/`. It doesn't require admin rights.
      The layout is only available to the currently logged-in user.
   
 1. Log out of macOS and log back in.
 1. Open **System Preferences > Language & Region > Keyboard Preferences > Input Sources** and enable the
    Boo layout of your choice.
 1. Make sure that the **Show Input menu in menu bar** box is checked.
 
To switch quickly between layouts you can press **Command+Space** or **Command+Option+Space**. This hotkey combination conflicts with the default settings for showing Spotlight. Open **System Preferences > Keyboard > Shortcuts** and ensure the Spotlight  shorcut is different from the Keyboard and Input Sources shortcuts.
