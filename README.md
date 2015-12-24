# IntelliJ symbolic link demonstration

Git supports symbolic links, and they are sometimes really, really, really cool to have a file turn up in two places in a repo, simultaneously. From Git's point of view, this simply works.

```
$ touch a.txt
$ ln -s a.txt b.txt
$ git add -A
```

Editing either `a.txt` or `b.txt` causes both to change.

## IntelliJ IDEA 15.0.2

Opening both the files `a.txt` and `b.txt` in IntelliJ at once causes a problem.

