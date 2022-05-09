# KiBot Debian repository

## How to use


1. Add the repo as a valid source for packages:

```shell
¤ wget https://set-soft.github.io/debian/kibot.list
¤ sudo cp kibot.list /etc/apt/sources.list.d/
```

2. Add the repo signature to your system:

```shell
¤ wget https://set-soft.github.io/debian/kibot.gpg
¤ sudo cp kibot.gpg /etc/apt/
```

3. Update your list of packages:

```shell
¤ sudo apt-get update
```

4. Install the main package:

```shell
¤ sudo apt-get install kibot
```

