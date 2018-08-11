## Makes it easy when adding, commit and pushing files to repo

For Ubuntu, Linux, raspberry pi and macos (OSX) <br>

<br>
<br>

## Install:

You can use the install script:

```
cd ~/
git clone https://github.com/WestleyK/easy-push
cd easy-push/
./make install
```

Or you can install manualy:

```
cd ~/
git clone https://github.com/WestleyK/easy-push
cd easy-push/
sudo cp hub-push /usr/local/bin/
```

<br>
<br>

## Usage:

This long example should demonstrate what it does and how to use it:

```
$ cd your-repo/
$ ls
README.md     LICENSE    main.sh    install.sh    hello.c    Makefile
$ git pull origin master
From https://github.com/<YOUR_REPO>
 * branch            master     -> FETCH_HEAD
Already up to date.
$ touch foo.sh
$ touch bar.txt
$ hub-push
Enter commit for: foo.sh
[added foo.sh]
Enter commit for: bar.txt
[added bar.txt]
Pushing repo...
Counting objects: 6, done.
Delta compression using up to 12 threads.
Compressing objects: 100% (6/6), done.
Writing objects: 100% (6/6), 1.55 KiB | 1.55 MiB/s, done.
Total 6 (delta 1), reused 0 (delta 0)
remote: Resolving deltas: 100% (1/1), done.
To https://github.com/<YOUR_REPO>
   2da96cd..3b53e45  master -> master
Branch 'master' set up to track remote branch 'master' from 'origin'.
Done.
$
```






<br>
<br>

## End README

<br>
<br>



