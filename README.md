## rasa_venv

### install git-lfs (Git Large File Storage)
```console
$ wget https://github.com/git-lfs/git-lfs/releases/download/v2.4.2/git-lfs-linux-amd64-2.4.2.tar.gz
$ tar -xzvf git-lfs-linux-amd64-2.4.2.tar.gz
$ cd git-lfs-linux-amd64-2.4.2
$ ./install.sh # it will prints "Git LFS initialized."
```

### setup
```console
$ git clone https://github.com/reza-ebrahimi/rasa_venv.git
$ cd rasa_venv
$ tar -xvzf archive/venv.tar.gz venv
```

### activate environment
```console
$ source venv/bin/activate
(venv) $
```

### deactivate environment
```console
(venv) $ deactivate
$
```

### running restrauntbot example
```console
(venv) $ cd restaurantbot/
(venv) $ python bot.py train-nlu
(venv) $ python bot.py train-dialogue
(venv) $ python bot.py run
```