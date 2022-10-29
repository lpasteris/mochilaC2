issab@LAPTOP-G553SF2I MINGW64 ~/OneDrive/Escritorio/bootcamp-001/digital_house/Intro_tarea_3
$ git clone https://github.com/zuki2610/Introduccionalainformatica.git
Cloning into 'Introduccionalainformatica'...
remote: Enumerating objects: 3, done.
remote: Counting objects: 100% (3/3), done.
remote: Compressing objects: 100% (2/2), done.
remote: Total 3 (delta 0), reused 0 (delta 0), pack-reused 0
Receiving objects: 100% (3/3), done.

issab@LAPTOP-G553SF2I MINGW64 ~/OneDrive/Escritorio/bootcamp-001/digital_house/Intro_tarea_3
$ cd Introduccionalainformatica

issab@LAPTOP-G553SF2I MINGW64 ~/OneDrive/Escritorio/bootcamp-001/digital_house/Intro_tarea_3/Introduccionalainformatica (main)
$ touch app.js

issab@LAPTOP-G553SF2I MINGW64 ~/OneDrive/Escritorio/bootcamp-001/digital_house/Intro_tarea_3/Introduccionalainformatica (main)
$ git status
On branch main
Your branch is up to date with 'origin/main'.

Untracked files:
  (use "git add <file>..." to include in what will be committed)
        app.js

nothing added to commit but untracked files present (use "git add" to track)

issab@LAPTOP-G553SF2I MINGW64 ~/OneDrive/Escritorio/bootcamp-001/digital_house/Intro_tarea_3/Introduccionalainformatica (main)
$ git add app.js

issab@LAPTOP-G553SF2I MINGW64 ~/OneDrive/Escritorio/bootcamp-001/digital_house/Intro_tarea_3/Introduccionalainformatica (main)
$ git status
On branch main
Your branch is up to date with 'origin/main'.

Changes to be committed:
  (use "git restore --staged <file>..." to u


  issab@LAPTOP-G553SF2I MINGW64 ~/OneDrive/Escritorio/bootcamp-001/digital_house/Intro_tarea_3/Introduccionalainformatica (main)
$ git commit -m "mi primer commit"
[main a962b8b] mi primer commit
 1 file changed, 0 insertions(+), 0 deletions(-)
 create mode 100644 app.js

issab@LAPTOP-G553SF2I MINGW64 ~/OneDrive/Escritorio/bootcamp-001/digital_house/Intro_tarea_3/Introduccionalainformatica (main)
$ git status
On branch main
Your branch is ahead of 'origin/main' by 1 commit.
  (use "git push" to publish your local commits)

nothing to commit, working tree clean

issab@LAPTOP-G553SF2I MINGW64 ~/OneDrive/Escritorio/bootcamp-001/digital_house/Intro_tarea_3/Introduccionalainformatica (main)
$ git push
Enumerating objects: 4, done.
Counting objects: 100% (4/4), done.
Delta compression using up to 12 threads
Compressing objects: 100% (2/2), done.
Writing objects: 100% (3/3), 277 bytes | 277.00 KiB/s, done.
Total 3 (delta 0), reused 0 (delta 0), pack-reused 0
To https://github.com/zuki2610/Introduccionalainformatica.git
   92c44a1..a962b8b  main -> main

issab@LAPTOP-G553SF2I MINGW64 ~/OneDrive/Escritorio/bootcamp-001/digital_house/Intro_tarea_3/Introduccionalainformatica (main)
$ git status
On branch main
Your branch is up to date with 'origin/main'.

nothing to commit, working tree clean
