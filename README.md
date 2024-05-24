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
pyinstaller xper1.spec
```

this will create a directory,
``xper``, inside ``dist`` where you will the the exe file. 
You will need to copy the entire ``xper`` directory to run the executable.