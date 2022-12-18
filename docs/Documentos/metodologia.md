# Metodologias aplicadas ao projeto


## 1. Introdução

O projeto Alectrion utilizará métodos ágeis para desenvolver e entregar _software_ por meio de iterações em<br>
pequenos ciclos. Também é importante seguir os seguintes **princípios do ágil** [1]:

- Indivíduos e interações mais que processos e ferramentas;

- Software em funcionamento mais que documentação abrangente;

- Colaboração com o cliente mais que negociação de contratos;

- Responder a mudanças mais que seguir um plano;

## 2. Metodologias utilizadas

A Tabela 1 a seguir resume quais metodologias foram escolhidas e qual a finalidade de cada uma no contexto<br>
do projeto Alectrion.

<figcaption align='center'>
   Tabela 1: Metodologias utilizadas no projeto
   <br>
</figcaption>

|**Logo**|**Nome**|**Finalidade**|
|--------|:-------------:|--------------------|
|<img src="assets/logos/lean-inception.jpg" width="80px" height="60px">|Lean Inception [2]|Entendimento do problema, levantamento de requisitos em alto nível, elaboração do MVP|
|<img src="assets/logos/scrum.png" width="80px" height="60px">|Scrum [3]|Desenvolvimento do _software_|
|<img src="assets/logos/xp.jpg" width="80px" height="60px">|XP [4]|Adoção dos valores e das práticas que beneficiem a equipe e o produto, bem como descrição dos requisitos em histórias|
|<img src="assets/logos/kanban.png" width="80px" height="60px">|Kanban [5]|Uso do quadro e das listas de tarefas|

### 2.1 Lean Inception

As seguintes **atividades** dessa metodologia foram realizadas:

- [Visão do produto](../Leaninception/visao-do-produto.md);
- [O produto: é, não é; faz, não faz](../Leaninception/e-naoe-faz-naofaz.md);
- [Objetivos do negócio](../Leaninception/objetivos.md);
- [Personas](../Leaninception/personas.md);
- [Jornada do usuário](../Leaninception/jornadas.md);
- [_Brainstorming_ de funcionalidades](../Leaninception/brainstorm.md);
- [Revisão técnica, de negócio e de UX](../Leaninception/revisao-tecnica.md);
- [Sequenciador](../Leaninception/sequenciador.md);
- [MVP canvas](../Leaninception/mvp.md);

### 2.2 Scrum

**Características e atividades** adotadas:

- Trabalho em _sprints_: uma _sprint_ é um ciclo de desenvolvimento com data de início, de fim e tarefas bem definidas;

- Times pequenos, autogerenciáveis, com papéis bem definidos e focados em um objetivo;

- Reunião de planejamento: realizada ao se iniciar uma _sprint_ para determinar o que será feito e quem será o responsável por cada tarefa;

- _Daily Meetings_: Reuniões diárias de curta duração para acompanhar o andamento da _sprint_. No caso desse projeto,<br>
serão feitas reuniões de **_checkpoint_** no mesmo formato da _daily_, porém nem todos os dias da semana serão<br>
contemplados. Saiba mais no nosso [Plano de Comunicação](../Planejamento/comunicacao.md);

- Revisão e Retrospectiva da _sprint_: Reunião que ocorre no final de uma _sprint_ para pontuar o que deu certo,<br>
o que deu errado, e identificar dívidas técnicas, para fazer a melhoria contínua do processo de trabalho.<br>
Essa atividade também foi adaptada para o projeto. Saiba mais no nosso [Plano de Comunicação](../Planejamento/comunicacao.md);

**Artefatos** gerados:

- _Product backlog_: lista de histórias de usuário de todo o produto;

- _Sprint backlog_: lista de histórias de usuário da  sprint;

### 2.3 XP

Os seguintes **valores** XP são parte desse projeto:

- **Comunicação**: desenvolver software requer uma equipe disciplinada e colaborativa. A comunicação é chave para <br>
que o conhecimento e a informação sejam transferidos de um membro para cada outro na equipe. O XP reforça a importância <br>
da comunicação de forma apropriada, ou seja, dando preferência para conversas face-a-face com o suporte de algum mecanismo <br>
de desenho (ex.: quadro branco);

- **Simplicidade**: significa fazer a coisa mais simples e funcional. Isso evita fazer o que é desnecessário e traz o foco <br>
para aspectos mais importantes, como manter o projeto (_design_) do sistema o mais simples possível. Assim, manter, dar <br>
suporte e revisar o _software_ fica mais fácil;

- **Respeito**: é preciso haver respeito mútuo entre todos os membros do time para que possam se comunicar, além de fornecer <br>
e aceitar _feedback_ que honre o relacionamento. Além disso, com respeito o time trabalha junto para identificar boas soluções<br>
para problemas.

Mais ainda, as **principais práticas** adotadas para o contexto desse projeto são:

- **O time todo**: ter um grupo funcional de pessoas de diferentes áreas e com cargos necessários para desenvolver <br>
um produto. Esse é o time. Isso significa que pessoas com uma demanda, assim como aquelas que participam da realização <br>
dessa demanda de alguma forma, trabalham juntas, diariamente, para alcançar certo resultado;

- **Programação em pares**: consiste em 2 pessoas trabalhando com código juntas no mesmo equipamento. Pode ser executado <br>
de forma remota por meio de reunião virtual e compartilhamento de tela, por exemplo. A ideia é ter mais olhos e mentes <br>
focados em determinada tarefa, ao mesmo tempo em que ocorre uma revisão contínua do que está sendo feito, além <br>
de gerar uma resposta mais rápida a problemas que possam surgir. Times que utilizam essa prática relatam que ela <br>
promove um maior foco na realização da tarefa e não leva mais tempo do que o esperado, além de criar menos código para <br>
alcançar um objetivo. Para praticar isso, enquanto uma pessoa escreve o código, a outra atua com atenção como revisora. <br>
A dupla pode intercalar os papéis de programador de tempo em tempo, caso queiram, enquanto colaboram e se comunicam;

- **Histórias**: são descrições sobre o que o produto deveria fazer em termos significativos para os clientes e usuários. <br>
A recomendação é que as histórias sejam breves, curtas, servindo para o planejamento do que tem que ser feito e <br>
atuando como lembretes para conversas mais detalhadas quando o time se reunir para realizar aquela história em particular;

- **Ciclo semanal**: também chamado de iteração. O time se reúne no começo do ciclo para planejar as histórias que serão <br>
feitas, à escolha do cliente, e os responsáveis por elas. O time também decide como vão abordar cada história para que, <br>
ao final do período, tenham em funcionamento <br>
os recursos (as funcionalidades) já testadas. A intenção dessa entrega com data marcada por ciclo é ter algo para <br>
que o usuário veja e dê _feedback_;

- **Integração Contínua (CI)**: é a prática na qual mudanças no código são imediatamente testadas quando adicionadas <br>
a uma base de código maior. O benefício disso é conseguir encontrar e consertar problemas assim que eles aparecem. <br>
Para realizar essa prática, comumente utiliza-se pipelines, testes automatizados, políticas e outros recursos <br>
associados ao _DevOps_.

### 2.4 Kanban

Para o caso dessa metodologia, as seguintes listas serão utilizadas por meio do nosso Zenhub:

* Backlog do Produto: Tarefas planejadas que ainda serão feitas, mas não na sprint atual;

* Backlog da _Sprint_: Tarefas que devem ser feitas na _sprint_ atual;

* Em andamento (_in progress_): Tarefas que tiveram sua execução iniciada;

* Em revisão (Q/A): Tarefas completas e testadas que estão aguardando validação dos requisitos;

* Tarefas Resolvidas (_closed_): Tarefas que foram finalizadas;

## 3. Referências

> [1] AGILEMANIFESTO. Manifesto para Desenvolvimento Ágil de Software. Disponível em: https://agilemanifesto.org/iso/ptbr/manifesto.html

> [2] CAROLI, Paulo. Lean Inception: Como alinhar as pessoas e construir o produto certo. 1. ed. atual. São Paulo: Caroli, 2018. ISBN 978-85-94377-06-7. E-book.

> [3] SCRUM.ORG. What is Scrum?. Disponível em: https://www.scrum.org/resources/what-is-scrum

> [4] AGILE ALIANCE. Extreme Programming (XP). Disponível em: https://www.agilealliance.org/glossary/xp/

> [5] ATLASSIAN. What is Kanban ?. Disponível em: https://www.atlassian.com/agile/kanban#:~:text=What%20is%20kanban%3F,of%20work%20at%20any%20time

## 4. Histórico de versão

|**Data**|**Descrição**|**Autor(es)**|
|--------|-------------|--------------|
|15/12/2022| Criação do documento de metodologia | Erick Giffoni |
