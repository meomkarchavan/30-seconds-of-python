---
title: check_file_exist
tags: utility,file,function,beginner
---

Check if file exist.

- Returns `True` if the file exist else return `False`.
- Uses the `os.path.isfile(path)` function which returns true if file is present in given directory.

```py
mport os
def check_file_exist(path):
	return os.path.isfile(path)
```

```py
check_file_exist('check_file_exist.md') #True
```
