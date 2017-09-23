#Shell
What are the different shells installed or available?

``` terminal$ cat /etc/shells ```

it will show something like this:

```
/bin/bash
/bin/csh
/bin/ksh
/bin/sh
/bin/tcsh
/bin/zsh
```

find what is the current shell you are using.

``` terminal$ echo $0 ```

it will show the current shell

```
-bash
```
in this example, we are using ```bash``` as the default shell.

you can change it to a new shell, lets say ```sh```.

```
terminal$ sh

```
next lets find what is the default shell when you start a terminal.

```
terminal$ echo $SHELL
````
this will give you default shell.

```
/bin/bash
```

