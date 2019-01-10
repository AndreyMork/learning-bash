| Code | Meaning |
|---|---|
| `0` | **stdinput** |
| `1` | **stdout** |
| `2` | **stderror** |

|||
|---|---|
| `>` | redirect `stdout` |
| `>>` | append |
| `2>` | redirect `stderror` |
| `&>` | redirect both **standard output** and **standard error** |
| <code>&#124;</code> | redirect output from one **command** to another **command**. The Difference between <code>&#124;</code> and `>` is that `>` redirects to a **file**. |

`ls -l /bin/usr > ls-output.txt 2>&1` redirecting **stdout** and **stderror** to one file.

`/dev/null` This file is a system device called a bit bucket which accepts input and does nothing with it. To suppress error messages from a command, we do this:
`ls -l /bin/usr 2> /dev/null`



## Filter
`ls /bin /usr/bin | sort | uniq | less`

`uniq -d` only duplicate lines
