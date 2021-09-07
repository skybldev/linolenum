# linolenum - so you know which line of code is which.

Inspired by this junk from a introductory computer science elective "course":

![](https://i.imgur.com/gZBoX64.png)

...which makes me cringe on many, many levels.

# Summary

This script takes a file from stdin and adds a comment after it with the number
of the respective line. The commend delimiter is supplied as an argument.

# Usage

Make sure you `chmod +x` the file before executing. Execute with `./linolenum`.
It will automatically be executed by node because of the shebang, and for the
same reason `node linolenum` will not work.
