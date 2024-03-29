# Este é um repositorio para documentar tudo que eu aprendi e quero apresentar sobre o tema GIT

## Como iniciar um repositorio no github via terminal?
 Existe basicamente duas formas de criar e utilizar o repositorio com o git no github, conforme a imagem;

[!Imagem0](/imagens/Duas%20formas%20para%20utilizar%20o%20git.png)

Via terminal direto;

>[!NOTE]
>
>Usando o Linux mint 21.3 e o vs code 1.86.2.

>[!IMPORTANT]
>
> Você precisa baixar o Git, ter uma conta no GitHub e configurar o vscode para usar o git com
> ele

Baixe o  
[Git](https://git-scm.com/) aqui esta uma 
[Documentação](https://learn.microsoft.com/pt-br/training/modules/introduction-to-github-visual-studio-code/) para usar integrar o git ao vscode


Abrir o terminal >> buscar um local que deseja guardar uma pasta >> criar uma pasta >> abrir essa pasta no vs code
>[!TIP]
>
>Use o terminal pois a aprendizagem e mais eficiente!

Usando o comando mkdir criarei uma pasta chamada exemplo1.
![Imagem1](/imagens/exemplo1_mkdir.png "imagem mostra passo1") 

Depois entrei na pasta com o comando cd, em seguida utilizei o comando ls para verificar se tinha alguma coisa na pasta e em seguida criei um arquivo chamado readme.md com o comando touch.
![Imagem2](/imagens/exemplo1_touch_md.png)

O proximo passo pode ser feito usando o auxilio do VS code, pois existe a integração com o Github e podemos escolher lá a disponibilidade do repositorio.
>[!NOTE]
>
>Podemos realizar o processo pelo site do github, vou demonstrar em seguida.

Na pasta do projeto, ls para verificar o que tem na pasta, em seguida executando (code . ) a pasta e tudo que esta na pasta é aberto no vs code.
![Imagem3](/imagens/exemplo1_abrindo_code.png)

Para ter o que mostrar no repositorio do GitHub vou escrever:
Isto é um teste de exemplo, os ## são usados para formatar o texto nos arquivos .md e eles são usados para titulos.
![Imagem4](/imagens/exemplo1_digitando_md_txt.png)

Usando o atalho Ctrl + s podemos salvar, ou o caminho; Arquivo >> salvar.
![Imagem5](/imagens/exemplo1_salvando_md.png)

Usando o menu lateral esquerdo no vs code podemos veriicar a opção (Controle de codigo fonte) aqui podemos enviar nosso codigo para o github

>[!IMPORTANT]
> É Necessario realizar a configuração da conta do GitHub no seu VScode, estou deixando um link 
> com a [documentação](https://learn.microsoft.com/pt-br/training/modules/introduction-to-github-visual-studio-code/) para realizar isso, porém caso não cosiga a proxima parte mostra um exemplo
> com um repositorio criado via site do github.

Agora precisamos acessar a conta do GitHub e criar um repositorio.

![Imagem6](/imagens/exemplo1_criando_repositorio_nogit.png)

Logo em seguida informar nome para o repositorio, pode ser igual o nome da pasta que esta na nossa maquina, ou não pode ser um outro nome qualquer.

![Imagem7](/imagens/exemplo1_criando_repositorio_nomecriar.png)

O GitHub mostra as formas de realizar o commit com a pasta no pc e o repositorio de forma remota conforme imagem abaixo.

![Imagem8](/imagens/exemplo1_dados_https_para_add.png)

Para realizar isso, executaremos cada um dos codigos da imagem acima no terminal do VS code conforme imagem abaixo;

![Imagem9](/imagens/exemplo1_executando%20enderecorepositorio.png)

>[!NOTE]
>
> Eu errei os passos para realizar o processo, deu um erro no momento de executrar  
> git push -u origin main
> pois eu deveria ter executado git commit -m "qualquer texto que queira aqui" antes

Conforme podemos ver na imagem abaixo.

![Imagem10](/imagens/exemplo1_finalizando_commit.png)

>[!IMPORTANT]
>
>
> No seu pode ocorrer um erro, pois o git precisa do login e senha, o login é o seu nome de user
> a senha pode ser obtida aqui no 
> [link](https://docs.github.com/pt/authentication/keeping-your-account-and-data-secure/managing-your-personal-access-tokens)