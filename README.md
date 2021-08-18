# pypi-run-directly-from-terminal

## Setting up the application

1. Build your package

```cmd
python setup.py sdist bdist_wheel
```

2. Upload on pypi using twine

```cmd
twine upload dist/*
```

3. Install the package (you can run this in some other directory)

```cmd
pip3 install evil_insult==0.0.1
```

4. Run your application

```cmd
python3 -m evil_insult
```


