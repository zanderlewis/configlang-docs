# Your First Language

A simple config file can look like this:

```Text
[LANG_SETTINGS]
file_extension = mylang
```

This will use the default language syntax, but changes the file extension. To modify the syntax, you can make the config file look like this:

```Text
[LANG_SETTINGS]
file_extension = mylang

[SYNTAX]
PRINT = PRINT
SLC = //
```

The above script makes the `print` syntax `PRINT` instead of `print`. `SLC` stands for `Single Line Comment` and changes the syntax from `#` to `//`.