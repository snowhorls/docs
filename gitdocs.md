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

## use-a-credential-helper[^1]

this stores your credentials unencrypted on the disk so you dont have to log in everytime you push <br>
see **git-credential-store**[^2] and **gitcredentials**[^3]
```
git config --global credential.helper store
```
## references
[^1]: https://git-scm.com/doc/credential-helpers
[^2]: https://git-scm.com/docs/git-credential-store
[^3]: https://git-scm.com/docs/gitcredentials
[^4]: https://git-scm.com/docs/gittutorial
