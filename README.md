# linux-mint-helper
A small helper program for Linux Mint meant to ease users into using the terminal.

The goal of this project is to ease users into using the terminal by doing simple tasks like installing an app, or updating the system.

Right now, the program is so small it should work with Ubuntu and Pop!\_OS without any issues.

Also, the code in the main page tends to be incomplete so use the code from the [releases](https://github.com/TheNoGoat/linux-mint-helper/releases) page if you want to work with something kinda stable

# Installing helper

Run helper-installer.sh by typing in

> ./helper-installer.sh

If it says something like "Permission Denied.", run the command

> chmod +x helper-installer.sh

If you already installed helper, it will wipe the previous installation.

# Uninstalling helper

Run helper-remover.sh by typing in

> ./helper-remover.sh

If it says something like "Permission Denied.", run the command

> chmod +x helper-remover.sh

# Running helper

Type

> minthelper

# Compiling helper

If you want to manually compile helper, make sure you have the c compiler `cc` installed. Then you can compile it using the command

> make

And it can be installed using the helper-install.sh script.

# Credits

Since gcc doesn't have the conio library, it doesn't support pretty useful commands like getch().
So, I ended up using [this](https://stackoverflow.com/a/16361724) code from stackoverflow.

And I got some help in cleaning up the code from [TrashCatiCat](https://github.com/TrashCatCait). Do check out her page.
