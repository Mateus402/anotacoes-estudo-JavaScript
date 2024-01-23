# Git

Uma maneira de organizar o versionamento do código.

Comandos básicos

### Altera a branch
```git
git checkout nomedabranch
```

### Para subir novas alterações para o GitHub

```git
git add .
git commit -m "comentário do commit" // Exemplo: "feat/forms" 
git push origin nomedabranch
```

### para puxar alterações do Github

```git
git pull nomedabranch
```

### merge de uma branch para outra branch

```git
// Deve estar na main
git merge main nomedabranch

git add .
git commit -m "feat/update"
git push origin main
``` 

### trocar de brach

```git
git checkout nome da branch
```