# NFR Framework

## Introdução

De acordo com a abordagem apresentada por **Reinaldo Antônio da Silva (2019)**, o NFR Framework é um modelo utilizado na modelagem de Requisitos Não-Funcionais (RNFs), baseado em *softgoals*. Esses objetivos não possuem uma definição clara ou critérios de sucesso bem estabelecidos, o que os torna ideais para representar qualidades subjetivas dos sistemas.

Os *softgoals* ajudam desenvolvedores a tomar decisões durante o projeto, considerando aspectos como qualidade, segurança e desempenho. Além disso, podem influenciar uns aos outros, criando uma rede de impactos que afetam o sistema como um todo.

### Tipos de Softgoals

Os *softgoals* podem ser classificados em três grupos principais: 

1. **Softgoals NFR**: Representam diretamente os Requisitos Não-Funcionais e podem ser organizados de forma hierárquica.
2. **Softgoals de Operacionalização**: Apontam para alternativas de implementação dos softgoals NFR, por meio de funções, estruturas ou restrições.
3. **Softgoals de Afirmação**: Representam justificativas baseadas em conhecimento de domínio ou prioridades, servindo como base para apoiar ou refutar decisões de projeto e seleção de alternativas.

<p style="text-align: center"><b>Figura 1</b> - Tipos de Softgoal </p>

![tipos-nfr](../assets/nfr/tipos-nfr.png)


<font size="3"><p style="text-align: center">Fonte: Silva, 2019.</p></font>

O atendimento aos *softgoals* é avaliado qualitativamente por meio de rótulos como **satisfeito**, **parcialmente satisfeito** ou **não satisfeito**, com base nas contribuições positivas ou negativas entre os nós no **Softgoal Interdependency Graph (SIG)**.

> **Nota**: O *Softgoal Interdependency Graph (SIG)* é um grafo que mostra como diferentes objetivos não-funcionais estão inter-relacionados, ajudando a visualizar conflitos e sinergias entre eles.

## Interdependências entre Softgoals

As **interdependências** representam as associações existentes entre os softgoals no NFR Framework. Elas se dividem em dois grandes grupos: **decomposições** e **contribuições**.

### Decomposições

As **decomposições** ocorrem em diferentes níveis de abstração, incluindo softgoals de NFR (requisitos não funcionais), de operacionalização e de afirmação. De acordo com Silva (2019), as três primeiras categorias envolvem a subdivisão de um softgoal em metas mais específicas, facilitando seu entendimento e análise. Há ainda uma decomposição especial voltada à priorização.

Os principais tipos de decomposição são:

- **Decomposição NFR:** utilizada para quebrar metas amplas e complexas em partes menores e mais manejáveis. Essa divisão ajuda a reduzir ambiguidades e a facilitar a definição de prioridades.

- **Decomposição de Operacionalização:** visa transformar uma solução genérica em soluções específicas, mais diretamente implementáveis no sistema.

- **Decomposição de Afirmação:** empregada para justificar ou refutar determinadas escolhas de projeto com base em argumentos técnicos ou estratégicos.

- **Decomposição de Priorização:** trata-se de uma decomposição especial em que um softgoal é refinado em outro do mesmo tipo e tópico, mas com a adição de um critério de prioridade. Essa abordagem permite destacar a relevância relativa de diferentes metas.

Essas decomposições são representadas graficamente nos modelos do NFR Framework por meio de conexões entre nós (softgoals), utilizando-se setas e operadores lógicos (como AND/OR) para indicar a natureza da decomposição.

<p style="text-align: center"><b>Figura 2</b> - Tipos de decomposição </p>

![decomposicao-nfr](../assets/nfr/decomposicao-nfr.png)


<font size="3"><p style="text-align: center">Fonte: Silva, 2019.</p></font>


### Contribuições

No NFR Framework, os softgoals são progressivamente refinados em metas mais específicas. Como resultado, um softgoal derivado pode contribuir de forma total ou parcial — e tanto positiva quanto negativamente — para o softgoal original. A seguir, listam-se os tipos de contribuição:

- AND: se os softgoals derivados forem satisfeitos, o softgoal primordial também será.
- OR: se algum dos softgoals derivados forem satisfeitos, o softgoal primordial também será.
- MAKE(++): um softgoal originado contribui de forma plenamente positiva, logo o softgoal original também será satisfeito.
- BREAK(--): um softgoal originado contribui de forma plenamente negativa, logo o softgoal original será negado.
- HELP(+): um softgoal originado realiza uma contribuição restritamente positiva, o que reflete da mesma forma e na mesma intensidade no softgoal primordial.
- HURT(-): um softgoal originado realiza uma contribuição restritamente negativa, o que reflete da mesma forma e na mesma intensidade no softgoal primordial.
- UNKNOWN(?): contribuição incógnita.
- EQUALS: relação direta entre as satisfações do softgoal derivado e a do primordial.
- SOME: a forma de contribuição é conhecida, no entanto, a intensidade dessa contribuição é desconhecida.

---
### Propagação de impactos 

A **propagação de impactos** no NFR Framework diz respeito à análise das relações de dependência entre os requisitos não funcionais, avaliando como alterações em um softgoal podem influenciar outros com os quais mantém algum tipo de vínculo. Essa avaliação é essencial para identificar **efeitos colaterais**, **conflitos** e **contribuições acumuladas** que podem afetar diretamente a qualidade geral do sistema.

Para que essa análise seja eficaz, é necessário compreender com clareza:
- As **interações entre os softgoals**;
- As **prioridades atribuídas a cada meta de qualidade**;
- Os **possíveis trade-offs** entre requisitos concorrentes.

Ao considerar a propagação de impactos, os engenheiros de requisitos conseguem tomar **decisões mais conscientes**, identificar **pontos críticos do sistema** e **gerenciar mudanças** de forma mais segura e estruturada.

**Tipos de Impacto entre Softgoals**

A seguir, são apresentados os tipos mais comuns de impacto entre softgoals, junto com suas respectivas notações simbólicas, conforme utilizados no NFR Framework:

- **✓ (Satisfeito)**
  Indica que um requisito não funcional contribui de forma clara e significativa para a satisfação de outro softgoal. Representa uma relação de impacto **fortemente positiva**.

- **𝒲+ (Fracamente satisfeito)**
  Indica uma contribuição positiva, porém **moderada**. O requisito relacionado apoia o softgoal-alvo, mas sua influência é limitada ou indireta.

- **✗ (Negado)**
  Indica que o requisito em questão tem um impacto **negativo direto**, impedindo ou contradizendo a realização de outro softgoal.

- **𝒲− (Fracamente negado)**  
  Representa uma **influência negativa mais fraca**, que pode dificultar, mas não necessariamente inviabilizar, o alcance do softgoal afetado.

- **🗲 (Conflitante)** 
  Indica a existência de um **conflito** entre softgoals. A realização de um pode beneficiar alguns aspectos e prejudicar outros, exigindo negociação e priorização.

- **? (Indeterminado)**
  Utilizado quando a relação entre dois requisitos não funcionais é **desconhecida ou incerta**. Pode indicar falta de informação ou necessidade de análise posterior.


## Metodologia

A metodologia adotada nesta aplicação do NFR Framework seguiu uma abordagem prática e colaborativa, baseada nos princípios de **Reinaldo Antônio da Silva (2019)**, com foco na coleta, organização e análise de requisitos não funcionais relacionados ao sistema da Receita Federal.

Cada integrante do grupo foi responsável por duas funcionalidades específicas do sistema, sendo também responsável por levantar e modelar os requisitos não funcionais associados à sua área. Os RNFs foram obtidos por meio de técnicas de elicitação, como introspecção e análise de documentos.

A Tabela 1 apresenta a distribuição das funcionalidades por integrante:

<p style="text-align: center"><b>Tabela 1</b> - Distribuição de funcionalidades por integrante</p>

| Funcionalidade               | Integrante Responsável |
|-----------------------------|------------------------|
| [Funcionalidade A]          | [Nome 1]               |
| [Funcionalidade B]          | [Nome 2]               |
| ...                         | ...                    |
| [Funcionalidade N]          | [Nome N]               |

<p style="text-align: center"><b>Tabela 1</b> - Distribuição de funcionalidades por integrante</p>

Com base nessa divisão, os requisitos não funcionais foram mapeados, classificados em softgoals e organizados em modelos gráficos segundo os conceitos do NFR Framework.

### Cartões de Especificação

Para facilitar o registro e o rastreamento das decisões de projeto, foram utilizados **Cartões de Especificação de Requisitos Não-Funcionais**, apresentados nas Tabelas 2 a N. Cada cartão contém os seguintes campos:


| Campo              | Descrição                                                                 |
|--------------------|---------------------------------------------------------------------------|
| Nº do Requisito    | Identificador único do requisito (ex: RNF01, RNF02...)                   |
| Descrição          | Texto explicativo sobre o que o requisito exige ou pretende garantir     |
| Classificação      | FURPS+    |
| Origem             | Fonte do requisito (ex: usuário, legislação, análise técnica)             |
| Justificativa      | Razão pela qual o requisito foi definido (ex: atender à LGPD)            |
|Critério de aceitação| Condições que devem ser atendidas para considerar o requisito cumprido                                                                       |
| Dependência        | Outros requisitos dos quais este depende ou se relaciona                 |
| Prioridade         | Nível de importância (Alta, Média ou Baixa)                              |
| Conflitos          | Possíveis requisitos com os quais este pode gerar conflito               |
| Histórias          | Histórias de usuário relacionadas ao requisito, se aplicável             |



### RNF 1 

| Campo              | Descrição                                                                 |
|--------------------|---------------------------------------------------------------------------|
| Nº do Requisito    | RNF 01                                       |
| Descrição          |  Melhorias no chatbot, suporte a imagens descritivas e vídeos com legenda para garantir acessibilidade a usuários com deficiência visual ou auditiva.     |
| Classificação      | Usabilidade     |
| Origem             | Fonte do requisito (ex: usuário, legislação, análise técnica)             |
| Justificativa      | Razão pela qual o requisito foi definido (ex: atender à LGPD)            |
|Critério de aceitação| Condições que devem ser atendidas para considerar o requisito cumprido                                                                       |
| Dependência        | Outros requisitos dos quais este depende ou se relaciona                 |
| Prioridade         | Nível de importância (Alta, Média ou Baixa)                              |
| Conflitos          | Possíveis requisitos com os quais este pode gerar conflito               |
| Histórias          | Histórias de usuário relacionadas ao requisito, se aplicável             |









## Referências

SILVA, Reinaldo Antônio da. *NFR4ES: Um Catálogo de Requisitos Não-Funcionais para Sistemas Embarcados*. Recife: Universidade Federal de Pernambuco, 2019.
Disponível em: [https://aprender3.unb.br/pluginfile.php/3096155/mod\_resource/content/2/DISSERTA%C3%87%C3%83O%20Reinaldo%20Ant%C3%B4nio%20da%20Silva.pdf](https://aprender3.unb.br/pluginfile.php/3096155/mod_resource/content/2/DISSERTA%C3%87%C3%83O%20Reinaldo%20Ant%C3%B4nio%20da%20Silva.pdf)

## Histórico de Versão

| Versão | Data       | Descrição                          | Autor                                          | Revisor                                     |
| ------ | ---------- | ---------------------------------- | ---------------------------------------------- | ------------------------------------------- |
| `1.0`     | 29/05/2025 | Criação do documento NRF-framework | [Thales Germano](https://github.com/thalesgvl) | [Jose Eduardo](https://github.com/jevprado) |
| `1.1`    | 29/05/2025 | Ajustes no documento | [Thales Germano](https://github.com/thalesgvl) |[Jose Eduardo](https://github.com/jevprado)|
| `1.2`    | 01/06/2025 | Adicionando imagens e tópicos decomposição e contribuição | [Jose Eduardo](https://github.com/jevprado) | [Thales Germano](https://github.com/thalesgvl) |