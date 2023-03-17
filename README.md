# language-forth

This fork includes some highlighting support flash forth and fixes

1. words highlight as illegal if the name is over 15 characters
2. hex numerals highlight properly if the leading charcter is a-f

Adds syntax highlighting to Gforth files in VSCode. Note will work for most Forth files. 

This package was forked from [language-forth](https://github.com/harrypower/language-forth). I added highlighting for the .f files and autoclosing support for `."` and `:`.

## Features

- Syntax highlighting

    ![Screenshoot](images/screenshoot.png)

## Release Notes

Add file extension detection
