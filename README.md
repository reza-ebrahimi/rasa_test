## rasa_venv

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