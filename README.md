# dockerveth

Show which docker containers are attached to which `veth` interfaces on your server.

# Example

```
[root@dockervisor-1 ~]# dockerveth
CONTAINER ID	VETH       	NAMES
60d27ce962ff	vethe353e93	hopeful_bhaskara
d07a2979e69a	vethe4c3cee	silly_meitner
1e8656e195ba	veth1ce04be	thirsty_meitner
```

# Requirements

- ?


# Installation

1. Download [dockerveth.sh](https://github.com/micahculpepper/dockerveth/raw/master/dockerveth.sh) and save it
wherever you like.

2. Make sure `dockerveth.sh` is executable:

```bash
chmod +x dockerveth.sh
```

3. Symlink `dockerveth.sh` to a program directory. Example:

```bash
# From the directory containing dockerveth.sh:
ln -s "$(pwd)/dockerveth.sh" /usr/local/bin/dockerveth
```

# Usage

```bash
dockerveth
```
_The command does not take any arguments (yet)._

