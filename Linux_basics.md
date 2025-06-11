****How to add the path of repository to your system's path****
1. first check if path is present in the syetm path or not
```
echo $PATH
```
2. If The pasth "ex:/usr/local/bin/" isn't listed, add it:
```
echo 'export PATH=$PATH:/usr/local/bin' >> ~/.bashrc
source ~/.bashrc
```
