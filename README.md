# Modelo de desenvolvimento com git

Olá pessoal, esse é um modelo de git flow utilizado em alguns projetos, espero que ajude quem esta iniciando no git. 

### branch main - produção
### branch developer - desenvolvimento
### branch feat/... - features do desenvolvedor



### Inicio de uma nova branch
git branch feat/tela-lista-empresas

### Entrando na nova branch
git checkout feat/tela-lista-empresas

Desenvolvimento da feature......

### Adicionando arquivos a branch
git add .

### Commitando os arquivos
git commit -m "tela de lista de empresas"

### Publicando os arquivos na branch
git push -u origin feat/tela-lista-empresas


### Retornando para a branch principal
git checkout developer

### Baixando as atualizações
git pull

### Retornando a branch para possiveis ajustes
git checkout feat/tela-lista-empresas

### Mesclando a branch com a branch principal
git merge developer

 Seguir o passos anteriores de commit e push.......

### Iniciando uma nova branch
git branch feat/tela-cadastro-empresa

