EANG+SALA@EANG MINGW64 ~
$ git config --global user.name "JuanOtero03"

EANG+SALA@EANG MINGW64 ~
$ git config --global user.email "oterofernandezjuan@gmail.com"

EANG+SALA@EANG MINGW64 ~
$ git config --global core.editor "code --wait"

EANG+SALA@EANG MINGW64 ~
$ git config --global core.autocrlf true

EANG+SALA@EANG MINGW64 ~
$
EANG+SALA@EANG MINGW64 ~
$ git config --global user.name "JuanOtero03"
bash: EANG+SALA@EANG: command not found
bash: $: command not found

EANG+SALA@EANG MINGW64 ~
$ git config --global core.autocrlf true

EANG+SALA@EANG MINGW64 ~
$ $ git config --global user.name "JuanOtero03"
bash: $: command not found

EANG+SALA@EANG MINGW64 ~
$ git config --global core.editor "code --wait"

EANG+SALA@EANG MINGW64 ~
$ git config --list
diff.astextplain.textconv=astextplain
filter.lfs.clean=git-lfs clean -- %f
filter.lfs.smudge=git-lfs smudge -- %f
filter.lfs.process=git-lfs filter-process
filter.lfs.required=true
http.sslbackend=schannel
core.autocrlf=true
core.fscache=true
core.symlinks=false
pull.rebase=false
credential.helper=manager
credential.https://dev.azure.com.usehttppath=true
init.defaultbranch=master
user.name=JuanOtero03
user.email=oterofernandezjuan@gmail.com
core.editor=code --wait
core.autocrlf=true

EANG+SALA@EANG MINGW64 ~
$ mkdir mi-proyecto-web

EANG+SALA@EANG MINGW64 ~
$ cd mi-proyecto-web

EANG+SALA@EANG MINGW64 ~/mi-proyecto-web
$ cd mi-proyecto-web
bash: cd: mi-proyecto-web: No such file or directory

EANG+SALA@EANG MINGW64 ~/mi-proyecto-web
$ git init
Initialized empty Git repository in C:/Users/SALA2/mi-proyecto-web/.git/

EANG+SALA@EANG MINGW64 ~/mi-proyecto-web (master)
$ git status
On branch master

No commits yet

nothing to commit (create/copy files and use "git add" to track)

EANG+SALA@EANG MINGW64 ~/mi-proyecto-web (master)
$ git add index.html
fatal: pathspec 'index.html' did not match any files

EANG+SALA@EANG MINGW64 ~/mi-proyecto-web (master)
$ git add index.html
fatal: pathspec 'index.html' did not match any files

EANG+SALA@EANG MINGW64 ~/mi-proyecto-web (master)
$ git add index.html
fatal: pathspec 'index.html' did not match any files

EANG+SALA@EANG MINGW64 ~/mi-proyecto-web (master)
$ touch index.html

EANG+SALA@EANG MINGW64 ~/mi-proyecto-web (master)
$ nano index.html

EANG+SALA@EANG MINGW64 ~/mi-proyecto-web (master)
$ git add index.html
warning: in the working copy of 'index.html', LF will be replaced by CRLF the next time Git touches it

EANG+SALA@EANG MINGW64 ~/mi-proyecto-web (master)
$ git status
On branch master

No commits yet

Changes to be committed:
  (use "git rm --cached <file>..." to unstage)
        new file:   index.html


EANG+SALA@EANG MINGW64 ~/mi-proyecto-web (master)
$ git add index.html

EANG+SALA@EANG MINGW64 ~/mi-proyecto-web (master)
$ git commit -m "Añadir pagina inicial"
[master (root-commit) 4621149] Añadir pagina inicial
 1 file changed, 11 insertions(+)
 create mode 100644 index.html

EANG+SALA@EANG MINGW64 ~/mi-proyecto-web (master)
$ nano index.html

EANG+SALA@EANG MINGW64 ~/mi-proyecto-web (master)
$ nano index.html

EANG+SALA@EANG MINGW64 ~/mi-proyecto-web (master)
$ nano estilos.css

EANG+SALA@EANG MINGW64 ~/mi-proyecto-web (master)
$ git status
On branch master
Changes not staged for commit:
  (use "git add <file>..." to update what will be committed)
  (use "git restore <file>..." to discard changes in working directory)
        modified:   index.html

Untracked files:
  (use "git add <file>..." to include in what will be committed)
        estilos.css

no changes added to commit (use "git add" and/or "git commit -a")

EANG+SALA@EANG MINGW64 ~/mi-proyecto-web (master)
$ git add index.html estilos.css
warning: in the working copy of 'index.html', LF will be replaced by CRLF the next time Git touches it
warning: in the working copy of 'estilos.css', LF will be replaced by CRLF the next time Git touches it

EANG+SALA@EANG MINGW64 ~/mi-proyecto-web (master)
$ git diff

EANG+SALA@EANG MINGW64 ~/mi-proyecto-web (master)
$ git add index.html estilos.css

EANG+SALA@EANG MINGW64 ~/mi-proyecto-web (master)
$ git diff -staged
error: invalid option: -staged
usage: git diff [<options>] [<commit>] [--] [<path>...]
   or: git diff [<options>] --cached [--merge-base] [<commit>] [--] [<path>...]
   or: git diff [<options>] [--merge-base] <commit> [<commit>...] <commit> [--] [<path>...]
   or: git diff [<options>] <commit>...<commit> [--] [<path>...]
   or: git diff [<options>] <blob> <blob>
   or: git diff [<options>] --no-index [--] <path> <path>

common diff options:
  -z            output diff-raw with lines terminated with NUL.
  -p            output patch format.
  -u            synonym for -p.
  --patch-with-raw
                output both a patch and the diff-raw format.
  --stat        show diffstat instead of patch.
  --numstat     show numeric diffstat instead of patch.
  --patch-with-stat
                output a patch and prepend its diffstat.
  --name-only   show only names of changed files.
  --name-status show names and status of changed files.
  --full-index  show full object name on index lines.
  --abbrev=<n>  abbreviate object names in diff-tree header and diff-raw.
  -R            swap input file pairs.
  -B            detect complete rewrites.
  -M            detect renames.
  -C            detect copies.
  --find-copies-harder
                try unchanged files as candidate for copy detection.
  -l<n>         limit rename attempts up to <n> paths.
  -O<file>      reorder diffs according to the <file>.
  -S<string>    find filepair whose only one side contains the string.
  --pickaxe-all
                show all files diff when -S is used and hit is found.
  -a  --text    treat all files as text.


EANG+SALA@EANG MINGW64 ~/mi-proyecto-web (master)
$ git commit -m "Añadir sección sobre el proyecto y hoja de estilos"
[master fb7901b] Añadir sección sobre el proyecto y hoja de estilos
 2 files changed, 19 insertions(+), 2 deletions(-)
 create mode 100644 estilos.css

EANG+SALA@EANG MINGW64 ~/mi-proyecto-web (master)
$ echo "Este es un archivo temporal" > temporal.txt

EANG+SALA@EANG MINGW64 ~/mi-proyecto-web (master)
$ git add temporal.txt
warning: in the working copy of 'temporal.txt', LF will be replaced by CRLF the next time Git touches it

EANG+SALA@EANG MINGW64 ~/mi-proyecto-web (master)
$ git commit -m "Añadir archivo temporal"
[master a9cf06e] Añadir archivo temporal
 1 file changed, 1 insertion(+)
 create mode 100644 temporal.txt

EANG+SALA@EANG MINGW64 ~/mi-proyecto-web (master)
$ git rm temporal.txt
rm 'temporal.txt'

EANG+SALA@EANG MINGW64 ~/mi-proyecto-web (master)
$ git commit -m "Eliminar archivo temporal"
[master 34320a4] Eliminar archivo temporal
 1 file changed, 1 deletion(-)
 delete mode 100644 temporal.txt

EANG+SALA@EANG MINGW64 ~/mi-proyecto-web (master)
$ nano index.html

EANG+SALA@EANG MINGW64 ~/mi-proyecto-web (master)
$ git restore index.html

EANG+SALA@EANG MINGW64 ~/mi-proyecto-web (master)
$ git log
commit 34320a4616ab25b62ea6adec3658f8ed32ad5c9f (HEAD -> master)
Author: JuanOtero03 <oterofernandezjuan@gmail.com>
Date:   Thu Apr 24 14:51:34 2025 -0500

    Eliminar archivo temporal

commit a9cf06e3d0c3fc566decebe69ce9e3b421d235af
Author: JuanOtero03 <oterofernandezjuan@gmail.com>
Date:   Thu Apr 24 14:50:43 2025 -0500

    Añadir archivo temporal

commit fb7901bf3a4ab05acdc1e60de0fd440fa055ca26
Author: JuanOtero03 <oterofernandezjuan@gmail.com>
Date:   Thu Apr 24 14:49:52 2025 -0500

    Añadir sección sobre el proyecto y hoja de estilos

commit 462114900c683724e4908ecd3a89dda62fca9582
Author: JuanOtero03 <oterofernandezjuan@gmail.com>
Date:   Thu Apr 24 14:42:56 2025 -0500

    Añadir pagina inicial

EANG+SALA@EANG MINGW64 ~/mi-proyecto-web (master)
$  a9cf06e3d0c3fc566decebe69ce9e3b421d235af
bash: a9cf06e3d0c3fc566decebe69ce9e3b421d235af: command not found

EANG+SALA@EANG MINGW64 ~/mi-proyecto-web (master)
$ git reset a9cf06e3d0c3fc566decebe69ce9e3b421d235af --soft

EANG+SALA@EANG MINGW64 ~/mi-proyecto-web (master)
$ git status
On branch master
Changes to be committed:
  (use "git restore --staged <file>..." to unstage)
        deleted:    temporal.txt


EANG+SALA@EANG MINGW64 ~/mi-proyecto-web (master)
$ git commit -m "Restablecer cambios de estilo y sección"
[master b8286e5] Restablecer cambios de estilo y sección
 1 file changed, 1 deletion(-)
 delete mode 100644 temporal.txt

EANG+SALA@EANG MINGW64 ~/mi-proyecto-web (master)
$ git branch desarrollo

EANG+SALA@EANG MINGW64 ~/mi-proyecto-web (master)
$ git branch
  desarrollo
* master

EANG+SALA@EANG MINGW64 ~/mi-proyecto-web (master)
$ git checkout desarrollo
Switched to branch 'desarrollo'

EANG+SALA@EANG MINGW64 ~/mi-proyecto-web (desarrollo)
$ nano contacto.html

EANG+SALA@EANG MINGW64 ~/mi-proyecto-web (desarrollo)
$ git add contacto.html
warning: in the working copy of 'contacto.html', LF will be replaced by CRLF the next time Git touches it

EANG+SALA@EANG MINGW64 ~/mi-proyecto-web (desarrollo)
$ git commit -m "Añadir página de contacto"
[desarrollo b8a00e2] Añadir página de contacto
 1 file changed, 18 insertions(+)
 create mode 100644 contacto.html

EANG+SALA@EANG MINGW64 ~/mi-proyecto-web (desarrollo)
$ nano index.html

EANG+SALA@EANG MINGW64 ~/mi-proyecto-web (desarrollo)
$ git add index.html

EANG+SALA@EANG MINGW64 ~/mi-proyecto-web (desarrollo)
$ git commit -m "Añadir enlace a página de contacto"
[desarrollo 0c8cfe3] Añadir enlace a página de contacto
 1 file changed, 3 insertions(+)

EANG+SALA@EANG MINGW64 ~/mi-proyecto-web (desarrollo)
$ git checkout master
Switched to branch 'master'

EANG+SALA@EANG MINGW64 ~/mi-proyecto-web (master)
$ git merge desarrollo
Updating b8286e5..0c8cfe3
Fast-forward
 contacto.html | 18 ++++++++++++++++++
 index.html    |  3 +++
 2 files changed, 21 insertions(+)
 create mode 100644 contacto.html

EANG+SALA@EANG MINGW64 ~/mi-proyecto-web (master)
$ git checkout -b feature/galeria
Switched to a new branch 'feature/galeria'

EANG+SALA@EANG MINGW64 ~/mi-proyecto-web (feature/galeria)
$ nano galeria.html

