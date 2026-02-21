# git-docs

## setup-email-and-password
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

## use-a-credential-helper

this stores your credentials unencrypted on the disk so you dont have to log in everytime you push <br>
see **git-credential-store** and **gitcredentials** man pages
```
git config --global credential.helper store
```
