# 📚 Introdução

Link para download do Git: https://git-scm.com/downloads

O Git Bash é um terminal extendido para otimizar o uso do Git.

## 📗 Para criar um repositóio Git

```
$ git init
```

## 📒 Para clonar um repositório existente

### Clonando a branch main

```
$ git clone [URL] [nome-do-diretorio-local]
```

### Clonando uma branch específica

```
$ git clone [URL] --branch [nome-da-branch] --single-branch
```

## 📘 Para exibir as condições do diretório de trabalho

```
$ git status
```

## 📕 Para preparar as alterações

```
$ git add .
```

## 📗 Para commitar as alterações

```
$ git commit -m"[nome-do-commit]"
```

### Alterando o nome do último commit

```
$ git commit --amend -m"[nome-do-commit]"
```

## 📒 Para listar o histórico

```
$ git log
```

## 📘 Para apagar um arquivo

```
$ git rm [nome-do-arquivo]
```

## 📕 Para restaurar um arquivo

```
$ git restore [nome-do-arquivo]
```

## 📗 Para resetar as alterações

### "Despreparando" as alterações

```
$ git reset --mixed [codigo-do-commit]
```

### Restaurando as alterações sem excluir os arquivos novos

```
$ git reset --hard [codigo-do-commit]
```

### Trocando de branch preservando as alterações feitas que não foram commitadas

```
$ git reset --soft [nome-da-branch]
```

## 📒 Trabalhando com branchs

### Para criar uma branch ou trocar de branch

```
$ git checkout -b [nome-da-branch]
```

### Para deletar uma branch

```
$ git branch -d [nome-da-branch]
```

### Para aplicar as alterações de uma branch em outra branch

```
$ git merge [nome-da-outra-branch]
```

## 📘 Trabalhando com repositórios locais e repositórios remotos

### Para adicionar um repositório remoto para seu repositório local

```
$ git remote add origin [URL]
```

### Para enviar as alterações para o repositório remoto

```
$ git push -u origin main
```

### Para "puxar" as alterações do repositório remoto sem alterar o repositório local

```
$ git fetch origin main
```

### Para "puxar" as alterações do repositório remoto tentando alterar o repositório local para corresponder com o conteúdo do repositório remoto

```
$ git pull origin main
```
