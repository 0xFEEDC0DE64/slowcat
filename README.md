# slowcat
A very slow cat

## Examples
```
slowcat filename

( echo ab ; echo cd ; echo ef ; echo gh ) | slowcat

SLOWCAT_DELAY=.1 slowcat --help

timeout screen /dev/ttyUSB0 115200 ; SLOWCAT_DELAY=.05 slowcat filename > /dev/ttyUSB0
```
