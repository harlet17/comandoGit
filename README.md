[![Author](https://img.shields.io/badge/Dev-Nadi%20Duno-blueviolet%20)](https://github.com/nadiduno)
[![Author](https://img.shields.io/badge/Dev-Harlet%20Orellan-blueviolet%20)](https://github.com/harlet17)

# Comandos em Git

```bash
$ git init 
# Criando uma branch no repositório local (pc) 
$ git checkout -b feature-readme
# Modifica o README no local e comita
$ git add README.md
$ git commit -m 'Update README'
$ git status
$ git push
# Aqui da um erro e recomenda fazer um push da nova branch
$ git push --set-upstream origin feature-readme
$ git push
$ git checkout main
$ git merge feature-readme
$ git push
# Aqui da o conflito, já que previamente tinhamos modificado o README no repositório remoto
$ git pull
$ git config pull.rebase false
$ git pull
# Aqui temos que tomar a decisão de que código conversar, e fazer o merge a mão
$ git add README.md
$ git commit -m 'Solve conflict README'
$ git status
$ git push
```

