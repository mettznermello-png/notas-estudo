# notas-estudo
Minhas notas de estudos do tec SENAC 2026

## Configurando o GIT

Codes Needed to change the PC:

```bash
git config --global user.name
git config --global user.email
```
```bash
git –version
git config –global user.name “Joao Mello”
git config –global user.email “mettznermello@gmail.com”
```

## How to create a repositerie

```bash
Go to the site on Google Chrome "Github" open the charecter
Go through to "New" and then repositerie
Put on public always
Turn on README.md
wait to the paste apear
open the Git Bash
put the code "cd Doc *tab*" The initias of the paste *tab*
```

## How to create a key on Github

Follow the steps:

```bash
ls -al ~/.ssh
ssh-keygen -t ed25519 -C “mettznermello@gmail.com”
eval “$(ssh-agent -s)”
ssh-add ~/.ssh/id_ed25519
clip <~/.ssh/id_ed25519.pub
```

## codes to use on diary day sunny day

```bash
control + K + O: open the "open folder"
```