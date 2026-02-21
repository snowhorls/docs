# git-docs

## setup-email-and-password
man **git config** line 6009 <br>

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

## set-vim-as-default-editor
```
git config --global core.editor vim
```

## use-a-credential-helper[^1]

this stores your credentials[^1] unencrypted on the disk so you dont have to log in everytime you push <br>
see **git-credential-store[^2]** and **gitcredentials** man pages
```
git config --global credential.helper store
```

[^1]: https://git-scm.com/doc/credential-helpers
[^2]: https://man.archlinux.org/man/git-credential-store.1 https://git-scm.com/docs/git-credential-store
