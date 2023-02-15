# envy
record cmd other .bash_history

## Install
```
curl https://raw.githubusercontent.com/LeafChage/keep/main/keep > ./keep
chmod +x ./keep
```

## How to use
```sh
$ ./keep help
keep record cmd other .bash_history

EXAMPLE:
  $ keep -- echo "hello"
  $ keep -- echo "hello2"
  $ keep list
    > echo hello
    > echo hello2
  $ keep list -t
    > # Wed Feb 15 03:23:18 UTC 2023
    > echo hello
    > # Wed Feb 15 03:23:18 UTC 2023
    > echo hello2

SUBCOMMAND:
  help    show usage
  list    show list
```
