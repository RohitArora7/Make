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



ERROR
```bash
Makefile:2: *** missing separator (did you mean TAB instead of 8 spaces?).  Stop
Makefile:6: *** missing separator.  Stop.

