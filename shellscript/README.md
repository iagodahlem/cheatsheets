# Shellscript

## Expressions

| Expression | Description |
| :--- | :--- |
| `-d file` | True if file is a directory. |
| `-e file` | True if file exists. |
| `-f file` | True if file exists and is a regular file. |
| `-L file` | True if file is a symbolic link. |
| `-r file` | True if file is a file readable by you. |
| `-w file` | True if file is a file writable by you. |
| `-x file` | True if file is a file executable by you. |
| `file1 -nt file2` | True if file1 is newer than (according to modification time) file2 |
| `file1 -ot file2` | True if file1 is older than file2 |
| `-z string` | True if string is empty. |
| `-n string` | True if string is not empty. |
| `string1 = string2` | True if string1 equals string2. |
| `string1 != string2` | True if string1 does not equal string2. |

## Colors

| Code | Color |
| :--- | :--- |
| 00 | Off |
| 30 | Black |
| 31 | Red |
| 32 | Green |
| 33 | Yellow |
| 34 | Blue |
| 35 | Magenta |
| 36 | Cyan |
| 37 | White |
