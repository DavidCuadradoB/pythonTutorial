## Virtual environment

### Install virtualenvwrapper: 
```
    pip install virtualenvwrapper-win
```

### Create virtual environment:
```
    mkvirtualenv myproject
```

### Activate the environment:
```
    workon myproject
```

### Install pylint and configurate vscode to use the correct env:
```
    - pip install pylint
    - Ctrl+Shift+P -> Python: Select Interpreter -> Select the python env interpreter. 

```

### Migrate the project:
```
    py manage.py migrate
```

### Create migrations model code:
```
    py manage.py makemigrations polls
```

### Migrate the generated code:
```
    py manage.py sqlmigrate polls 0001
```