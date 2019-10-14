# py_config
TO AVOID DUPLICATION WHEN SAVING AND LOADING KEY VALUES MUST BE STRINGS.

A module designed for use as a configuration file.
Default save location is `TEMP_PATH/py_config.json`, other locations can be set with `myconfig.set_path()` It is recommended to change the default to match your project. 
You are in charge of saving (`config.load()`)and loading(`config.save()`).


## Global
For global use accross multiple modules use

```from py_config import GLOBAL_CONFIG
```

## Standalone
For use as a standalone config file use

```
from py_config import config

myconfig = config() 
```
You can then use it like any other dictionary.
