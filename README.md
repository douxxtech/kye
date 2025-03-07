# Kye - Kill Your Existance
Kye is your ultimate weapon against broken processes.

### What ?
Kye allows you to kill **ALL** the processes from an user, to completly eliminate the his existance.

### Installation
Run this command on your linux / darwin operating system:

```shell
curl -sSL "https://setup.dpip.lol/kye" | sudo bash
```


### Usage
```shell
kye [OPTION]... [USERNAME/UID]
  --force               use SIGKILL instead of SIGTERM
  --no-preserve-me      allow killing your own session
  --help                display this help and exit
  --version             output version information and exit
By default, kye sends SIGTERM to all processes of the specified user.
If no user is specified, the current user is assumed.
To kill another user's processes, root privileges are required.
```

### Credits
Made by [douxx](https://github.com/douxxtech/), licensed under [GPL-3.0](LICENSE)