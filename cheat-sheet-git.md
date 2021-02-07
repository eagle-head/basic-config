# Cheat Sheet to Git commands

### git cat-file options

```sh
$ git cat-file -p <hash> // Contents of the object
```

```sh
$ git cat-file -s <hash> // Size of the object
```

```sh
$ git cat-file -p <hash> // Type of the object
```

### List files in the Staging Area [table format]

```sh
$ git ls-files -s
```

### From Staging Area to Woking directory

```sh
$ git checkout-index -a
```
