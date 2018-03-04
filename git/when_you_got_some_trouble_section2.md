## Reflog
<hr>
Reflog records almost every change you make in your repository.
```bash
~$ git reflog
<sha_hash> Ref@{N}: commit: message
<sha_hash> Ref@{N}: commit: message
<sha_hash> Ref@{N}: commit: message
...

~$ git reset <sha_hash>
# OR
~$ git reset Ref@{N}
```

[Refs And The Reflog](https://www.atlassian.com/git/tutorials/refs-and-the-reflog)  
[Git Reflog](https://www.atlassian.com/git/tutorials/rewriting-history/git-reflog)

