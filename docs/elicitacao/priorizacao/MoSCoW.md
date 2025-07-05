## Introdução 

A técnica MoSCoW é utilizada para **priorizar requisitos** com base em sua importância para o sistema. Ela os categoriza em quatro grupos:

- **Must (Obrigatórios)** – Requisitos essenciais para o funcionamento mínimo do sistema.
- **Should (Importantes)** – Requisitos importantes, mas que podem ser entregues após os "Must".
- **Could (Desejáveis)** – Requisitos desejáveis, entregues se houver tempo/recursos.
- **Won’t (Não serão feitos agora)** – Requisitos que não serão implementados nesta versão.

## Tabela de participação 

<p style="text-align: center"><b>Tabela 1</b> - Tabela de contribuição.</p>

|Nome                                               | Atividade entregue                        | 
| ------------------------------------------------- | ----------------------------------------- | 
| [Jose Eduardo](https://github.com/jevprado)       | Criação do documento `1.0` <br> Criação do documento `2.0`, participação na entrevista e tabela MoSCoW.                          | 
| [Diassis](https://github.com/Diaxiz)                 | Participação na entrevista e criação da tabela MoSCoW.   | 
| [Thales Germano](https://github.com/thalesgvl)       | Revisor da versão `1.0` |

<font size="3"><p style="text-align: center">Fonte: [Jose Eduardo](https://github.com/jevprado), 2025.</p></font>

## Objetivo

A priorização foi realizada de forma presencial, com a participação de membros da equipe do projeto ([Jose Eduardo](https://github.com/jevprado) e [Diassis](https://github.com/Diaxiz)) como representantes da equipe 06 e Fernando dos Santos como entrevistado e usuário do aplicativo da Receita Federal, utilizando a técnica MoSCoW com o objetivo de priorizar os [Requisitos Elicitados](https://requisitos-de-software.github.io/2025.1-ReceitaFederal/elicitacao/requisitos-elicitados/) pelo grupo 06 anteriormente. 

## MoSCoW 

### Must  

<p style="text-align: center"><b>Tabela 2</b> - Tabela Must.</p>

| ID   | Descrição                                                                                    | Rastreabilidade |
|-------|---------------------------------------------------------------------------------------------| --------------- |
| RF01  | Acesso simultâneo a múltiplos CPFs/CNPJs                                                     | [ADC1](https://requisitos-de-software.github.io/2025.1-ReceitaFederal/elicitacao/analisededocumentos/) e [ST01](https://requisitos-de-software.github.io/2025.1-ReceitaFederal/elicitacao/storytelling/)            |
| RF02  | Cadastro de CPF via app (totalmente remoto)                                               |[ADC2](https://requisitos-de-software.github.io/2025.1-ReceitaFederal/elicitacao/analisededocumentos/)     |
| RF03  | Acompanhamento de status da restituição (precisão quanto aos lotes)                       | [ADC3](https://requisitos-de-software.github.io/2025.1-ReceitaFederal/elicitacao/analisededocumentos/) e [ST02](https://requisitos-de-software.github.io/2025.1-ReceitaFederal/elicitacao/storytelling/)     |
| RF04  | Notificação de vencimento próximo                                                          |  [ADC4](https://requisitos-de-software.github.io/2025.1-ReceitaFederal/elicitacao/analisededocumentos/)     |
| RF06  | Acesso offline a serviços essenciais do app (históricos de contribuições, DARFs)          |  [ADC6](https://requisitos-de-software.github.io/2025.1-ReceitaFederal/elicitacao/analisededocumentos/)     |
| RF07  | Alteração de dados via app                                                                |  [ADC7](https://requisitos-de-software.github.io/2025.1-ReceitaFederal/elicitacao/analisededocumentos/)    |
| RF20 | Acompanhar processos no próprio aplicativo                                                | [INT18](https://requisitos-de-software.github.io/2025.1-ReceitaFederal/elicitacao/introspeccao/)    |
| RF21 | Integração com o App Esocial dentro do próprio                                            |  [INT19](https://requisitos-de-software.github.io/2025.1-ReceitaFederal/elicitacao/introspeccao/)     |
| RF23 | Compartilhamento de comprovantes e certidões por WhatsApp, e-mail ou Drive                |  [INT21](https://requisitos-de-software.github.io/2025.1-ReceitaFederal/elicitacao/introspeccao/)     |
| RF24 | Reenvio de notificações perdidas via e-mail ou mensagem no app                            | [INT22](https://requisitos-de-software.github.io/2025.1-ReceitaFederal/elicitacao/introspeccao/)    |
| RF25 | Comparativo automático entre declarações de anos anteriores                               | [INT23](https://requisitos-de-software.github.io/2025.1-ReceitaFederal/elicitacao/introspeccao/)     |
| RF26 | FAQ interativo com busca inteligente (filtrado por tema: CPF, IRPF, Certidões etc.)       | [INT24](https://requisitos-de-software.github.io/2025.1-ReceitaFederal/elicitacao/introspeccao/)     |
| RF27 | Integração com calendário do dispositivo para lembretes de obrigações fiscais             | [INT25](https://requisitos-de-software.github.io/2025.1-ReceitaFederal/elicitacao/introspeccao/)     |
| RNF2 | Conteúdo educativo para iniciantes                                                         |[ADC14](https://requisitos-de-software.github.io/2025.1-ReceitaFederal/elicitacao/analisededocumentos/) e [ST08](https://requisitos-de-software.github.io/2025.1-ReceitaFederal/elicitacao/storytelling/)     |
| RNF4 | Proteção de dados pessoais conforme a LGPD                                                 | [ADC17](https://requisitos-de-software.github.io/2025.1-ReceitaFederal/elicitacao/analisededocumentos/)     |
| RNF6 | Interface com a possibilidade de uso do modo escuro                                        | [ADC23](https://requisitos-de-software.github.io/2025.1-ReceitaFederal/elicitacao/analisededocumentos/), [INT17](https://requisitos-de-software.github.io/2025.1-ReceitaFederal/elicitacao/introspeccao/) e [ST11](https://requisitos-de-software.github.io/2025.1-ReceitaFederal/elicitacao/storytelling/)     | 
|RNF18 | Armazenamento anônimo de logs de erro respeitando a LGPD                                   |[INT15](https://requisitos-de-software.github.io/2025.1-ReceitaFederal/elicitacao/introspeccao/)     
| RNF21 | Integração confiável com serviços externos (Gov.br, instituições financeiras)        | [ST13](https://requisitos-de-software.github.io/2025.1-ReceitaFederal/elicitacao/storytelling/)  e [ENT05](https://requisitos-de-software.github.io/2025.1-ReceitaFederal/elicitacao/entrevista/)    |

<font size="3"><p style="text-align: center">Fonte: [Jose Eduardo](https://github.com/jevprado) e [Diassis](https://github.com/Diaxiz) , 2025.</p></font>

### Should  

<p style="text-align: center"><b>Tabela 3</b> - Tabela Should.</p>


| ID   | Descrição                                                                                    | Rastreabilidade |
|-------|---------------------------------------------------------------------------------------------| --------------- |
| RF05  | Agendar no próprio aplicativo atendimentos presenciais em unidades da Receita Federal     |  [INT3](https://requisitos-de-software.github.io/2025.1-ReceitaFederal/elicitacao/introspeccao/)     |
| RF12 | Integração com conta Gov.br                                                               | [ADC12](https://requisitos-de-software.github.io/2025.1-ReceitaFederal/elicitacao/analisededocumentos/), [ST10](https://requisitos-de-software.github.io/2025.1-ReceitaFederal/elicitacao/storytelling/) e [ENT04](https://requisitos-de-software.github.io/2025.1-ReceitaFederal/elicitacao/entrevista/)  |
| RF14 | Acessar informações detalhadas a cerca da declaração de imposto de renda de um ano especifico         | [INT1](https://requisitos-de-software.github.io/2025.1-ReceitaFederal/elicitacao/introspeccao/)  e [ENT03](https://requisitos-de-software.github.io/2025.1-ReceitaFederal/elicitacao/entrevista/)   |
| RF15 | Declaração do Imposto de Renda diretamente pelo app | [INT2](https://requisitos-de-software.github.io/2025.1-ReceitaFederal/elicitacao/introspeccao/) e [ENT01](https://requisitos-de-software.github.io/2025.1-ReceitaFederal/elicitacao/entrevista/)   |
| RF18 | Consultar pendências de Malha                                                             |  [INT7](https://requisitos-de-software.github.io/2025.1-ReceitaFederal/elicitacao/introspeccao/)     |
| RF28 | Consulta de inscrição no CNPJ                                       | [INT26](https://requisitos-de-software.github.io/2025.1-ReceitaFederal/elicitacao/introspeccao/)     | 
| RF29 | Consulta de tabelas CNAE, NCM e unidades da Receita Federal         | [INT27](https://requisitos-de-software.github.io/2025.1-ReceitaFederal/elicitacao/introspeccao/)    |   
| RF32 | Consultar débitos pendentes (DARFs) | [ST04](https://requisitos-de-software.github.io/2025.1-ReceitaFederal/elicitacao/storytelling/)    | 
| RF33 | Pagamento do DARF com cartão de crédito | [ST05](https://requisitos-de-software.github.io/2025.1-ReceitaFederal/elicitacao/storytelling/)    |  
| RF34 | Emitir comprovante de CPF em PDF | [ST07](https://requisitos-de-software.github.io/2025.1-ReceitaFederal/elicitacao/storytelling/)    |  
| RNF3 | Testes de desempenho para suportar alta demanda de usuários simultâneos                    |  [ADC15](https://requisitos-de-software.github.io/2025.1-ReceitaFederal/elicitacao/analisededocumentos/)     |
| RNF7 | Testes de segurança para garantir a integridade dos dados e autenticação segura            | [ADC19](https://requisitos-de-software.github.io/2025.1-ReceitaFederal/elicitacao/analisededocumentos/)     |
| RNF8 | Compatível com Android 8+ e iOS 14+                                                        |  [ADC20](https://requisitos-de-software.github.io/2025.1-ReceitaFederal/elicitacao/analisededocumentos/)    |
| RNF13| O app deve suportar modo de operação em baixa conectividade, com cache de dados essenciais |  [INT11](https://requisitos-de-software.github.io/2025.1-ReceitaFederal/elicitacao/introspeccao/)    |
| RNF14 | Atualizações do app não devem causar perda de dados armazenados localmente                 |  [INT12](https://requisitos-de-software.github.io/2025.1-ReceitaFederal/elicitacao/introspeccao/)    |
| RNF17 | Suporte a leitores de tela (TalkBack, VoiceOver) em todas as funcionalidades               |  [INT14](https://requisitos-de-software.github.io/2025.1-ReceitaFederal/elicitacao/introspeccao/) e [ADC22](https://requisitos-de-software.github.io/2025.1-ReceitaFederal/elicitacao/analisededocumentos/)  |
| RNF19 | Versão mínima em HTML5 responsiva para acesso via navegador em caso de falha do app        |  [INT16](https://requisitos-de-software.github.io/2025.1-ReceitaFederal/elicitacao/introspeccao/)     |
| RNF20 | Clareza na apresentação de dados fiscais        | [ST12](https://requisitos-de-software.github.io/2025.1-ReceitaFederal/elicitacao/storytelling/)     |




<font size="3"><p style="text-align: center">Fonte: [Jose Eduardo](https://github.com/jevprado) e [Diassis](https://github.com/Diaxiz) , 2025.</p></font>

### Could  

<p style="text-align: center"><b>Tabela 4</b> - Tabela Could.</p>

| ID   | Descrição                                                                                    | Rastreabilidade |
|-------|---------------------------------------------------------------------------------------------| --------------- |
| RF08  | Funcionalidade de histórico e acompanhamento de restituições de anos anteriores             |   [ADC8](https://requisitos-de-software.github.io/2025.1-ReceitaFederal/elicitacao/analisededocumentos/)     |
| RF10 | Geração de guias de pagamento                                                             |   [ADC10](https://requisitos-de-software.github.io/2025.1-ReceitaFederal/elicitacao/analisededocumentos/), [ST03](https://requisitos-de-software.github.io/2025.1-ReceitaFederal/elicitacao/storytelling/)    |
| RF13 | Envio de documentos para instrução de processos                                           |  [ADC16](https://requisitos-de-software.github.io/2025.1-ReceitaFederal/elicitacao/analisededocumentos/)     |
| RF16 | O aplicativo deve mostrar um histórico de envio das declarações entregues pelo usuário.             |  [INT5](https://requisitos-de-software.github.io/2025.1-ReceitaFederal/elicitacao/introspeccao/), [ST09](https://requisitos-de-software.github.io/2025.1-ReceitaFederal/elicitacao/storytelling/)     |
| RF17 | Emissão de certidão negativa via aplicativo                                               |  [INT6](https://requisitos-de-software.github.io/2025.1-ReceitaFederal/elicitacao/introspeccao/) e [ENT02](https://requisitos-de-software.github.io/2025.1-ReceitaFederal/elicitacao/entrevista/)    |Validado|
| RF22 | Permitir via App autorização de acesso à terceiros                                        |  [INT20](https://requisitos-de-software.github.io/2025.1-ReceitaFederal/elicitacao/introspeccao/)   |
| RF30 | Acesso à Caixa Postal para mensagens oficiais da Receita Federal    |  [INT28](https://requisitos-de-software.github.io/2025.1-ReceitaFederal/elicitacao/introspeccao/)    |  
| RF31 | Visualização de notícias e vídeos institucionais da Receita Federal | [INT29](https://requisitos-de-software.github.io/2025.1-ReceitaFederal/elicitacao/introspeccao/)    |  
| RNF1 | Acessibilidade (chatbot, imagens, vídeos) — melhorias no chatbot                 | [ADC13](https://requisitos-de-software.github.io/2025.1-ReceitaFederal/elicitacao/analisededocumentos/)     |
| RNF5 | Interface responsiva e acessível                                                           | [ADC18](https://requisitos-de-software.github.io/2025.1-ReceitaFederal/elicitacao/analisededocumentos/)     |
| RNF12 | Linguagem da interface deve seguir padrão A2 do CEFR, evitando jargões técnicos            | [ADC25](https://requisitos-de-software.github.io/2025.1-ReceitaFederal/elicitacao/analisededocumentos/)    |
| RNF16 | Tempo de carregamento inicial do app não deve ultrapassar 5 segundos em conexão móvel      | [ADC24](https://requisitos-de-software.github.io/2025.1-ReceitaFederal/elicitacao/analisededocumentos/)    |

<font size="3"><p style="text-align: center">Fonte: [Jose Eduardo](https://github.com/jevprado) e [Diassis](https://github.com/Diaxiz) , 2025.</p></font>

### Won't  

<p style="text-align: center"><b>Tabela 5</b> - Tabela Won't.</p>

| ID    | Descrição                                                                                    | Rastreabilidade |
|-------|--------------------------------------------------------------------------------------------- | --------------- |
| RF19 | Dashboard para profissionais contábeis de múltiplos CPFs/CNPJs                            |  [INT8](https://requisitos-de-software.github.io/2025.1-ReceitaFederal/elicitacao/introspeccao/), [ST14](https://requisitos-de-software.github.io/2025.1-ReceitaFederal/elicitacao/storytelling/)     |Validado|
| RNF9 | Testes de usabilidade semestrais com público 60+                                           | [ADC21](https://requisitos-de-software.github.io/2025.1-ReceitaFederal/elicitacao/analisededocumentos/)    |
| RNF10| O aplicativo deve ter tempo de resposta inferior a 3 segundos para ações comuns            |  [INT9](https://requisitos-de-software.github.io/2025.1-ReceitaFederal/elicitacao/introspeccao/)     |
| RNF11| O aplicativo deve funcionar em smartphones com telas de 4.5" a 7" sem perda de usabilidade | [INT10](https://requisitos-de-software.github.io/2025.1-ReceitaFederal/elicitacao/introspeccao/)     |
| RNF15 | Tempo de inatividade programada máximo de 2h por mês, com aviso prévo                      | [INT13](https://requisitos-de-software.github.io/2025.1-ReceitaFederal/elicitacao/introspeccao/)     |


<font size="3"><p style="text-align: center">Fonte: [Jose Eduardo](https://github.com/jevprado) e [Diassis](https://github.com/Diaxiz) , 2025.</p></font>


## Entrevista com usuário  

<p style="text-align: center"><b>Vídeo 1</b> - Execução da técnica MoSCoW </p>

<iframe width="700" height="400"
        src="https://www.youtube.com/embed/dNmnlOIgb7I"
        title="YouTube video player"
        frameborder="0"
        allow="accelerometer; autoplay; clipboard-write; encrypted-media; gyroscope; picture-in-picture; web-share"
        referrerpolicy="strict-origin-when-cross-origin"
        allowfullscreen>
</iframe>

<font size="3"><p style="text-align: center">Fonte: [Jose Eduardo](https://github.com/jevprado), 2025.</p></font>


## Referências 

> <a>1.</a> Wiegers, K., & Beatty, J. (2013). Software Requirements (3rd ed.). Microsoft Press. 
>
> <a>2.</a> Product Plan. Disponível em: [https://www.productplan.com/glossary/moscow-prioritization/](). Acesso em: 03 de maio. de 2025.
>
> <a>3.</a> SERRANO, Milene; SERRANO, Maurício. Requisitos (Aula 07): Elicitação, Modelagem e Análise. 2025. Disponível em: [https://aprender3.unb.br/pluginfile.php/3096086/mod_resource/content/2/Requisitos%20-%20Aula%2007.pdf]()  Acesso em: 03 de maio. de 2025.
>

## Histórico de versões

Versão |   Data  | Descrição | Autor(es) | Revisor(es)
------ | ---- | ------ | ---------- | ----------
`1.0` | 04/05/2025 | Criação do primeiro documento MoSCoW | [Jose Eduardo](https://github.com/jevprado) e [Andre Lopes](https://github.com/andrewslopes) | [Diassis](https://github.com/Diaxiz) |
`2.0` | 04/07/2025 | Refatoração do documento MoSCoW com requisitos elicitados atualizados e adição do vídeo com usuário | [Jose Eduardo](https://github.com/jevprado) e [Diassis](https://github.com/Diaxiz) | REVISOR AQUI |