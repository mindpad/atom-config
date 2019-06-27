### Atom config and keymap (qwertz layout (german)) ###

Git repository for [Atom Editor](https://atom.io/) configuration.

## Installation ##

Cloning of the git rep to right ~/.atom/

```
    git clone git@github.com:mindpad/atom-config.git .atom
```

Installing Atom Editor:

```
    wget -qO - https://packagecloud.io/AtomEditor/atom/gpgkey | sudo apt-key add -
    sudo sh -c 'echo "deb [arch=amd64] https://packagecloud.io/AtomEditor/atom/any/ any main" > /etc/apt/sources.list.d/atom.list'
    sudo apt-get update
    sudo apt-get install atom
```

Configuring autopep8 - autocorrection for python.

```
    pip install pycodestyle
    pip install autopep8
```


