<div align="center">

<img alt="Cabeçalho UFMS" src="/.assets/cabecalho_docs.png" />

## Diretrizes para escrita de estórias

</div>

### 1. Introdução

Uma estória é uma descrição de uma necessidade de usuários reais de um sistema de software a ser desenvolvido ou mantido. Essa descrição deve ter detalhes suficientes para permitir que a equipe de desenvolvimento possa fazer uma estimativa do trabalho a ser feito.

Este documento tem o propósito de informar as diretrizes a serem usadas para a escrita de estórias na Disciplina de Construção de Software 2 da Facom. A Seção 2 registra as diretrizes citadas e a Seção 3 apresenta alguns exemplos de estórias bem escritas.

### 2. Diretrizes

As diretrizes para escrita de estórias na Disciplina de Construção de Software 2 da Facom são descritas nesta seção.

#### Diretriz 1 - Sobre a estrutura

Todas as estórias devem usar a seguinte estrutura:

Como `<papel de usuário>` eu quero `<descrição da necessidade do usuário>` a fim de `<descrição do objetivo do usuário>`. Condições de satisfação: Breve descrição dos testes de aceitação a serem realizados para demonstrar que a estória foi completamente implementada. Estas condições são específicas por estória.

No item `<papel de usuário>` deve ser indicado a qual tipo de usuário a necessidade está relacionada. No Siscad, por exemplo, papéis de usuário típicos são alunos e professores.

#### Diretriz 2 - Sobre a identificação

Toda estória deve ter um identificador único, formado pelo nome do projeto a que pertence e um número sequencial imediatamente superior ao da última estória escrita para o projeto em questão.

#### Diretriz 3 - Sobre o grau de detalhamento

Se uma estória é grande demais para ser implementada em um Sprint, ela deve ser marcada como um epic e deve ser quebrada em estórias menores antes do planejamento de um Sprint em que há a possibilidade de que ela seja implementada.

#### Diretriz 4 - Sobre prioridades e estimativas

Toda estória deve ter registrada sua prioridade e sua estimativa sempre que ela for incluída no Backlog de um Sprint.

#### Diretriz 5 - Definição de estória implementada

Uma estória é considerada completamente implementada e, portanto, pode ser queimada no Burndown Chart se e somente se:

- A funcionalidade da estória está complementada codificada e os seus critérios de satisfação foram cumpridos;
- Foram feitos e documentados testes de unidade e de integração em relação ao seu código;
- O documento de rastreabilidade de requisitos foi atualizado com o código criado.

### 3. Exemplos

Alguns exemplos de estórias bem escritas são dados na Tabela 1.

| Estória                                                                                                                | Critérios de satisfação                                                                                                                                                                                                                                                                                                                                                                                                                                                                        |
| ---------------------------------------------------------------------------------------------------------------------- | ---------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------- |
| Como um estudante eu quero acessar meu percentual de presenças online a fim de saber se já reprovei em uma disciplina. | - O usuário consegue selecionar qualquer disciplina em que está matriculado ou que já tenha cursado; - Suas presenças e faltas a cada dia de aula dado naquela disciplina escolhida são apresentadas; - O usuário não consegue editar suas presenças e faltas.                                                                                                                                                                                                                                 |
| Como um professor eu quero poder lançar as presenças e faltas de meus alunos em um dia letivo de uma turma.            | - O usuário consegue selecionar um dia letivo de uma turma em que é professor; - O usuário consegue visualizar a lista de todos alunos matriculados naquela turma e informar se cada um deles estava presente ou ausente; - Há uma opção “lançar presença para todos” e uma opção “lançar ausência para todos”, que vale apenas para a aula selecionada; - Se uma das opções do item anterior for acionada, o usuário ainda consegue alterar pontualmente as presenças e faltas de cada aluno. |

_Tabela 1 - Exemplos de estórias bem escritas._

### 4. Referências

https://www.mountaingoatsoftware.com/blog/clarifying-the-relationship-between-definition-of-done-and-conditions-of-sa
