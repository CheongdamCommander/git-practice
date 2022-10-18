# shell commands
### practice-1  
---
```sh  
Last login: Tue Sep 27 23:13:34 on ttys001
parkchanmin@bagchanmin-ui-MacBookPro ~ % pwd
/Users/parkchanmin
parkchanmin@bagchanmin-ui-MacBookPro ~ % ls
Applications			Public
Desktop				coding test
Documents			node_modules
Downloads			nodejsproject
Library				package-lock.json
Movies				package.json
Music				tempCodeRunnerFile.python
Pictures			webp
parkchanmin@bagchanmin-ui-MacBookPro ~ % cd Pictures
parkchanmin@bagchanmin-ui-MacBookPro Pictures % ls
Photos Library.photoslibrary		Photo Booth 보관함
parkchanmin@bagchanmin-ui-MacBookPro Pictures % ls -lh
total 0
drwxr-xr-x@ 8 parkchanmin  staff   256B  9 27 23:34 Photos Library.photoslibrary
drwxr-xr-x@ 6 parkchanmin  staff   192B  9  2 17:56 Photo Booth 보관함
parkchanmin@bagchanmin-ui-MacBookPro Pictures % cd ..
parkchanmin@bagchanmin-ui-MacBookPro ~ % ls
Applications			Public
Desktop				coding test
Documents			node_modules
Downloads			nodejsproject
Library				package-lock.json
Movies				package.json
Music				tempCodeRunnerFile.python
Pictures			webp
parkchanmin@bagchanmin-ui-MacBookPro ~ % cd/Documents
zsh: no such file or directory: cd/Documents
parkchanmin@bagchanmin-ui-MacBookPro ~ % cd Documents
parkchanmin@bagchanmin-ui-MacBookPro Documents % ls
Arduino			League of Legends	Zoom
parkchanmin@bagchanmin-ui-MacBookPro Documents % cd ..
parkchanmin@bagchanmin-ui-MacBookPro ~ % cd/Documents/Zoom
zsh: no such file or directory: cd/Documents/Zoom
parkchanmin@bagchanmin-ui-MacBookPro ~ % mkdir newfile
parkchanmin@bagchanmin-ui-MacBookPro ~ % pwd
/Users/parkchanmin
parkchanmin@bagchanmin-ui-MacBookPro ~ % cd Documents
parkchanmin@bagchanmin-ui-MacBookPro Documents % ls
Arduino			League of Legends	Zoom
parkchanmin@bagchanmin-ui-MacBookPro Documents % cd Zoom
parkchanmin@bagchanmin-ui-MacBookPro Zoom % mv Zoom New_Zoom
mv: rename Zoom to New_Zoom: No such file or directory
parkchanmin@bagchanmin-ui-MacBookPro Zoom % rm Zoom
rm: Zoom: No such file or directory
parkchanmin@bagchanmin-ui-MacBookPro Zoom % cd ..
parkchanmin@bagchanmin-ui-MacBookPro Documents % pwd
/Users/parkchanmin/Documents
parkchanmin@bagchanmin-ui-MacBookPro Documents % ls 
Arduino			League of Legends	Zoom
parkchanmin@bagchanmin-ui-MacBookPro Documents % League of Legends
zsh: command not found: League
parkchanmin@bagchanmin-ui-MacBookPro Documents % pwd
/Users/parkchanmin/Documents
parkchanmin@bagchanmin-ui-MacBookPro Documents % cd League of Lengends
cd: too many arguments
parkchanmin@bagchanmin-ui-MacBookPro Documents % cd Arduino
parkchanmin@bagchanmin-ui-MacBookPro Arduino % pwd
/Users/parkchanmin/Documents/Arduino
parkchanmin@bagchanmin-ui-MacBookPro Arduino % ls -lh
total 0
drwxr-xr-x  3 parkchanmin  staff    96B  9  7 14:26 libraries
parkchanmin@bagchanmin-ui-MacBookPro Arduino % exit

Saving session...
...copying shared history...
...saving history...truncating history files...
...completed.

[프로세스 완료됨] 
```



