# Make
touch Makefile

```bash
all:
  echo hello
```


It's show line starting by ^I if TAB is given to that line and it end the line by $

```bash
cat -e -t -v  Makefile
```


```bash
:%s/^[ ]\+/\t/g
```
