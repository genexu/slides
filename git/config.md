## Config
<hr>
Setting up who you are
```bash
~$ git config --global user.name "Your Name"
~$ git config --global user.email mail@example.com
# Or remove --global for specific repo

```
Add remote
```bash
~$ git remote add origin https://github.com/<username>/<repo_name>.git
~$ git remote -v
# Add upstream for fork repo
~$ git remote add upstream <upstream_repo>
```
