# Mypy

### Cases that work:

- ```mypy mypy_working```
- ```mypy src/inner_folder_in_src_not_working```

### Cases that do not work:
- ```mypy src```


# Stubtest

### Cases that work:

- ```python3 -m mypy.stubtest stubtest_working```



### Cases that do not work:
- ```python3 -m mypy.stubtest stubtest_not_working```



## Essentially, we'd like the cases that don't work to be working, in order to have a general solution.