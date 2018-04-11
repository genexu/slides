## Pruning Branches
<hr>

```
# Rebase the commits whose parent is branchA upto branchB onto <new parent>.
~$ git rebase --onto master A2 B2

Before
M1---M2---M3---M4 (master)
       \
        A1---A2---A3 (branchB)
                \
                 B1---B2 (HEAD -> branchC) 

After       (master)
M1---M2---M3---A2---B1---B2 (HEAD)
       \
        A1---A2---A3 (branchA)
              \
               B1---B2(branchB)
```
