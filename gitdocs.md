# git-docs

## set-vim-as-default-editor
```
git config --global core.editor vim
```

## use-a-credential-helper

this stores your credentials unencrypted on the disk so you dont have to log in everytime you push <br>
see **git-credential-store** man page
```
git config credential.helper store
```
