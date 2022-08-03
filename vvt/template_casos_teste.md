> **Responsável:** Testador(a)
>
> Esse documento serve como entrada para:
>
> 1. Projetar e implementar scripts de teste;
> 2. Revisar os casos de teste;
> 3. Criar os casos de teste.
>
> **Descrição principal:** Um caso de teste especifica as condições que necessitam ser validadas para permitir a avaliação de alguns aspectos particulares do sistema sob teste. Um caso de teste é mais formal do que uma idéia de teste e normalmente tem a forma de uma especificação. Em ambientes menos formais, casos de teste podem ser criados pela identificação de um ID único, um nome, dados de teste associados e resultados esperados.
>
> Os casos de teste podem ser derivados de várias fontes, mas normalmente incluirão um subconjunto de requisitos (tais como casos de uso, características de desempenho, necessidades de confiabilidade) e outros tipos de atributos de qualidade. Para mais informações sobre tipos de teste e seus relacionamentos com os atributos de qualidade do teste.
>
> **Boas Práticas:**
>
> - Os casos de teste devem descrever um comportamento e não um passo a passo;
> - Precisam seguir uma linguagem ubíqua, ou seja, qualquer pessoa que ler entenderá o objetivo;
> - Todos os cenários devem ser independentes, porém seguiram uma sequencia lógica de execução;
> - Os casos de teste devem serem escritos na primeira ou terceira pessoa.
> - As ações e os resultados devem sempre iniciar com um verbo infinitivo — preencher, validar, clicar, acionar — ou imperativo — preencha, valide, verifique.

<div align="center">

<img alt="Cabeçalho UFMS" src="/.assets/cabecalho_docs.png" />

##### Faculdade de Computação <br /> Núcleo de Práticas em Engenharia de Software

</div>

<div align="right">

### Caso de Teste <br /> `<nome do projeto>` <br /> Versão `<versão>`

</div>

<div align="center">

#### Histórico de Alterações do Documento

| Data | Versão | Descrição | Autor |
| ---- | ------ | --------- | ----- |
|      |        |           |       |

</div>

### 1. Introdução

Este documento especifica os testes que devem ser realizados para os seguintes caso de uso (ou estórias de usuário) `<nome do caso de uso/nome da estória de usuário>`. Ele contém todas as informações necessárias para a construção dos scripts de teste, como preparação do ambiente, dados de entrada e resultados esperados.

#### 1.1 Visão geral do documento

Além desta seção introdutória, as seções seguintes estão organizadas como descrito abaixo.

##### Seção 2 – Testes Funcionais

Esta seção especifica os testes funcionais para o fluxo principal e para os outros cenários do caso de uso.

##### Seção 3 – Testes Não Funcionais

Esta seção especifica os testes não funcionais do caso de uso.

### 2. Testes Funcionais

#### 2.1 `<Identificador do CT>`: `<Nome do Teste Funcional>`

| Dado         | Valor         |
| ------------ | ------------- |
| Automatizado | `<Sim / Não>` |
| Responsável  |               |
| Data         |               |

##### Procedimentos

> [descreva os procedimentos do teste. São passos ordenados logicamente, caso um outro caso de teste precise ser executado antes, você pode mencionar diretamente “Executar o CT-XX”]

##### Resultado Esperado

> [indique o resultado esperado do teste)]

### 3. Testes Não Funcionais

#### 3.1. `<Identificador do CT>`: `<Nome do Teste Não Funcional>`

| Dado         | Valor                                                                      |
| ------------ | -------------------------------------------------------------------------- |
| Categoria    | `<informar a categoria do teste (usabilidade, desempenho, segurança, etc>` |
| Automatizado | `<Sim / Não>`                                                              |
| Responsável  |                                                                            |
| Data         |                                                                            |

##### Procedimentos

> [descreva os procedimentos do teste. São passos ordenados logicamente, caso um outro caso de teste precise ser executado antes, você pode mencionar diretamente “Executar o CT-XX”]

##### Resultado

> [indique o resultado esperado do teste)]
