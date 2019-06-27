### Atom config and keymap (qwertz layout (german)) ###

Git repository for [Atom Editor](https://atom.io/) configuration. Mostly Used for python.

## Installation ##

Cloning of the git rep to right ~/.atom/

```
    git clone
```

Installation of the Atom Editor:

```
    wget -qO - https://packagecloud.io/AtomEditor/atom/gpgkey | sudo apt-key add -
    sudo sh -c 'echo "deb [arch=amd64] https://packagecloud.io/AtomEditor/atom/any/ any main" > /etc/apt/sources.list.d/atom.list'
    sudo apt-get update
    sudo apt-get install atom
```

Installation of autopep8

```
    pip install pycodestyle
    pip install autopep8

```


