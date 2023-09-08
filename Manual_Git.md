# Vincular e subir modificação para GitHub

### Iniciar repositório git

Já dentro da pasta em que se deseja alocar os arquivos:
```
git init 
```
Caso não enteja na pasta se faz necessário entrar na mesma, mesmo que pelo próprio terminal.

### Informar o link do Repositório em que se deseja subir o pacote
```
git remote add origin [url-do-repo]
```
### Verificar em qual link (Repositório) está vinculado
```
git remote -v
```

### Caso existam arquivos que não estão na pasta local:
```
git pull 
```
### Listar e verificar em qual branch está
Para listar as brabch's existentes e ver em qual está pode ser utilizado.
```
git branch
```
Ira listar todas as banchs e irá aparecer em verde a branch em que se etá.

### Criar nova branch e mover para ela
```
git checkout -b [nome-da-branch]
```
### Mover para outra branch
```
git checkout [nome-da-branch-a-entrar]
```
### Mesclar (mover) branchs
Para mesclar duas branchs é necessário estar dentro da branch que deseja manter e fazer o merge da branch que quere trazer pra dentro.
```
git merge [nome-repo-que-quer-mesclar]
```
Exemplo:     
Estou dentro da branch *main* e quero colocar a branch *nova* dentro da branch *main*

```
git merge nova
```
A branch *nova* ira para dentro da branch *main*

### verificar os Status do procedimento
```
git status
```


