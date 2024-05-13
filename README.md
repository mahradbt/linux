# Linux Scripts


## Setup bash environment

1. run `./ubuntu-setup.sh`

2. place `bash_extra`

```bash
cp bash_extra ~/.bash_extra
```

3. copy bash_extra and use it

add below code at the end of `.bashrc`

```bash
if [ -f ~/.bash_extra ]; then
    . ~/.bash_extra
fi

```


