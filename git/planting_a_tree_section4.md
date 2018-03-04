## Pruning Branches
<hr>

```
# Rebase the HEAD from <old parent> onto <new parent>
~$ git rebase --onto branchA branchB

Before
o---o---o---o (branchA)
         \
          o---o---o (branchB)
               \
                o---o (HEAD -> branchC) 

After        (branchA)
o---o---o---o---o---o---o (HEAD -> branchC)
         \
          o---o---o (branchB)
```
