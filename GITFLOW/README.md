# Operações com Branch 

## uma branch é uma ramificação do codigo que esta sendo desenvolvido, sendo assim uma parte não interfere na outra até que as duas sejam mescladas.

### As branches são extremamente úteis para colaboração em equipe, já que diferentes membros da equipe podem trabalhar em diferentes recursos ou correções de bugs em paralelo, sem conflitos diretos. Elas também são úteis para experimentação e desenvolvimento de novos recursos de forma isolada.

### Ao longo do ciclo de vida de um projeto Git, várias branches podem ser criadas, mescladas e excluídas conforme necessário para gerenciar e organizar o desenvolvimento do projeto.

Para criar uma branch usamos o codigo
    
`git branch (nome_da_branch)`

Quando criamos um repositorio no git ele vem com uma branch principal, chamada de 'master' ou 'main', podemos protar o nome da nossa branch quando quisermos ou quando tivermos problemas de incomatibilidade de nomes com o comando 

`git  branch -m master main` **Obs que estou mudando de master para main** 


`git branch -m main master` **Obs que agora estou mudando de main para master**

Depois de um algumas mudanças foi redefinido a nomeclatura de algumas branch e comando do git antes a branch principal se chamava **master** depois da mudança começou a se chamar **main** devido a algumas versões desatualizadas pode vir com o nome antigo, o comando abaixo defini como padrão o nome **main**

`git config --global init.defaultBranch main`

