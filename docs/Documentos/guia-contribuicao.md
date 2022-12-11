# Guia de Contribuição

## 1. Introdução

**Como contribuir para o projeto Alectrion ?**

Siga as diretrizes abaixo.

## 2. Diretrizes para contribuir

### 2.1 Código de Conduta

Siga o seguinte [código de conduta](https://www.contributor-covenant.org/version/2/1/code_of_conduct/) [3] para contribuir em qualquer repositório desse projeto.

### 2.2 Politica de Issues

A criação de novas _issues_ deverá seguir um dos padrões estabelecidos abaixo:

- [_Bug report_](https://github.com/fga-eps-mds/2022-2-Alectrion-DOC/blob/main/.github/ISSUE_TEMPLATE/bug_report.md): para relatar problemas, erros, defeitos ou falhas;

- [História de usuário](https://github.com/fga-eps-mds/2022-2-Alectrion-DOC/blob/main/.github/ISSUE_TEMPLATE/hist-ria-de-usu-rio--us-s-.md): quando for descrever funcionalidades a nível de história de usuário;

- [Geral](https://github.com/fga-eps-mds/2022-2-Alectrion-DOC/blob/main/.github/ISSUE_TEMPLATE/geral.md): utilizado para criar ou relatar tarefas ou outras atividades gerais.

### 2.3 Política de Commit

Os _commits_ deverão seguir o padrão de mensagens especificado pelo [Conventional Commits](https://www.conventionalcommits.org/en/v1.0.0/) [2]. As seguintes regras também se aplicam:

- A descrição de um _commit_ deve ser escrita em Português;

- Um _commit_ deve referenciar a _issue_ trabalhada;

- Um _commit_ deve representar uma unidade de trabalho. Por exemplo: não adicionar arquivos relacionados a _issues_ diferentes no mesmo _commit_;

Exemplo: Issue 1: Realizar autenticação do usuário (serviço)
```
git commit -m "#1 feat: adicionado serviço de autenticação"
```

### 2.4 Pareamento

Para tarefas realizadas em pares, os _commits_ precisam seguir o seguinte padrão:

```
Descrição do commit

Signed-off-by: Nome do responsável <nome@gmail.com>
Co-authored-by: Nome de quem auxiliou <auxiliador@gmail.com>
```

Obs.: o email PRECISA ser o mesmo que está vinculado à conta do Github.

- **'Signed-off-by: '** deve ser preenchido pelo responsável pelo código;

- **'Co-authored-by:'** deve ser preenchido por quem prestou auxílio durante a tarefa.

## 3. Referências

> [1] EQUIPE ALECTRION 2022-1. Como contribuir. Disponível em: https://fga-eps-mds.github.io/2022-1-Alectrion-DOC/documentation/Documentos/guia-contribuicao.html

> [2] CONVENTIONAL COMMITS. Conventional Commits. Disponível em: https://www.conventionalcommits.org/en/v1.0.0/

> [3] CONTRIBUTOR COVENANT. CONTRIBUTOR COVENANT CODE OF CONDUCT. Disponível em: https://www.contributor-covenant.org/version/2/1/code_of_conduct/

## 4. Histórico de versão

|**Data**|**Descrição**|**Autore(es)**|
|--------|-------------|--------------|
|08/12/2022| Criação do Guia de Contribuição | Erick Giffoni |
