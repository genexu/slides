## Pruning Branches
<hr>

```
# Rebase the HEAD from <old parent> onto <new parent>
~$ git rebase --onto branchA branchB

Before       (branchA)
o---o---o---o
         \ (branchB)
          o---o---o
               \
                o---o (HEAD -> branchC) 

After        (branchA)
o---o---o---o---o---o---o (HEAD -> branchC)
         \ (branchB)
          o---o---o
```
