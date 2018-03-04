## Git Diff
Basic diff
```bash
~$ git diff <branch> <branch> 
~$ git diff <sha_hash> <sha_hash> 
# origin..newone
```
Diff specific file
```bash
~$ git diff [sha_hash||branch] [sha_hash||branch] <filename>
```

```bash
index <sha_hash>...<sha_hash>
<filename> +++--- 
---Hello World
+++Hello My Friend!
```

