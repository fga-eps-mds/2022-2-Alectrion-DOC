# Plano de gerenciamento de riscos


## 1. Introdução
Este documento visa explicitar como ocorrerá o gerenciamento de riscos, de modo a identificar e mapear os possíveis riscos presentes no projeto.

## 2. Categoria dos riscos

Os riscos podem ser categorizados como:

- **Técnico:** Os riscos técnicos abordam os requisitos, tecnologia, complexidade, confiabilidade e qualidade.

- **Externo:** Os riscos externos são relativos ao cliente, mercado ou ambiente.

- **Organizacional:** Os riscos organizacionais abordam as dependências do projeto, recursos e priorização.

- **Gerenciamento de projetos:** Os riscos de gerenciamento do projeto abordam a estimativa, planejamento, controle e a comunicação.


## 3. Análise quantitativa

### 3.1 Probabilidade

| Probabilidade | Intervalo | Peso |
| :-----------: | :-------: | :--: |
|  Muito baixa  | 0 a 15    |  1   |
|     Baixa     | 16 a 35   |  2   |
|     Média     | 36 a 50   |  3   |
|     Alta      | 51 a 65   |  4   |
|  Muito alta   | 66 a 100  |  5   |

### 3.2 Impacto

|   Impacto   |                  Descrição                  | Peso |
| :---------: | :-----------------------------------------: | :--: |
| Muito baixo |              Pouco Expressivo               |  1   |
|    Baixo    |                Pouco impacto                |  2   |
|    Médio    |                Impacto Médio                |  3   |
|    Alto     |               Grande impacto                |  4   |
| Muito alto  | Impacto impede o desenvolvimento do projeto |  5   |

### 3.3 Prioridade

A prioridade determina a urgência que medidas devem ser tomadas para resolver o risco, calculada com base no **impacto** e na **probabilidade**.

|       I/P       | **Muito baixa** | **Baixa** | **Média** | **Alta** | **Muito alta** |
| :-------------: | :-------------: | :-------: | :-------: | :------: | :------------: |
| **Muito baixo** |        1        |     2     |     3     |     4    |        5       |
|    **Baixo**    |        2        |     4     |     6     |     8    |       10       |
|    **Médio**    |        3        |     6     |     9     |    12    |       15       |
|    **Alto**     |        4        |     8     |    12     |    16    |       20       |
| **Muito alto**  |        5        |    10     |    15     |    20    |       25       |

### 3.4 Nível de prioridade

| Prioridade  | Intervalo |
| :---------: | :-------: |
| Muito baixa |   1 a 5   |
|    Baixa    |  6 a 10   |
|    Média    |  11 a 15  |
|    Alta     |  16 a 20  |
| Muito alta  |  21 a 25  |


## 4. Documentação dos riscos

### 4.1 Riscos técnicos

| ID | Risco | Consequência | Impacto | Probabilidade | Prioridade |
| -- | ----- | ------------ | ------- | ------------- | ---------- |
| RT01 | Limitação técnica | Demora no desenvolvimento do projeto | Alto | Média | Média |
| RT02 | Má gestão dos requisitos | Desenvolvimento falho do produto | Muito alto | Média | Média |
| RT03 | Baixa qualidade do software | Comprometimento da confiabilidade e integridade do software | Muito alto | Média | Média |
| RT04 | Mudança das tecnologias | Adequar todo o código as novas tecnologias | Muito alto | Muito baixa | Muito baixa |

### 4.2 Riscos organizacionais

| ID | Risco | Consequência | Impacto | Probabilidade | Prioridade |
| -- | ----- | ------------ | ------- | ------------- | ---------- |
| RO01 | Má priorização das tarefas  | Confusão e consequente ineficiência na divisão de trabalho | Alto | Alta | Alta |
| RO02 | Mudança de escopo | Necessidade de replanejamento e repriorização do projeto | Muito Alto | Baixa | Baixa |

### 4.3 Riscos de gerenciamento de projeto 

| ID | Risco | Consequência | Impacto | Probabilidade | Prioridade |
| -- | ----- | ------------ | ------- | ------------- | ---------- |
| RGP01 | Comunicação ineficiente entre os membros da equipe | Falta de alinhamento entre o time de desenvolvimento | Alto | Alta | Alta |
| RGP02 | Desistência de membros | Sobrecarga de trabalho para o restante da equipe | Alto | Média | Média |
| RGP03 | Falta de compatibilidade entre horários dos membros | Dificuldade para a realização de eventos síncronos entre a equipe | Alto | Alta | Alta |
| RGP04 | Baixa produtividade da equipe | Atraso nas entregas | Alto | Média | Média |
| RGP05 | Pareamento não efetivo | Atraso nas entregas | Alto | Média | Média |


### 4.4 Risco externo

| ID | Risco | Consequência | Impacto | Probabilidade | Prioridade |
| -- | ----- | ------------ | ------- | ------------- | ---------- |
| RE01 | Adoecimento de membro da equipe | Atraso nas entregas e/ou sobrecarga de trabalho aos demais membros | Alto | Média | Média | 


## 5. Referências Bibliográficas

<!-- Referências enumeradas-->

> [1] Guia PMBOK 6a. ed. EUA: Project Management Institure, 2017. Disponível em: https://www.site.com

> [2] EQUIPE ALECTRION 2022-1. Planejamento de Gerenciamento de Riscos. Disponível em: https://github.com/fga-eps-mds/2022-1-Alectrion-DOC/blob/main/docs/documentation/Documentos/plano-de-riscos.md


## 6. Histórico de versão

|**Data**|**Descrição**|**Autor(es)**|
|--------|-------------|--------------|
| 05/12/2022 | Criação do documento | João Vitor |
| 07/12/2022 | Documentação dos riscos | João Vitor |
| 08/12/2022 | Correção de erros de escrita | João Vitor |