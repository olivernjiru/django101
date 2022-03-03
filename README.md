# Django Setup

Install Python.

Check the version by typign this in the command prompt
```
py --version
```

Setting up a virtual environment
```
py -m venv project-name
```

To create a virtual environment:
```
virtualenv name
```


Each time you start a new command prompt, you’ll need to activate the environment again.
To activate the virtual environment
```
project-name\Scripts\activate.bat
```

Install Django
In the command prompt, ensure your virtual environment is active, and execute the following command:
```
py -m pip install Django
```

To verify your Django installation execute the following in the command prompt:
```
django-admin --version
```

To install mysqlclient:
```
pip install mysqlclient
```

To upgrade pip:
```
pip install -U  --upgrade pip
```

After setting up and activating the virtual environment, run the following command:
```
$ python -m pip install -e django/
```



