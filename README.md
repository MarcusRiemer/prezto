Marcus i3 config
==

  1. Launch Zsh:

        zsh

  2. Clone the repository:

        git clone https://github.com/MarcusRiemer/i3 ${ZDOTDIR:-$HOME}/.i3
        
If you are using kdm as a login manager, add the appropriate .desktop file

        # /usr/share/apps/kdm/sessions/i3.desktop                                                  git:master +
        [Desktop Entry]
        Encoding=UTF-8
        Name=i3
        Comment=This session starts i3
        Exec=/usr/bin/i3
        Type=Application
