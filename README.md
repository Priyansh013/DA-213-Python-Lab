# Conda Commands

Check present working directory;
```hash
pwd
```

List of all items present in the directory:
```hash
ls
```



Create Virtual environment

```hash
conda create -n NAME
```

Search for avaialable versions:
```hash
conda search LIBRARYNAME
```

after making sure given version is avaialable:
```hash
conda install LIBRARYNAME==LIBRARYVERSION
```
To check the library has installed or not:
```hash
python
>>>import pandas as pd
>>>print(pd.__version__)
```

To exit python environament:
```hash
>>>exit()
```

check list of envirnments available:

```hash
conda env list
```
