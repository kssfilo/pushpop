# PushPop

bash scripts to push/pop files into/from temporary directory (~/.push)

## Installation

Copy files below to pathed directory.

- push
- pop (Symbolic link to push)

## Usage

```bash
#push files/directories
>push some.file somedir

#pop pushed files/directories
>pop

#list pushed files
>push -l
#or
>pop -l

#pop 3 times
>pop -n3

#pop all
>pop -a

#drop head
>pop -d

#drop 3times
>pop -dn3

#drop all
>pop -da
```

## Options(push)

```
push [options] <files>

-l:list stack
```

## Options(pop)

```
pop [options] 

-l:list stack
-n <count> :pop <count> times
-a:pop all
-d:drop(able to use with -n/-a
```

# License

MIT
