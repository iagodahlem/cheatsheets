[index]: https://github.com/iagodahlem/cheatsheets

# Shellscript

1. [Expressions](#1.0)
2. [Colors](#2.0)

## <a name='1.0'></a> Expressions

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

## <a name='2.0'></a> Colors

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

## <a name='3.0'></a> General

```sh
# Ask for the administrator password upfront
sudo -v


# Tells the shell script to exit if it encounters an error
set -eo pipefail
set -e
```

---

[← Back][index]
