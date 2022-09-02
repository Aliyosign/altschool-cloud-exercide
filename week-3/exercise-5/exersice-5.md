### output of command `git config -l`
``` shell
$ git config -l
diff.astextplain.textconv=astextplain
filter.lfs.clean=git-lfs clean -- %f
filter.lfs.smudge=git-lfs smudge -- %f
filter.lfs.process=git-lfs filter-process
filter.lfs.required=true
http.sslbackend=openssl
http.sslcainfo=C:/Program Files/Git/mingw64/ssl/certs/ca-bundle.crt
core.autocrlf=true
core.fscache=true
core.symlinks=false
core.usebuiltinfsmonitor=true
core.fsmonitor=true
pull.rebase=false
credential.helper=manager-core
credential.https://dev.azure.com.usehttppath=true
init.defaultbranch=master
filter.lfs.clean=git-lfs clean -- %f
filter.lfs.smudge=git-lfs smudge -- %f
filter.lfs.process=git-lfs filter-process
filter.lfs.required=true
user.name=alice
user.email=aliceeneyo@gmail.com
core.editor=emacs
core.repositoryformatversion=0
core.filemode=false
core.bare=false
core.logallrefupdates=true
core.symlinks=false
core.ignorecase=true
remote.origin.url=https://gitlab.com/Aliyosign/altschool-cloud-exercise.git
remote.origin.fetch=+refs/heads/*:refs/remotes/origin/*
branch.main.remote=origin
branch.main.merge=refs/heads/main
```
<br>

### output for  `git remote -v `
```
origin  https://gitlab.com/Aliyosign/altschool-cloud-exercise.git (fetch)
origin  https://gitlab.com/Aliyosign/altschool-cloud-exercise.git (push)
```

### output for `git log`
```
commit ab9a0e79a83d707b3433d81f925eb57e3d406af7 (HEAD -> main, origin/main)
Author: alice eneyo <aliceeneyo@gmail.com>
Date:   Tue Aug 23 21:43:00 2022 -0700

    added the vagrantfile

commit 1b3b151f715438149f6998767e9c064caf1cc1eb
Author: alice eneyo <aliceeneyo@gmail.com>
Date:   Mon Aug 22 18:18:52 2022 -0700

    commiting my exercise

commit c6775216d5b8dc5d2647f689baa920b71654a255
Author: Alice Eneyo <aliceeneyo@gmail.com>
Date:   Sun Aug 21 17:29:23 2022 -0700

    Update README.md

commit 7b236fa6633c2a4c142547edfea441a384d52726
Author: Alice Eneyo <aliceeneyo@gmail.com>
Date:   Sun Aug 21 17:28:44 2022 -0700

    Initial commit
```
