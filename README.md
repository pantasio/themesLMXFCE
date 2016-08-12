# themesLMXFCE

change keyboard shortcuts

It is really ridiculous! There are 3 (three) different GUI ways to edit the global shortcuts in XFCE:

    Settings|Keyboard|Application Shortcuts
    Settings|Window manager|Keyboard
    Settings|Settings editor|xfce4-keyboard-shortcuts
    
The only way I know for removing/editing the global keyboard shortcuts is to edit one or both of the following files:

    /usr/share/mint-configuration-xfce/xfce4/xfconf/xfce-perchannel-xml/xfce4-keyboard-shortcuts.xml
    ~/.config/xfce4/xfconf/xfce-perchannel-xml/xfce4-keyboard-shortcuts.xml
    
there is also file:

    /etc/xdg/xfce4/xfconf/xfce-perchannel-xml/xfce4-keyboard-shortcuts.xml
