# py_config
TO AVOID DUPLICATION WHEN SAVING AND LOADING KEY VALUES MUST BE STRINGS.

A module designed for use as a configuration file.

For global use accross multiple modules use

```from py_config import GLOBAL_CONFIG```

For use as a standalone config file use

```from py_config import config

myconfig = config()```

You can use it like any other dictionary.
