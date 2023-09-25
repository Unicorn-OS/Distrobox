# Favorite:
## Keyboard Binding per Distro/Toolbox
- [How I use distrobox on Fedora Silverblue](https://youtu.be/Q2PrISAOtbY)

Quote:
>Jorge, could you please tell us what the keyboard comand to launch the terminal in the respective profile is? is it "gnome-terminal -profile=yourprofile?"
>
>@JorgeCastro
>It's --profile=name, two dashes!

Relation:
- Gnome-terminal profiles https://help.gnome.org/users/gnome-terminal/stable/pref-profiles.html.en
- Gnome-terminal Export profile https://unix.stackexchange.com/questions/448811/how-to-export-a-gnome-terminal-profile
- Gnome Export custom keyboard shortcuts https://discussion.fedoraproject.org/t/how-to-export-save-shortcuts-in-gnome/75199, 


Source:
```
# Keyboard
dconf dump /org/gnome/settings-daemon/plugins/media-keys/custom-keybindings/ > custom.txt
# Gnome-Terminal profile
dconf dump /org/gnome/terminal/legacy/profiles:/ > gnome-terminal-profiles.dconf
```
