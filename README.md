# Mypy

### Cases that work:

- ```mypy mypy_working```

### Cases that do not work:
- ```mypy src```

This issue should be connected to the way package are used in mypy because
if you make the `src` package a folder (by removing the __init__.py) then the not working case starts to work.