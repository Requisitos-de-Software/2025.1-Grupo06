# Requisitos elicitados 

## Introdução 

Esta página tem como objetivo compilar todos os requisitos elicitados para o aplicativo da Receita Federal, com base em diversas técnicas utilizadas na etapa 02 do projeto. Foram aplicadas abordagens como **personas**, **storytelling**, **grupo de foco** e **analise de documentos**, que permitiram uma compreensão mais ampla e detalhada das necessidades dos usuários e dos processos envolvidos.

Os requisitos identificados estão organizados em duas categorias principais:

Requisitos Funcionais, que descrevem as funcionalidades que o sistema deve oferecer.

Requisitos Não Funcionais, que especificam restrições e qualidades esperadas do sistema, como desempenho, usabilidade e segurança.


## Tabela de requisitos elicitados 

### Tabela 01 - Requisitos Funcionais

<p style="text-align: center"><b>Tabela 1</b> - Tabela de requisitos  funcionais elicitados </p>

| ID   | Descrição                                                                                 | Categoria | Status da implemntação       | Fonte |Validada | 
| ---- | ----------------------------------------------------------------------------------------- | --------- | ---------------- | ----- | ----- | 
| RF01  | Acesso simultâneo a múltiplos CPFs/CNPJs                                         | RF        | NÃO IMPLEMENTADO | [ADC1](https://requisitos-de-software.github.io/2025.1-ReceitaFederal/elicitacao/analisededocumentos/), [ST01](https://requisitos-de-software.github.io/2025.1-ReceitaFederal/elicitacao/storytelling/)   | - |
| RF02  | Cadastro de CPF via app (totalmente remoto)                                               | RF        | NÃO IMPLEMENTADO |[ADC2](https://requisitos-de-software.github.io/2025.1-ReceitaFederal/elicitacao/analisededocumentos/)     |- |
| RF03  | Acompanhamento de status da restituição (precisão quanto aos lotes)                       | RF        | NÃO IMPLEMENTADO | [ADC3](https://requisitos-de-software.github.io/2025.1-ReceitaFederal/elicitacao/analisededocumentos/), [ST02](https://requisitos-de-software.github.io/2025.1-ReceitaFederal/elicitacao/storytelling/)     |- |
| RF04  | Notificação de vencimento próximo                                                         | RF        | NÃO IMPLEMENTADO |  [ADC4](https://requisitos-de-software.github.io/2025.1-ReceitaFederal/elicitacao/analisededocumentos/)     |- |
| RF05  | Agendar no próprio aplicativo atendimentos presenciais em unidades da Receita Federal     | RF        | NÃO IMPLEMENTADO |  [INT3](https://requisitos-de-software.github.io/2025.1-ReceitaFederal/elicitacao/introspeccao/)     |- |
| RF06  | Acesso offline a serviços essenciais do app (históricos de contribuições, DARFs)          | RF        | NÃO IMPLEMENTADO | [ADC6](https://requisitos-de-software.github.io/2025.1-ReceitaFederal/elicitacao/analisededocumentos/)     |- |
| RF07  | Alteração de dados via app                                                                | RF        | NÃO IMPLEMENTADO |  [ADC7](https://requisitos-de-software.github.io/2025.1-ReceitaFederal/elicitacao/analisededocumentos/)    |- |
| RF08  | Funcionalidade de histórico e acompanhamento de restituições de anos anteriores             | RF        | IMPLEMENTADO     |  [ADC8](https://requisitos-de-software.github.io/2025.1-ReceitaFederal/elicitacao/analisededocumentos/)     |- |
| RF09  | Declaração simplificada do IR                                                             | RF        | IMPLEMENTADO     |  [ADC9](https://requisitos-de-software.github.io/2025.1-ReceitaFederal/elicitacao/analisededocumentos/)     |- |
| RF10 | Geração de guias de pagamento                                                             | RF        | IMPLEMENTADO     |  [ADC10](https://requisitos-de-software.github.io/2025.1-ReceitaFederal/elicitacao/analisededocumentos/), [ST03](https://requisitos-de-software.github.io/2025.1-ReceitaFederal/elicitacao/storytelling/)    |- |
| RF11 | Consultar o status do CPF (ativo ou não)                                                  | RF        | IMPLEMENTADO     |  [ADC11](https://requisitos-de-software.github.io/2025.1-ReceitaFederal/elicitacao/analisededocumentos/), [ST06](https://requisitos-de-software.github.io/2025.1-ReceitaFederal/elicitacao/storytelling/)    |- |
| RF12 | Integração com conta Gov.br                                                               | RF        | IMPLEMENTADO     |  [ADC12](https://requisitos-de-software.github.io/2025.1-ReceitaFederal/elicitacao/analisededocumentos/), [ST10](https://requisitos-de-software.github.io/2025.1-ReceitaFederal/elicitacao/storytelling/)   |- |
| RF13 | Envio de documentos para instrução de processos                                           | RF        | IMPLEMENTADO     |  [ADC16](https://requisitos-de-software.github.io/2025.1-ReceitaFederal/elicitacao/analisededocumentos/)     |- |
| RF14 | Acessar informações detalhadas a cerca da declaração de imposto de renda de um ano especifico         | RF        | IMPLEMENTADO     | [INT1](https://requisitos-de-software.github.io/2025.1-ReceitaFederal/elicitacao/introspeccao/)     |- |
| RF15 | O aplicativo deve permitir o envio da declaração do Imposto de Renda diretamente pelo app | RF        | IMPLEMENTADO     |[INT2](https://requisitos-de-software.github.io/2025.1-ReceitaFederal/elicitacao/introspeccao/)     |- |
| RF16 | O aplicativo deve mostrar um histórico de envio das declarações entregues pelo usuário.             | RF        | IMPLEMENTADO     | [INT5](https://requisitos-de-software.github.io/2025.1-ReceitaFederal/elicitacao/introspeccao/), [ST09](https://requisitos-de-software.github.io/2025.1-ReceitaFederal/elicitacao/storytelling/)     |- |
| RF17 | Emissão de certidão negativa via aplicativo                                               | RF        | IMPLEMENTADO     | [INT6](https://requisitos-de-software.github.io/2025.1-ReceitaFederal/elicitacao/introspeccao/)     |- |
| RF18 | Consultar pendências de Malha                                                             | RF        | IMPLEMENTADO     | [INT7](https://requisitos-de-software.github.io/2025.1-ReceitaFederal/elicitacao/introspeccao/)     |- |
| RF19 | Dashboard para profissionais contábeis de múltiplos CPFs/CNPJs                            | RF        | NÃO IMPLEMENTADO | [INT8](https://requisitos-de-software.github.io/2025.1-ReceitaFederal/elicitacao/introspeccao/), [ST14](https://requisitos-de-software.github.io/2025.1-ReceitaFederal/elicitacao/storytelling/)     |- |
| RF20 | Acompanhar processos no próprio aplicativo                                                | RF        | NÃO IMPLEMENTADO | [INT18](https://requisitos-de-software.github.io/2025.1-ReceitaFederal/elicitacao/introspeccao/)    |- |
| RF21 | Integração com o App Esocial dentro do próprio                                            | RF        | NÃO IMPLEMENTADO | [INT19](https://requisitos-de-software.github.io/2025.1-ReceitaFederal/elicitacao/introspeccao/)     |- |
| RF22 | Permitir via App autorização de acesso à terceiros                                        | RF        | IMPLEMENTADO     | [INT20](https://requisitos-de-software.github.io/2025.1-ReceitaFederal/elicitacao/introspeccao/)   |- |
| RF23 | Compartilhamento de comprovantes e certidões por WhatsApp, e-mail ou Drive                | RF        | NÃO IMPLEMENTADO | [INT21](https://requisitos-de-software.github.io/2025.1-ReceitaFederal/elicitacao/introspeccao/)     |- |
| RF24 | Reenvio de notificações perdidas via e-mail ou mensagem no app                            | RF        | NÃO IMPLEMENTADO | [INT22](https://requisitos-de-software.github.io/2025.1-ReceitaFederal/elicitacao/introspeccao/)    |- |
| RF25 | Comparativo automático entre declarações de anos anteriores                               | RF        | NÃO IMPLEMENTADO | [INT23](https://requisitos-de-software.github.io/2025.1-ReceitaFederal/elicitacao/introspeccao/)     |- |
| RF26 | FAQ interativo com busca inteligente (filtrado por tema: CPF, IRPF, Certidões etc.)       | RF        | NÃO IMPLEMENTADO | [INT24](https://requisitos-de-software.github.io/2025.1-ReceitaFederal/elicitacao/introspeccao/)     |- |
| RF27 | Integração com calendário do dispositivo para lembretes de obrigações fiscais             | RF        | NÃO IMPLEMENTADO | [INT25](https://requisitos-de-software.github.io/2025.1-ReceitaFederal/elicitacao/introspeccao/)     |- |
| RF28 | Consulta de inscrição no CNPJ                                       | RF        | IMPLEMENTADO |[INT26](https://requisitos-de-software.github.io/2025.1-ReceitaFederal/elicitacao/introspeccao/)     |   - |
| RF29 | Consulta de tabelas CNAE, NCM e unidades da Receita Federal         | RF        | IMPLEMENTADO |[INT27](https://requisitos-de-software.github.io/2025.1-ReceitaFederal/elicitacao/introspeccao/)    |    - |  
| RF30 | Acesso à Caixa Postal para mensagens oficiais da Receita Federal    | RF        | IMPLEMENTADO | [INT28](https://requisitos-de-software.github.io/2025.1-ReceitaFederal/elicitacao/introspeccao/)    |   - |
| RF31 | Visualização de notícias e vídeos institucionais da Receita Federal | RF        | IMPLEMENTADO | [INT29](https://requisitos-de-software.github.io/2025.1-ReceitaFederal/elicitacao/introspeccao/)    |  - |
| RF32 | Consultar débitos pendentes (DARFs) | RF        | IMPLEMENTADO | [ST04](https://requisitos-de-software.github.io/2025.1-ReceitaFederal/elicitacao/storytelling/)    |  - |
| RF33 | Pagamento do DARF com cartão de crédito | RF        | IMPLEMENTADO | [ST05](https://requisitos-de-software.github.io/2025.1-ReceitaFederal/elicitacao/storytelling/)    |  - |
| RF34 | Emitir comprovante de CPF em PDF | RF        | IMPLEMENTADO | [ST07](https://requisitos-de-software.github.io/2025.1-ReceitaFederal/elicitacao/storytelling/)    |  - |

<font size="3"><p style="text-align: center">Fonte: [José Eduardo](https://github.com/jevprado), [Thales Germano](https://github.com/thalesgvl) e [Marco Marques](https://github.com/marcomarquesdc), 2025.</p></font>

### Tabela 02 - Requisitos Não-Funcionais

<p style="text-align: center"><b>Tabela 2</b> - Tabela de requisitos não funcionais elicitados </p>

| ID   | Descrição                                                                                  | Categoria | Status da implemntação           | Fonte | Validada | 
| ---- | ------------------------------------------------------------------------------------------ | --------- | ---------------- | ----- |----- |
| RNF1 | Acessibilidade (chatbot, imagens, vídeos) — melhorias no chatbot                 | RNF       | NÃO IMPLEMENTADO | [ADC13](https://requisitos-de-software.github.io/2025.1-ReceitaFederal/elicitacao/analisededocumentos/)     |-|
| RNF2 | Conteúdo educativo para iniciantes                                                         | RNF       | NÃO IMPLEMENTADO | [ADC14](https://requisitos-de-software.github.io/2025.1-ReceitaFederal/elicitacao/analisededocumentos/), [ST08](https://requisitos-de-software.github.io/2025.1-ReceitaFederal/elicitacao/storytelling/)     |-|
| RNF3 | Testes de desempenho para suportar alta demanda de usuários simultâneos                    | RNF       | IMPLEMENTADO     | [ADC15](https://requisitos-de-software.github.io/2025.1-ReceitaFederal/elicitacao/analisededocumentos/)     |-|
| RNF4 | Proteção de dados pessoais conforme a LGPD                                                 | RNF       | IMPLEMENTADO     | [ADC17](https://requisitos-de-software.github.io/2025.1-ReceitaFederal/elicitacao/analisededocumentos/)     |-|
| RNF5 | Interface responsiva e acessível                                                           | RNF       | IMPLEMENTADO     | [ADC18](https://requisitos-de-software.github.io/2025.1-ReceitaFederal/elicitacao/analisededocumentos/)     |-|
| RNF6 | Interface com a possibilidade de uso do modo escuro                                        | RNF       | NÃO IMPLEMENTADO |[ADC23](https://requisitos-de-software.github.io/2025.1-ReceitaFederal/elicitacao/analisededocumentos/), [INT17](https://requisitos-de-software.github.io/2025.1-ReceitaFederal/elicitacao/introspeccao/), [ST11](https://requisitos-de-software.github.io/2025.1-ReceitaFederal/elicitacao/storytelling/)     |-|
| RNF7 | Testes de segurança para garantir a integridade dos dados e autenticação segura            | RNF       | IMPLEMENTADO     | [ADC19](https://requisitos-de-software.github.io/2025.1-ReceitaFederal/elicitacao/analisededocumentos/)     |-|
| RNF8 | Compatível com Android 8+ e iOS 14+                                                        | RNF       | IMPLEMENTADO     | [ADC20](https://requisitos-de-software.github.io/2025.1-ReceitaFederal/elicitacao/analisededocumentos/)    |-|
| RNF9 | Testes de usabilidade semestrais com público 60+                                           | RNF       | NÃO IMPLEMENTADO     | [ADC21](https://requisitos-de-software.github.io/2025.1-ReceitaFederal/elicitacao/analisededocumentos/)    |-|
| RNF10| O aplicativo deve ter tempo de resposta inferior a 3 segundos para ações comuns            | RNF       | IMPLEMENTADO     | [INT9](https://requisitos-de-software.github.io/2025.1-ReceitaFederal/elicitacao/introspeccao/)     |-|
| RNF11| O aplicativo deve funcionar em smartphones com telas de 4.5" a 7" sem perda de usabilidade | RNF       | IMPLEMENTADO     | [INT10](https://requisitos-de-software.github.io/2025.1-ReceitaFederal/elicitacao/introspeccao/)     |-|
| RNF12 | Linguagem da interface deve seguir padrão A2 do CEFR, evitando jargões técnicos            | RNF       | IMPLEMENTADO     | [ADC25](https://requisitos-de-software.github.io/2025.1-ReceitaFederal/elicitacao/analisededocumentos/)    |-|
| RNF13| O app deve suportar modo de operação em baixa conectividade, com cache de dados essenciais | RNF       | NÃO IMPLEMENTADO | [INT11](https://requisitos-de-software.github.io/2025.1-ReceitaFederal/elicitacao/introspeccao/)    |-|
| RNF14 | Atualizações do app não devem causar perda de dados armazenados localmente                 | RNF       | IMPLEMENTADO     | [INT12](https://requisitos-de-software.github.io/2025.1-ReceitaFederal/elicitacao/introspeccao/)    |-|
| RNF15 | Tempo de inatividade programada máximo de 2h por mês, com aviso prévo                     | RNF       | IMPLEMENTADO     | [INT13](https://requisitos-de-software.github.io/2025.1-ReceitaFederal/elicitacao/introspeccao/)     |-|
| RNF16 | Tempo de carregamento inicial do app não deve ultrapassar 5 segundos em conexão móvel      | RNF       | IMPLEMENTADO     | [ADC24](https://requisitos-de-software.github.io/2025.1-ReceitaFederal/elicitacao/analisededocumentos/)    |-|
| RNF17 | Suporte a leitores de tela (TalkBack, VoiceOver) em todas as funcionalidades               | RNF       | IMPLEMENTADO     | [INT14](https://requisitos-de-software.github.io/2025.1-ReceitaFederal/elicitacao/introspeccao/)  [ADC22](https://requisitos-de-software.github.io/2025.1-ReceitaFederal/elicitacao/analisededocumentos/)  |-|
|RNF18 | Armazenamento anônimo de logs de erro respeitando a LGPD                                   | RNF       | IMPLEMENTADO     | [INT15](https://requisitos-de-software.github.io/2025.1-ReceitaFederal/elicitacao/introspeccao/)     |-|
| RNF19 | Versão mínima em HTML5 responsiva para acesso via navegador em caso de falha do app        | RNF       | NÃO IMPLEMENTADO | [INT16](https://requisitos-de-software.github.io/2025.1-ReceitaFederal/elicitacao/introspeccao/)     |-|
| RNF20 | Clareza na apresentação de dados fiscais        | RNF       | IMPLEMENTADO | [ST12](https://requisitos-de-software.github.io/2025.1-ReceitaFederal/elicitacao/storytelling/)     |-|
| RNF21 | Integração confiável com serviços externos (Gov.br, instituições financeiras)        | RNF       | IMPLEMENTADO | [ST13](https://requisitos-de-software.github.io/2025.1-ReceitaFederal/elicitacao/storytelling/)     |-|


<font size="3"><p style="text-align: center">Fonte: [José Eduardo](https://github.com/jevprado), [Thales Germano](https://github.com/thalesgvl), 2025.</p></font>


## Referências


> <a>1.</a> PRESSMAN, Roger S.; MAXIM, Bruce R. *Engenharia de Software*. McGraw-Hill, 2016.  
>
> <a>2.</a>REIS, Carla Silva dos et al. Técnicas de elicitação de requisitos. *Revista de Informática Teórica e Aplicada*, 2014 
>
> <a>3.</a>SOMMERVILLE, Ian. *Engenharia de Software*. Pearson, 2019.  
>


## Historico de versões

| Versão | Data       | Descrição                                      | Autor(es)                                      | Revisor(es)                                    |
| ------ | ---------- | ---------------------------------------------- | ---------------------------------------------- | ---------------------------------------------- |
| `1.0`   | 18/05/2025 | Criação do documento                           | [José Eduardo](https://github.com/jevprado)    | [Thales Germano](https://github.com/thalesgvl) |
| `2.0`   | 28/05/2025 | Corrigindo tabela de requisitos elicitados     | [José Eduardo](https://github.com/jevprado)    | [Diassis](https://github.com/Diaxiz)           |
| `2.1`   | 29/05/2025 | Corrigindo e adicionando requisitos elicitados | [Thales Germano](https://github.com/thalesgvl) | [José Eduardo](https://github.com/jevprado)    |
| `2.2`   | 29/05/2025 | Corrigindo código dos requisitos               | [José Eduardo](https://github.com/jevprado)    | [Thales Germano](https://github.com/thalesgvl) |
| `2.3`   | 30/05/2025 | Add req elicitados MM              | [Marco Marques](https://github.com/marcomarquesdc)    | [José Eduardo](https://github.com/jevprado)         |
| `2.4`   | 30/05/2025 | Adicionando Hyperlink nos requisitos elicitados | [José Eduardo](https://github.com/jevprado)    | [Thales Germano](https://github.com/thalesgvl) |
| `2.5`   | 04/06/2025 | Adicionando Hyperlink nos requisitos elicitados no Storytelling | [José Eduardo](https://github.com/jevprado)    | [Diassis](https://github.com/Diaxiz) |

