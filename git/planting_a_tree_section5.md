## Pruning Branches
<hr>

```
# Rebase the commits whose parent is branchA upto branchB onto <new parent>.
~$ git rebase --onto master branchA branchB

Before   (branchA)
o---o---o---o---o---o (master)
         \
          o---o---o (branchB)
               \
                o---o (HEAD -> branchC) 

After    (branchA)   (master)
o---o---o---o---o---o---o---o---o (HEAD -> branchB)
         \
          o---o---o---0 (branchC)
```
