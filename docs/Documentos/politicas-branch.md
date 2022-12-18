# Política de _branches_

## 1. Introdução

A política de _branches_ é essencial para que todos os contribuintes do projeto entendam como utilizar
corretamente as _branches_ de acordo com o padrão estabelecido.


Utilizaremos 2 modelos como política de _branches_ conforme o repositório em questão.

## 2. Para o repositório de documentação

O modelo de _branch_ a ser utilizado no repositório [2022-2-Alectrion-DOC](https://github.com/fga-eps-mds/2022-2-Alectrion-DOC) será simples:

- A _branch_ **main** é usada para fazer o _deploy_ para nosso _pages_;

- Outras _branches_ serão criadas a partir da **main** com o objetivo de atualizar, criar ou
corrigir algum problema nos documentos;

   - O nome dessas _branches_ deve seguir o padrão ```doc/<assunto ou artefato>```.<br>
   > Por exemplo: para adicionar o documento de visão, o nome da branch seria <br>
   ```doc/visao```, e o comando _git_ seria <br>
   ```git checkout -b doc/visao```

## 3. Para os repositórios de desenvolvimento

Os seguintes repositórios serão contemplados por esse modelo de _branches_, conforme a Imagem 1
abaixo:

- [2022-2-Alectrion-UserAPI](https://github.com/fga-eps-mds/2022-2-Alectrion-UserAPI)
- [2022-2-Alectrion-EquipamentApi](https://github.com/fga-eps-mds/2022-2-Alectrion-EquipamentApi)
- [2022-2-Alectrion-Gateway](https://github.com/fga-eps-mds/2022-2-Alectrion-Gateway)
- [2022-2-Alectrion-FrontEnd](https://github.com/fga-eps-mds/2022-2-Alectrion-FrontEnd)

<figcaption align='center'>
   Imagem 1: Modelo de <i>branches</i> para os repositórios de desenvolvimento 
</figcaption>

[<div align="center"><img width="80%" height="auto" src="assets/diagrama-de-branches.png"/></div>]()

#### *Main*

Utilizaremos a _branch_ ```main``` para produção. Ela representa uma versão estável da aplicação,
pronta para os usuários utilizarem com confiança.

#### *Bug*

_Branches_ para correções urgentes de _bugs_ são criadas a partir da _branch_ **main** e são juntadas diretamente nela (por meio de um _pull request_).<br>
Por convenção, o nome dessas _branches_  segue o formato ```hotfix/<problema a ser resolvido>```.<br>
Por exemplo: ```hotfix/imagens-nao-salvas-no-banco```

#### *Develop*

A _branch_ ```dev``` é para homologação, nela se encontra a versão ainda em testes da aplicação.
Quando a utilização dessa versão se demonstrar<br>
estável e com eventuais _bugs_ corrigidos, essa
_branch_ será juntada na ```main``` por meio de um _pull request_.

#### *Feature*

Representam as _branches_ criadas para contemplar as **histórias de usuário**. Elas serão criadas a partir
da ```dev``` e serão juntadas também na ```dev```<br>
por meio de um _pull request_. O **nome** dessas _branches_
seguirá o padrão ```us/<numero da us>-<assunto>```.<br>
Por exemplo:

> ```us/01-cadastro-usuario``` <br>
A partir da **dev**, faça: ```git checkout -b us/01-cadastro-usuario```

#### *Outras branches*

Outras branches devem ser criadas a partir do padrão: tipo/artefato.

## 4. Pull Requests

### *Labels*

Neste projeto utilizaremos algumas labels para associar às _Issues_ e às _Pull Requests_ para auxiliar no entendimento do objetivo das mesmas. As labels que serão usadas serão listadas a seguir mas também podem ser acessadas [aqui](https://github.com/fga-eps-mds/2022-2-Alectrion-DOC/labels).

 - **ANALYTICS:** Label para associar a questões de métricas e análises;
 - **ARQ:**
 - **bug:** Label para associar a algo que não está funcionando da forma esperada;
 - **DEVOPS:** Label para associar a _issues_ que envolvem os operadores do sistema;
 - **DOCS:** Label para associar a questões de documentação do produto;
 - **duplicate:** Label para marcar _issues_ duplicadas;
 - **EASY:** Label para associar a _issues_ de fácil resolução;
 - **enhancement:** Label para associar a _issues_ de novas _features_;
 - **Epic:** Label para associar a épicos;
 - **EPS:** Label para associar a _issues_ que devem ser realizadas ou monitoradas por alunos da disciplina de EPS;
 - **FEATURE:** Label para associar a _features_;
 - **good first issue:** Label para associar a _issues_ que podem ser resolvidas por recém chegados no repositório;
 - **HARD:** Label para associar a _issues_ que possuem maior complexidade de resolução;
 - **help wanted:** Label para associar a _issues_ onde se precisa de ajuda para continuar sua resolução;
 - **HOTFIX:** Label para associar a _issues_ que precisam resolver uma situação muito específica;
 - **invalid:** Label para associar a _issues_ onde algo não parece estar funcionando corretamente;
 - **MDS:** Label para associar a _issues_ que devem/podem ser realizadas por alunos da disciplina de MDS;
 - **MEDIUM:** Label para associar a _issues_ que possuem certa complexidade;
 - **question:** Label para associar a _issues_ onde maiores informações são necessárias para continuar sua resolução;
 - **US:** Label para associar a histórias de usuário;
 - **wontfix:** Label para associar a _issues_ que não possuem intenção de serem solucionadas a princípio;


### Abertura e conteúdo de *Pull Requests*

Após ter resolvido uma issue e estar satisfeito com o que foi alterado nos arquivos locais, deve-se enviar essas alterações para o repositório no GitHub por meio de commits. Após isso, pode-se ir para o repositório e abrir um _pull request_, onde deve-se escolher a _branch_ que se quer propor as alterações e informar o máximo de detalhes da contribuição, seguindo o [template de _pull requests_](https://github.com/fga-eps-mds/2022-2-Alectrion-DOC/blob/main/.github/pull_request_template.md), criando então um _pull request_ para ser revisado.

### Revisores

Ao abrir o _pull request_ deve-se marcar ao menos dois integrantes de EPS e dois de MDS para revisarem o conteúdo do PR. Caso seja necessário, o autor do PR será solicitado pelos revisores para fazer edições ou melhorias.

Sempre que implementar alterações sugeridas, deve-se avisar aos revisores para que eles dêem uma nova olhada. Ao fim, se a contribuição for aceita, o _pull request_ será _mergeado_ à branch de destino do repositório.

## 5. Referências

> [1] EQUIPE ALECTRION 2022-1. Política de Branches. Disponível em: https://fga-eps-mds.github.io/2022-1-Alectrion-DOC/documentation/Documentos/politicas-branch.html

> [2] ATLASSIAN. Gitflow Workflow. Disponível em: https://www.atlassian.com/git/tutorials/comparing-workflows/gitflow-workflow

## 6. Histórico de versão

|**Data**|**Descrição**|**Autore(es)**|
|--------|-------------|--------------|
|09/12/2022| Criação da política de _branches_ | Erick Giffoni |
|16/12/2022| Adição da política de _pull requests_ | Álvaro Leles |
