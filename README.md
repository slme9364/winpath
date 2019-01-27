winpath
===
This is shell script. This program can translate linux path to windows path on wsl. This shell script can use windows path, example `/mnt/c/...`.

# Usage
```
% winpath ~/test.txt

C:/Users/username/AppData/Local/lxxs/home/user/test.txt
```

## Example
open vscode  

```
% code $(winpath ~/test.txt)
```

can use windows path  

```
% winpath /mnt/c/Users/username/Desktop/test.txt

C:/Users/username/Desktop/test.txt
```

```
% cd /mnt/c/Users/username

% winpath test.txt

C:/Users/username/test.txt
```