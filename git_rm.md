## git rm
Команда ***git rm*** используется в Git для удаления файлов из индекса и рабочей директории. Она похожа на git add с тем лишь исключением, что она удаляет, а не добавляет файлы для следующего коммита.

```bash=
git rm [-f | --force] [-n] [-r] [--cached] [--ignore-unmatch]
	  [--quiet] [--pathspec-from-file=<file> [--pathspec-file-nul]]
	  [--] [<pathspec>…​].
```