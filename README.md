# テクノロジー（藤原） 授業 6/8

今日の授業で打ったコマンドをコピー＆ペーストしてください。

（`irb`や`ruby`の実行結果も含めて全てをコピーしてください）

## ターミナルに打ったコマンド

```
root@DESKTOP-C5R292V:~# ruby -v
ruby 2.5.1p57 (2018-03-29 revision 63029) [x86_64-linux]
root@DESKTOP-C5R292V:~# pwd
/root
root@DESKTOP-C5R292V:~# cd fujiwara
root@DESKTOP-C5R292V:~/fujiwara# pwd
/root/fujiwara
root@DESKTOP-C5R292V:~/fujiwara# cd ..
root@DESKTOP-C5R292V:~# ls -al
total 6
drwx------ 0 root root  512 Jun  8 10:48 .
drwxr-xr-x 0 root root  512 Jan  1  1970 ..
-rw-rw-rw- 1 root root    0 Jun  8 10:46 a
-rw------- 1 root root   38 Jun  6 13:49 .bash_history
-rw-rw-rw- 1 root root  120 Jun  8 10:56 .bash_profile
-rw-r--r-- 1 root root 3106 Oct 23  2015 .bashrc
drwx------ 0 root root  512 May 18 11:41 .config
lrwxrwxrwx 1 root root   38 Apr 27 09:43 fujiwara -> /mnt/c/Users/rei_m/Documents/fujiwara/
lrwxrwxrwx 1 root root   47 Apr 27 09:38 -fujiwara -> /mnt/c/Users/rei_m/Documents/fujiwara/-fujiwara
-rw-rw-rw- 1 root root   66 Apr 27 11:00 .gitconfig
drwxrwxrwx 0 root root  512 May 25 11:57 .ionic
drwxr-xr-x 0 3434 3434  512 May 25 10:33 ionic-tutorial
-rw-rw-rw- 1 root root    0 Jun  7 13:17 kani
drwxrwxrwx 0 root root  512 May 25 10:30 .node-gyp
drwxrwxrwx 0 root root  512 May 25 10:30 .npm
-rw-r--r-- 1 root root  148 Aug 18  2015 .profile
-rw-rw-rw- 1 root root    0 Jun  6 14:49 python
drwxrwxrwx 0 root root  512 Jun  8 11:14 .rbenv
drwx------ 0 root root  512 May 18 10:34 .ssh
-rw------- 1 root root 2034 Jun  8 10:48 .viminfo
root@DESKTOP-C5R292V:~# cd fujiwara
root@DESKTOP-C5R292V:~/fujiwara# ls
hello-github  ruby-chap1-intro
root@DESKTOP-C5R292V:~/fujiwara# cd /mnt/c/Users/rei_m/
root@DESKTOP-C5R292V:/mnt/c/Users/rei_m# ls
スタート メニュー     ntuser.dat{d028cbda-46ba-11e8-89e1-c49ded95c76c}.TM.blf
3D Objects            ntuser.dat{d028cbda-46ba-11e8-89e1-c49ded95c76c}.TMContainer00000000000000000001.regtrans-ms
AppData               ntuser.dat{d028cbda-46ba-11e8-89e1-c49ded95c76c}.TMContainer00000000000000000002.regtrans-ms
Application Data      NTUSER.DAT{e8d65ac5-d676-11e7-89d5-00155df74414}.TM.blf
Contacts              NTUSER.DAT{e8d65ac5-d676-11e7-89d5-00155df74414}.TMContainer00000000000000000001.regtrans-ms
Cookies               NTUSER.DAT{e8d65ac5-d676-11e7-89d5-00155df74414}.TMContainer00000000000000000002.regtrans-ms
Creative Cloud Files  ntuser.dat.log1
Desktop               ntuser.dat.log2
Documents             ntuser.ini
Downloads             OneDrive
Envs                  Pictures
Favorites             Prezi
Links                 PrintHood
Local Settings        Recent
mercurial.ini         Saved Games
MicrosoftEdgeBackups  Searches
Music                 SendTo
My Documents          Templates
NetHood               Videos
ntuser.dat            VirtualBox VMs
root@DESKTOP-C5R292V:/mnt/c/Users/rei_m# cd Documents/
root@DESKTOP-C5R292V:/mnt/c/Users/rei_m/Documents# ls
desktop.ini  fujiwara  My Music  My Pictures  My Videos
root@DESKTOP-C5R292V:/mnt/c/Users/rei_m/Documents# cd fujiwara/
root@DESKTOP-C5R292V:/mnt/c/Users/rei_m/Documents/fujiwara# ls
hello-github  ruby-chap1-intro
root@DESKTOP-C5R292V:/mnt/c/Users/rei_m/Documents/fujiwara# cd ~
root@DESKTOP-C5R292V:~# cd
root@DESKTOP-C5R292V:~# rm fujiwara
root@DESKTOP-C5R292V:~# ln -s /mnt/c/Users/rei_m/OneDrive/
ドキュメント/                          Desktop/                               添付ファイル/
.849C9593-D756-4E56-8D6E-42412F2A707B  desktop.ini                            画像/
root@DESKTOP-C5R292V:~# ln -s /mnt/c/Users/rei_m/OneDrive/ドキュメント/fujiwara/ ~/fujiwara
root@DESKTOP-C5R292V:~# cd fujiwara
root@DESKTOP-C5R292V:~/fujiwara# ls
hello-github  ruby-chap1-intro
root@DESKTOP-C5R292V:~/fujiwara# ruby helloruby.rb
Traceback (most recent call last):
ruby: No such file or directory -- helloruby.rb (LoadError)
root@DESKTOP-C5R292V:~/fujiwara# ls
hello-github  ruby-chap1-intro
root@DESKTOP-C5R292V:~/fujiwara# cd ruby-chap1-intro
root@DESKTOP-C5R292V:~/fujiwara/ruby-chap1-intro# ruby helloruby.rb
Hello, Ruby.
root@DESKTOP-C5R292V:~/fujiwara/ruby-chap1-intro# ruby helloruby.rb
Hello, Ruby.
root@DESKTOP-C5R292V:~/fujiwara/ruby-chap1-intro#
```
