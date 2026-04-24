# Hello-Word
Readme: Este projeto é uma pag. de um fotógrafo.

Para iniciar temo que criar um arquivo html depois css e realizar as movimentacoes no javascript.


o comando abaixo é do git bash


osvai@DESKTOP-IGU2CH1 MINGW64 ~/OneDrive/Documentos/Projetos/n
$ git clone https://github.com/Osvairfaria/Hello-Word.git
Cloning into 'Hello-Word'...
remote: Enumerating objects: 3, done.
remote: Counting objects: 100% (3/3), done.
remote: Compressing objects: 100% (2/2), done.
remote: Total 3 (delta 0), reused 0 (delta 0), pack-reused 0 (
from 0)
Receiving objects: 100% (3/3), done.

osvai@DESKTOP-IGU2CH1 MINGW64 ~/OneDrive/Documentos/Projetos/new-githab
$

----------------------------------------------------------------------------

Processo subir push - após as modificações


osvai@DESKTOP-IGU2CH1 MINGW64 ~/OneDrive/Documentos/Projetos/new-githab
$ ls
Hello-Word/  new-repositorio-autenticacao-dio/

osvai@DESKTOP-IGU2CH1 MINGW64 ~/OneDrive/Documentos/Projetos/new-githab
$ git status
fatal: not a git repository (or any of the parent directories)
: .git

osvai@DESKTOP-IGU2CH1 MINGW64 ~/OneDrive/Documentos/Projetos/new-githab
$ cd hello-word

osvai@DESKTOP-IGU2CH1 MINGW64 ~/OneDrive/Documentos/Projetos/new-githab/hello-word (main)
$ ls
README.md

osvai@DESKTOP-IGU2CH1 MINGW64 ~/OneDrive/Documentos/Projetos/new-githab/hello-word (main)
$ git status
On branch main
Your branch is up to date with 'origin/main'.

Changes not staged for commit:
  (use "git add <file>..." to update what will be committed)
  (use "git restore <file>..." to discard changes in working d
irectory)
        modified:   README.md

no changes added to commit (use "git add" and/or "git commit -
a")

osvai@DESKTOP-IGU2CH1 MINGW64 ~/OneDrive/Documentos/Projetos/new-githab/hello-word (main)
$ git add .

osvai@DESKTOP-IGU2CH1 MINGW64 ~/OneDrive/Documentos/Projetos/new-githab/hello-word (main)
$ git commit -m "Atualizando 4"
[main ffed96b] Atualizando 4
 1 file changed, 20 insertions(+)

osvai@DESKTOP-IGU2CH1 MINGW64 ~/OneDrive/Documentos/Projetos/new-githab/hello-word (main)
$ git push origin main
Enumerating objects: 5, done.
Counting objects: 100% (5/5), done.
Delta compression using up to 4 threads
Compressing objects: 100% (2/2), done.
Writing objects: 100% (3/3), 611 bytes | 152.00 KiB/s, done.
Total 3 (delta 0), reused 0 (delta 0), pack-reused 0 (from 0)
To https://github.com/Osvairfaria/Hello-Word.git
   15dfd69..ffed96b  main -> main

osvai@DESKTOP-IGU2CH1 MINGW64 ~/OneDrive/Documentos/Projetos/new-githab/hello-word (main)
$ ssh-keygen
Generating public/private ed25519 key pair.
Enter file in which to save the key (/c/Users/osvai/.ssh/id_ed25519):
Created directory '/c/Users/osvai/.ssh'.
Enter passphrase for "/c/Users/osvai/.ssh/id_ed25519" (empty for no passphrase):
Enter same passphrase again:
Your identification has been saved in /c/Users/osvai/.ssh/id_ed25519
Your public key has been saved in /c/Users/osvai/.ssh/id_ed25519.pub
The key fingerprint is:
SHA256:2nSiHYds/3mkJKGWOnszZdhQbCuq1Eawe20+Vd+7jRM osvai@DESKTOP-IGU2CH1
The key's randomart image is:
+--[ED25519 256]--+
|         .       |
|    .     +      |
|     o   o .     |
|    . ..o.o .    |
|     + oSBoo . . |
|    o =BB** . E .|
|   . +o=o+.o o ..|
|    . o *  ...oo.|
|      .+ +  o..oo|
+----[SHA256]-----+

osvai@DESKTOP-IGU2CH1 MINGW64 ~/OneDrive/Documentos/Projetos/new-githab/hello-word (main)
$
ok tudo pronto.

--------------------------------------------------------------------------------------


agora é mudando o push do https para SSH como chaves de autenticações


vide abaixo:




osvai@DESKTOP-IGU2CH1 MINGW64 ~/OneDrive/Documentos/Projetos/new-githab/hello-word (main)

>>>>>> (   $ git remote set-url origin git@github.com:Osvairfaria/Hello-Word.git    ) <<<<<<<

osvai@DESKTOP-IGU2CH1 MINGW64 ~/OneDrive/Documentos/Projetos/new-githab/hello-word (main)
$ git status
On branch main
Your branch is up to date with 'origin/main'.

Changes not staged for commit:
  (use "git add <file>..." to update what will be committed)
  (use "git restore <file>..." to discard changes in working d
irectory)
        modified:   README.md

no changes added to commit (use "git add" and/or "git commit -
a")

osvai@DESKTOP-IGU2CH1 MINGW64 ~/OneDrive/Documentos/Projetos/new-githab/hello-word (main)
$ git add .

osvai@DESKTOP-IGU2CH1 MINGW64 ~/OneDrive/Documentos/Projetos/new-githab/hello-word (main)
$ git commit -m "Atualizando redname 1"
[main 8d3cf76] Atualizando redname 1
 1 file changed, 1 insertion(+)

osvai@DESKTOP-IGU2CH1 MINGW64 ~/OneDrive/Documentos/Projetos/new-githab/hello-word (main)
$ git push origin main
The authenticity of host 'github.com (4.228.31.150)' can't be
established.
ED25519 key fingerprint is: SHA256:+DiY3wvvV6TuJJhbpZisF/zLDA0
zPMSvHdkr4UvCOqU
This key is not known by any other names.
Are you sure you want to continue connecting (yes/no/[fingerpr
int])? yes
Warning: Permanently added 'github.com' (ED25519) to the list
of known hosts.
Enumerating objects: 5, done.
Counting objects: 100% (5/5), done.
Delta compression using up to 4 threads
Compressing objects: 100% (2/2), done.
Writing objects: 100% (3/3), 298 bytes | 149.00 KiB/s, done.
Total 3 (delta 1), reused 0 (delta 0), pack-reused 0 (from 0)
remote: Resolving deltas: 100% (1/1), completed with 1 local o
bject.
To github.com:Osvairfaria/Hello-Word.git
   2ea42be..8d3cf76  main -> main

osvai@DESKTOP-IGU2CH1 MINGW64 ~/OneDrive/Documentos/Projetos/new-githab/hello-word (main)
$


