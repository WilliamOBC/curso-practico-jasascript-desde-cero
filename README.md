# curso-practico-jasascript-desde-cero

Este ejercicio es para Curso Práctico de JavaScript con Git

AHORA VAMOS A CREAR UN REPOSITORIO DESDE CERO

PS C:\Users\T470> cd .\Documents\

PS C:\Users\T470\Documents> cd '.\CURSOS PROGRAMACION\'

PS C:\Users\T470\Documents\CURSOS PROGRAMACION> cd '.\Curso de JS\'

PS C:\Users\T470\Documents\CURSOS PROGRAMACION\Curso de JS> git clone https://github.com/WilliamOBC/curso-practico-jasascript-desde-cero

Cloning into 'curso-practico-jasascript-desde-cero'...
remote: Enumerating objects: 5, done.
remote: Counting objects: 100% (5/5), done.
remote: Compressing objects: 100% (5/5), done.
remote: Total 5 (delta 0), reused 0 (delta 0), pack-reused 0
Receiving objects: 100% (5/5), done.

PS C:\Users\T470\Documents\CURSOS PROGRAMACION\Curso de JS> cd .\curso-practico-jasascript-desde-cero\.git\info\

PS C:\Users\T470\Documents\CURSOS PROGRAMACION\Curso de JS\curso-practico-jasascript-desde-cero\.git\info> ls

    Directorio: C:\Users\T470\Documents\CURSOS PROGRAMACION\Curso de
    JS\curso-practico-jasascript-desde-cero\.git\info

Mode LastWriteTime Length Name

---

-a---- 1/11/2023 9:33 a. m. 240 exclude

PS C:\Users\T470\Documents\CURSOS PROGRAMACION\Curso de JS\curso-practico-jasascript-desde-cero\.git\info> code ./ -r

Ahora en VisualStudioCode Creamos dos archivoa index.html, script.js y luego hacemos algunas modificaciones

PS C:\Users\T470\Documents\CURSOS PROGRAMACION\Curso de JS\curso-practico-jasascript-desde-cero> git status

On branch main
Your branch is up to date with 'origin/main'.

(use "git add <file>..." to include in what will be committed)
index.html

nothing added to commit but untracked files present (use "git add" to track)

PS C:\Users\T470\Documents\CURSOS PROGRAMACION\Curso de JS\curso-practico-jasascript-desde-cero> git add –A

PS C:\Users\T470\Documents\CURSOS PROGRAMACION\Curso de JS\curso-practico-jasascript-desde-cero> git commit -m "Hello, world HTML and JS"

[main 0ea186e] Hello, world HTML and JS  
 2 files changed, 14 insertions(+)
create mode 100644 index.html
create mode 100644 script.js

PS C:\Users\T470\Documents\CURSOS PROGRAMACION\Curso de JS\curso-practico-jasascript-desde-cero> git push
Enumerating objects: 5, done.
Counting objects: 100% (5/5), done.
Delta compression using up to 4 threads  
Compressing objects: 100% (3/3), done.
Writing objects: 100% (4/4), 625 bytes | 208.00 KiB/s, done.
Total 4 (delta 0), reused 0 (delta 0), pack-reused 0
To https://github.com/WilliamOBC/curso-practico-jasascript-desde-cero
ea0997e..0ea186e main -> main
