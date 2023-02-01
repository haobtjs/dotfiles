# Preview
![alt text ](./preview/1.png)
![alt text ](./preview/2.png)
# Setup
```
sudo pacman -S awesome rofi starship pamixer acpi git flameshot polkit-gnome
```
# Install 
```
git clone https://github.com/haobtjs/dotfiles
cd dotfiles
cd home && cp -a ./ ~/ && cd ..
cd bin && sudo cp -a ./ /bin && cd ..
sudo pacman -U ./packages/picom-ft-labs/picom-ft-labs-1872__2023.01.23-1-x86_64.pkg.tar.zst
#or run :cd packages/picom-ft-labs && makepkg -sic && cd ../../
sudo pacman -U ./packages/i3lock-color/i3lock-color-2.13.c.4-1-x86_64.pkg.tar.zst
#or run : cd packages/i3lock-color && makepkg -sic && cd ../../
tar -xf papirus-nordic.tar.xz -C ~/.icons/
```
# Some shortcut
`Super` + `Enter` : open terminal <br>
`Super` + `f` : open firefox <br>
`Super` + `e` : open file manager <br>
`Super` + `r` : open apps <br>
`Super` + `Shift` + `r` : open launcher <br>
`Super` + `x` : open powermenu <br>
`Super` + `d` : show/hide dock  <br>
`Super` + `s` : show shortcut