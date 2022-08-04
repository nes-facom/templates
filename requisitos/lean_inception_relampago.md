<div align="center">

<img alt="Cabeçalho UFMS" src="/.assets/cabecalho_docs.png" />

## Lean Inception Relâmpago

</div>

### 1. Introdução

Este documento registra a metodologia utilizada em workshops de _Inception Relâmpago_[^1] - uma sessão de poucas horas que gera a visão do produto, os objetivos do projeto, personas, e feature mapping. O tempo recomendado pelo autor é de entre três e quatro horas. A metodologia se baseia na [Lean Inception](https://www.caroli.org/lean-inception/).

Algumas atividades foram adaptadas utilizando artefatos do Lean Inception padrão retirados [deste template](https://miro.com/miroverse/lean-inception-workshop/).

[^1]: Descrição do autor da Lean Inception Relâmpago: https://www.caroli.org/inception-relampago-template-de-agenda-e-documentos-colaborativos/

### 2. Glossário de termos

##### Visão

O entendimento da necessidade do produto guiará as atividades da inception. Os conceitos apresentados inicialmente são apenas uma visão, e a ideia será refinada durante a inception.

##### Objetivos

Cada membro da equipe deve compartilhar o que entende sobre os objetivos do projeto, e isto deve ser discutido para que o time alcance um consenso sobre o que é realmente importante.

##### Personas

Para efetivamente identificar as funcionalidades de um sistema, consideramos importante ter em mente os usuários e seus objetivos. A maneira que normalmente utilizamos para representar estes usuários é através de personas.

Uma persona representa um usuário do sistema, descrevendo não só o seu papel, mas também suas necessidades específicas. Isto cria uma representação realística de usuários, auxiliando o time a descrever funcionalidades do ponto de vista de quem interagirá com o produto final.

##### Features

Feature é um agrupamento de funcionalidades afins. Tal agrupamento nos ajuda com a compreensão sobre o requisito como um todo, bem como das suas partes menores e complementares. O entendimento de feature vai variar de time para time. O importante é que tal agrupamento faça sentido para aquela equipe.

##### Feature Mapping

A partir de um conjunto de features precisamos elaborar um plano de execução. Para isto, adicionamos dados de capacidade da equipe, sequenciamento lógico, prioridade e tempo. O feature mapping é uma representação visual deste plano.

### 3. Agenda

|   Data/Hora    | Duração prevista | Atividade                                    |
| :------------: | :--------------: | -------------------------------------------- |
| 01/01/22 18h30 |      5 min       | Construindo o burn-up da Inception Relâmpago |
|                |      15 min      | Visão do produto                             |
|                |      10 min      | Esclarecendo Objetivos                       |
|                |      10 min      | Identificando Personas                       |
|                |      15 min      | Descobrindo as Features                      |
|                |                  |                                              |
| 02/01/22 18h30 |      30 min      | Revisão técnica das Features                 |
|                |      20 min      | Criação do Feature Mapping                   |

### 4. Visão do produto

|                   |                                            |
| :---------------: | ------------------------------------------ |
|       Para        | `[cliente final]`                          |
|       Cujo        | `[problema que precisa ser resolvido]`     |
|         O         | `[nome do produto]`                        |
|       É um        | `[categoria do produto]`                   |
|        Que        | `[benefício chave, razão para adquirí-lo]` |
| Diferentemente da | `[alternativa da concorrência]`            |
|  O nosso produto  | `[diferença chave]`                        |

#### 4.2. É/Não é, Faz/Não faz

| É                  | Não é                  |
| ------------------ | ---------------------- |
| `[o produto é um]` | `[o produto não é um]` |

| Faz               | Não faz               |
| ----------------- | --------------------- |
| `[o produto faz]` | `[o produto não faz]` |

### 5. Objetivos

| Objetivo maior       | Objetivo       | Descrição |
| -------------------- | -------------- | --------- |
| `[objetivo maior 1]` | `[objetivo 1]` |           |
|                      | `[objetivo 2]` |           |
|                      | `[objetivo 3]` |           |
|                      |                |           |
| `[objetivo maior 2]` | `[objetivo 4]` |           |

### 6. Personas

| Persona             | Perfil               | Comportamento           | Necessidades                |
| ------------------- | -------------------- | ----------------------- | --------------------------- |
| `[nome da persona]` | `[quem é a persona]` | `[o que a persona faz]` | `[o que a persona precisa]` |

### 7. Features

> ##### Instrução:
>
> 1. Listar os objetivos como títulos das colunas
> 2. Listar as personas como títulos das linhas
> 3. Fazer a seguinte pergunta: o que a persona X precisa no sistema para alcançar o objetivo Y?
> 4. Repetir o passo 3, e reorganizar as features listadas

| Persona       | `[objetivo 1]` | `[objetivo 2]` | `[objetivo 3]` |
| ------------- | -------------- | -------------- | -------------- |
| `[persona 1]` |                |                |                |
| `[persona 2]` |                |                |                |
| `[persona 3]` |                |                |                |

> _Obs: apesar da atividade começar com objetivos e personas, a lista de features geradas não necessariamente faz um mapeamento entre objetivos e personas. Na minha experiencia, o formato tabular ajuda com o brainstorming, mas não vale a pena mantê-lo._ [^2]

[^2]: _"template de inception relampago - features"_: https://docs.google.com/drawings/d/1A3vENXXopKEs6GWvA7FslOLVy2kojpSbeO1Dcq00q0A/edit

### 8. Revisão técnica

> ##### Classificação
>
> A classificação de uma feature é dada com base no quanto a equipe técnica sabe `o que deve ser feito` _vs._ o quanto ela sabe `como colocar isso em prática`.
>
> | _O que fazer?_ / _Como fazer?_ |    Baixo     |      Médio      |      Alto       |
> | :----------------------------: | :----------: | :-------------: | :-------------: |
> |              Alto              | :red_circle: | :yellow_circle: | :green_circle:  |
> |             Médio              | :red_circle: |  :red_circle:   | :yellow_circle: |
> |             Baixo              | :red_circle: |  :red_circle:   |  :red_circle:   |

| Feature       | Esforço :construction_worker: <sub>(1-3)</sub> | Valor :dollar: <sub>(1-3)</sub> | UX :heart: <sub>(1-3)</sub> |  Classificação  |
| ------------- | :--------------------------------------------: | :-----------------------------: | :-------------------------: | :-------------: |
| `[feature 1]` |                       3                        |                2                |              3              | :green_circle:  |
| `[feature 2]` |                                                |                                 |                             | :yellow_circle: |
| `[feature 3]` |                                                |                                 |                             |  :red_circle:   |

### 9. Feature Mapping

> ##### Regras [^3]
>
> 1. Uma onda pode conter um máximo de 3 features
> 2. Uma onda não pode ter mais de uma feature :red_circle:
> 3. Uma onda não pode conter 3 features apenas :yellow_circle: ou :red_circle:
> 4. O esforço total de uma onda não pode exceder 5 :construction_worker:
> 5. A soma do valor dos features não pode ser menor que 4 :dollar: e 4 :heart:
> 6. Se uma feature depende de outro, esse outra feature deve estar em uma onda anterior
>
> Inserir `<MVP>`, `<incremento>` ou `<v.1.0.0>` para demarcar quando os incrementos serão finalizados

[^3]: Template Lean Inception Workshop | miro.com: https://miro.com/miroverse/lean-inception-workshop/

| Onda |                                                                          |                                                                          |                                                                          |
| :--: | :----------------------------------------------------------------------: | :----------------------------------------------------------------------: | :----------------------------------------------------------------------: |
|  1   | `[feature 1]` (3:construction_worker:/2:dollar:/3:heart:/:green_circle:) | `[feature 2]` (3:construction_worker:/2:dollar:/3:heart:/:green_circle:) | `[feature 3]` (3:construction_worker:/2:dollar:/3:heart:/:green_circle:) |
|  2   |                                 `<MVP>`                                  | `[feature 4]` (3:construction_worker:/2:dollar:/3:heart:/:green_circle:) |                                `<v1.0.0>`                                |
|  3   |                                                                          |                                                                          |                                                                          |
|  4   |                                                                          |                                                                          |                                                                          |

### 10. Referências úteis

- [FunRestrospectives](https://www.funretrospectives.com/)
