# Plano de qualidade do produto

## 1. Introdução
Antes de começar a estruturar o plano de qualidade, deve-se deixar claro o entendimento de como é definida qualidade em software. Qualidade em software é uma característica que possui pontos de vista diferentes como por exemplo:

- Qualidade de software é a capacidade de um software de atender aos requisitos de um cliente
- “Um produto de software apresenta qualidade dependendo do grau de satisfação das necessidades dos clientes sob todos os aspectos do produto” (Sanders, 1994).
- “Qualidade é a totalidade de características e critérios de um produto ou serviço que exercem suas habilidades para satisfazer as necessidades declaradas ou envolvidas” (ISO9126).

## 2. Objetivo do plano de qualidade
Este documento possui a finalidade de estabelecer padrões apropriados para o produto desenvolvido e aprimorado neste projeto, especificando técnicas e ferramentas para que o produto final atenda os requisitos de qualidade propostos no projeto.

Aqui iremos definir:
- Objetivos de qualidades.
- Como alcançar estes objetivos de qualidade.
- Métricas para aferição de qualidade, baseado nos objetivos.
- Procedimentos, técnicas e ferramentas utilizadas para realizar os itens acima.

## 3. Documentação
A documentação que será usada como referência para este documento serão os outros documentos disponíveis nesta documentação do projeto.

## 4. Objetivos de qualidade
Neste projeto iremos encontrar formas de medir e melhorar a qualidade de software do produto Alectrion, usando a norma ISO/IEC 250110:2011, tendo como foco: qualidade interna, qualidade externa e qualidade em uso.

- A qualidade interna é medida e avaliada com relação aos seus requisitos internos, que podem incluir modelos estáticos e dinâmicos, além de outros documentos e até mesmo o código-fonte.

- A qualidade externa é medida baseada na execução do software, que pode ser medido e avaliado enquanto em um ambiente de testes, com dados simulados e métricas externas.

- A qualidade em uso é a visão da qualidade do produto de software do ponto de vista do usuário, quando este produto é usado em um ambiente e um contexto de uso real, próprios do usuário. Sendo medida com base no quão bem os usuários conseguem realizar suas tarefas e suprir suas necessidades num determinado ambiente.

## 5. Verificação e validação
Para as técnicas de verificação e validação foram selecionadas três abordagens:
- Análise estática do código: com o uso da ferramenta SonarCloud, para a coleta de métricas a serem avaliadas;
- Testes automatizados: são os testes unitários e de integração a serem produzidos e executados;
- Testes manuais: testes de aceitação a serem realizados para validar que o software está cumprindo as especificações dos usuários.

## 6. Padrões, práticas, convenções e métricas
Os padrões de software são importantes para a qualidade do produto de software, pois representam a identificação das melhores práticas. As métricas de qualidade de produto são essenciais para identificar componentes que não seguem um padrão previamente estabelecido e que podem resultar em problemas de qualidade. Não existem métricas de softwares padronizadas e universalmente aplicáveis, ou seja, uma métrica não possui a mesma interpretação e utilidade para todos os projetos. Assim, deve-se selecionar métricas com base nos objetivos de qualidade.

#### 6.1 ISOS e normas
Principal ISO e modelo utilizados no projeto:
- ISO/IEC 25010

#### 6.2 Padrões de codificação
Um padrão de codificação descreve várias convenções usadas para fazer implementações consistentes e com qualidade. Para este projeto são usadas as ferramentas _eslint_ e _prettier_ para a padronização do código desenvolvido pelos integrantes da equipe.

#### 6.3 Métricas
As seguintes métricas serão coletadas com o uso do SonarCloud.

|            métrica              | descrição                                                    | medida em |
| ------------------------------- | :----------------------------------------------------------: | :--------:|
| Files                           | quantidade de arquivos de código                             | número |
| Functions                       | quantidade de funções no código                              | número |
| Complexity                      | complexidade ciclomática                                     | número |
| Commented lines density         | densidade de linhas comentadas                               | % |
| Duplicated lines density        | densidade de linhas duplicadas                               | % |
| Coverage                        | cobertura de código pelos testes                             | % |
| Ncloc                           | quantidade de linhas do código                               | número |
| Tests                           | quantidade de testes                                         | número |
| Test errors                     | quantidade de testes que falharam                            | número |
| Test failures                   | quantidade de testes que falharam com exceção inesperada     | número |
| Test execution time             | tempo que levou a execução de todos os testes                | número |
| Security rating                 | dado de segurança e vulnerabilidades                         | número |

#### 6.4 Métricas para o produto
A partir dos valores coletados com as métricas, tem-se um indicativo sobre a qualidade do produto. Por isso, é possível definir os valores mínimos aceitáveis para cada métrica.
Para definir os valores de métrica aceitáveis para a qualidade interna, a equipe selecionou como base as métricas definidas no SonarCloud.

|            métrica              | valor |
| ------------------------------- | :--------: |
| Complexity                      | até 10|
| Commented lines density         | até 30%|
| Duplicated lines density        | até 3%|
| Coverage                        | acima de 80%|
| Test errors                     | 0|
| Test failures                   | 0|
| Security rating                 | 0 (A)|

## 7. Testes
Existem algumas formas de testar o software:
- Testes unitários: utilizado para validar se uma unidade da aplicação está funcionando corretamente;
- Testes de integração: utilizado para verificar a integração correta entre os diferentes módulos da aplicação, uma vez que já tenham sido testados em unidade, para verificar se eles interagem corretamente;
- Testes caixa-branca: utilizado para testar o código e garantir que os componentes estejam concisos;
- Testes caixa-preta: utilizado para verificar todas as entradas e saídas desejadas, ignorando a estrutura interna do código, focando apenas nos requisitos funcionais do sistema.

## 8. Ferramentas, técnicas e metodologias
Para o projeto são utilizadas as seguintes ferramentas:
- [Jest](https://jestjs.io/): framework de testes para JavaScript
- [ESLint](https://eslint.org/): ferramenta de verificação automática de código
- [Prettier](https://prettier.io/): ferramenta de formatação de código
- [SonarCloud](https://www.sonarsource.com/products/sonarcloud/): ferramenta de varredura de código para analisar o código de acordo com as regras e métricas definidas

## 9. Controle de código
O controle de código é feito com o propósito de monitoramento das alterações no código. Para garantir o correto procedimento para qualidade estão sendo realizadas tarefas automatizadas no GitHub, com controle de versão, testes automatizados, controle de _commits_, entre outros.

## 10. Coleta e manutenção
É a fase após a coleta e análise das métricas, onde inicia-se um processo de manutenção no sistema. O objetivo é modificar o produto após liberação para melhorias, correções de falhas ou adaptações no produto. Existem algumas categorias de manutenção:
- Manutenção Adaptativa: adaptar o software;
- Manutenção Corretiva: identificar e corrigir errors e _bugs_;
- Manutenção Preventiva: melhorar a manutenibilidade ou confiabilidade do produto;
- Manutenção Perfectiva: realizar modificações solicitadas pelo usuário e efetuar melhorias gerais.


## 11. Referências
> [1] NBR - ISO/IEC 9126-1 - Engenharia de software - Qualidade de produto - Parte 1: Modelo de qualidade. Disponivel em: https://jkolb.com.br/wp-content/uploads/2014/02/NBR-ISO_IEC-9126-1.pdf. Acesso em: 06 de dezembro de 2022
> [2] Alectrion. Disponível em: https://fga-eps-mds.github.io/2022-1-Alectrion-DOC/home/. Acesso em: 09 de dezembro de 2022  
> [3] SonarCloud. Metric Definitions. Disponível em: https://docs.sonarcloud.io/digging-deeper/metric-definitions/. Acesso em: 10 de dezembro de 2022
> [4] ISO/IEC 25010:2011 - Systems and software engineering - Systems and software Quality Requirements and Evaluation (SQuaRE) — System and software quality models. Disponivel em: https://www.iso.org/standard/35733.html. Acesso em: 18 de dezembro de 2022



## 12. Histórico de versão

|**Data**|**Descrição**|**Autore(es)**|
|--------|-------------|--------------|
|06/12/2022| Criação e introdução do documento | Álvaro Leles |
|11/12/2022| Descrição dos processos e métodos de controle da qualidade | Aline Lermen |
|18/12/2022| Atualização do documento | Álvaro Leles |