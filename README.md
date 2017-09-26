* This repo illustrates the use of submodules
* See [Chapter 7.11 Git Tools - Submodules](https://git-scm.com/book/en/v2/Git-Tools-Submodules) of the Git Book

```
[~/local/src/javascript/evalua-module/create-a-npm-module(master)]$ git submodule add git@github.com:ULL-ESIT-DSI-1617/scapegoat.git
Cloning into '/Users/casiano/local/src/javascript/evalua-module/create-a-npm-module/scapegoat'...
remote: Counting objects: 127, done.
remote: Total 127 (delta 0), reused 0 (delta 0), pack-reused 127
Receiving objects: 100% (127/127), 1.16 MiB | 1.12 MiB/s, done.
Resolving deltas: 100% (43/43), done.
[~/local/src/javascript/evalua-module/create-a-npm-module(master)]$ ls -ltra
total 16
drwxr-xr-x  10 casiano  staff  340 26 sep 12:35 ..
-rw-r--r--   1 casiano  staff  160 26 sep 12:36 README.md
drwxr-xr-x  11 casiano  staff  374 26 sep 12:38 scapegoat
-rw-r--r--   1 casiano  staff   96 26 sep 12:38 .gitmodules
drwxr-xr-x  13 casiano  staff  442 26 sep 12:38 .git
drwxr-xr-x   6 casiano  staff  204 26 sep 12:38 .
[~/local/src/javascript/evalua-module/create-a-npm-module(master)]$ cat .gitmodules 
[submodule "scapegoat"]
path = scapegoatpegoat
url = git@github.com:ULL-ESIT-DSI-1617/scapegoat.git
[~/local/scapegoatrc/javascript/evalua-module/create-a-npm-module(master)]$ git submodule add git@github.com:ULL-ESIT-DSI-1617/prueba-scapegoat.git
Cloning into '/Users/casiano/local/src/javascript/evalua-module/create-a-npm-module/prueba-scapegoat'...
remote: Counting objects: 9, done.
remote: Compressing objects: 100% (7/7), done.
remote: Total 9 (delta 2), reused 8 (delta 1), pack-reused 0
Receiving objects: 100% (9/9), done.
Resolving deltas: 100% (2/2), done.
~/local/src/javascript/evalua-module/create-a-npm-module(master)]$ cat .gitmodules 
[submodule "scapegoat"]
path = scapegoat
url = git@github.com:ULL-ESIT-DSI-1617/scapegoat.git
[submodule "prueba-scapegoat"]
path = prueba-scapegoat
url = git@github.com:ULL-ESIT-DSI-1617/prueba-scapegoat.gitt
```
