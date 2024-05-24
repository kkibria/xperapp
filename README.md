# virtual environment
Setup the virtual environment 
```
poetry install
```

Activate the virtual environment
```
poetry shell
```

# build the executable
Use pyinstaller to build the executable,

```
pyinstaller xper.spec
```

this will create an executable inside ``dist``. 
You will need to copy the executable where you will run it from.