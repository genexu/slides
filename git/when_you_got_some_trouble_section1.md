# Bisecting
<hr>

Find which commit introduced a bug using a binary search

```bash
~$ git bisect start <bad_ref> <good_ref>
Bisecting: <N> revisions left to test after this (roughly <N> step)

[<sha_hash>] Commit Message
~$ git bisect good
# OR
~$ git bisect bad
...

<sha_hash> is the first bad commit!!!
<show commit info>

~$ git bisect reset
```
