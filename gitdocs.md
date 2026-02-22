# git-docs

## setup-email-and-password[^4]

globally

```
git config --global user.name "username"
git config --global user.email "email"
```
or localy

```
git config --global user.name "username"
git config --global user.email "email"
```

## set-vim-as-default-editor[^4]
```
git config --global core.editor vim
```

## remote-repos
git uses remote repos to push and pull contributions from the internet
```
git remote -v
```
shows your remote servers you have configured

### adding-remote-repos[^5]

```
git remote add <shortname> <url>
```
or
```
git remote add origin https://github.com/username/repo
```

## use-a-credential-helper[^1]

this stores your credentials unencrypted on the disk so you dont have to log in everytime you push <br>
```
git config --global credential.helper store
``` 
see **git-credential-store**[^2] and **gitcredentials**[^3] <br>

references

[^1]: https://git-scm.com/doc/credential-helpers
[^2]: https://git-scm.com/docs/git-credential-store
[^3]: https://git-scm.com/docs/gitcredentials
[^4]: https://git-scm.com/docs/gittutorial
[^5]: [basics-working-with-remotes](https://git-scm.com/book/ms/v2/Git-Basics-Working-with-Remotes), [git-remote-manpage](https://git-scm.com/docs/git-remote)
[^6]: https://www.quora.com/What-is-the-purpose-of-the-origin-remote-in-Git 
