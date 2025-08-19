# KiBot Debian repository

## How to use


### Debian 13 (trixie) and newers

- Add the repo as a valid source for packages:

```shell
$ wget https://set-soft.github.io/debian/kibot.sources
$ sudo cp kibot.sources /etc/apt/sources.list.d/
```

> [!NOTE]
> The old `.list` file and separate key are now deprecated.
> You can safetly remove them if you downloaded it for Debian 12 and older.

- Update your list of packages:

```shell
$ sudo apt-get update
```

- Install the main package:

```shell
$ sudo apt-get install kibot
```


### Debian 12 (bookworkm) and olders

- Add the repo as a valid source for packages:

```shell
$ wget https://set-soft.github.io/debian/kibot.list
$ sudo cp kibot.list /etc/apt/sources.list.d/
```

- Add the repo signature to your system:

```shell
$ wget https://set-soft.github.io/debian/kibot.gpg
$ sudo cp kibot.gpg /etc/apt/
```

- Update your list of packages:

```shell
$ sudo apt-get update
```

- Install the main package:

```shell
$ sudo apt-get install kibot
```

