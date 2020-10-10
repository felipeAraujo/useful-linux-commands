# useful-linux-commands
Just commands to be used on linux terminal

# dependencies
Programs that need to be installed before you can use all of these commands

```
xclip
mg123
```

# steps
You just need to run the command below:

```
mkdir commands-temp &&
cp -r commands/* commands-temp &&
chmod -R u+x commands-temp/ &&
sudo mv commands-temp/* /usr/local/bin &&
rmdir commands-temp
```

Following this command you will:

- Create a new directory (commands-temp)
- Create a copy of the commands in this new directory (commands-temp)
- made all comands inside commands-temp executable
- Move all commands inside commands-temp to /usr/local/bin
- Delete commands-temp directory