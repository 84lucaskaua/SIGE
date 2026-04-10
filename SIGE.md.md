**SENAC-DF**

|  |
| --- |
|  |

**SIGE**

**Sistema de Gerenciamento de Estoque**

*Documento de Projeto*

|  |
| --- |
| **Integrantes da Equipe** |
| Natanael |
| Lucas |
| Angel |
| Manuella |

Versão: 1.0

Brasília – DF, 2026

# SUMÁRIO

[SUMÁRIO 1](#_Toc226726224)

[1. INTRODUÇÃO 1](#_Toc226726225)

[1.1 Contexto 1](#_Toc226726226)

[1.2 Objetivo do Documento 1](#_Toc226726227)

[1.3 Equipe 1](#_Toc226726228)

[2. DESCRIÇÃO DO SISTEMA 1](#_Toc226726229)

[3. OBJETIVO DO SISTEMA 1](#_Toc226726230)

[4. ESCOPO DO PROJETO 1](#_Toc226726231)

[4.1 Dentro do Escopo 1](#_Toc226726232)

[4.2 Fora do Escopo 1](#_Toc226726233)

[5. BRIEFING DO CLIENTE 1](#_Toc226726234)

[6. PROBLEMA QUE O SISTEMA RESOLVE 1](#_Toc226726235)

[7. USUÁRIOS DO SISTEMA 1](#_Toc226726236)

[8. FUNCIONALIDADES PRINCIPAIS 1](#_Toc226726237)

[9. REQUISITOS DO SISTEMA 1](#_Toc226726238)

[9.1 Requisitos Funcionais 1](#_Toc226726239)

[9.2 Requisitos Não Funcionais 1](#_Toc226726240)

[10. PROTÓTIPO 1](#_Toc226726241)

[11. ORGANIZAÇÃO DAS TAREFAS – TRELLO 1](#_Toc226726242)

# 1. INTRODUÇÃO

## 1.1 Contexto

Durante o desenvolvimento de um sistema é muito importante registrar as informações do projeto em um documento. Essa documentação ajuda a organizar as ideias da equipe, registrar as decisões tomadas e explicar como o sistema funciona.

O presente documento descreve o projeto SIGE – Sistema de Gerenciamento de Estoque, desenvolvido por estudantes do SENAC-DF como parte de atividade acadêmica de desenvolvimento de sistemas. O SIGE foi concebido para atender às necessidades de controle de estoque de almoxarifado em uma unidade de saúde.

## 1.2 Objetivo do Documento

Este documento tem como objetivo registrar e organizar todas as informações relevantes do projeto SIGE, incluindo a descrição do sistema, seus objetivos, escopo, usuários, funcionalidades e requisitos. Serve como referência central para a equipe de desenvolvimento e demais partes interessadas.

## 1.3 Equipe

O projeto SIGE é desenvolvido pela seguinte equipe de estudantes do SENAC-DF:

* Natanael
* Lucas
* Angel
* Manuella

# 2. DESCRIÇÃO DO SISTEMA

O SIGE é um sistema web desenvolvido para controle de estoque de almoxarifado em uma unidade de saúde. O sistema permite o gerenciamento eficiente de produtos, controlando entradas e saídas de materiais de forma organizada e segura.

A solução digital substitui processos manuais que estavam sujeitos a erros, perdas e dificuldades de rastreamento. Com o SIGE, a equipe administrativa passa a contar com uma ferramenta centralizada, de acesso controlado e com atualização em tempo real.

# 3. OBJETIVO DO SISTEMA

O principal objetivo do SIGE é organizar o controle de estoque, evitar perdas e garantir maior eficiência no gerenciamento dos materiais da unidade de saúde.

Para alcançar esse objetivo, o sistema busca:

* Centralizar todas as informações de estoque em um único ambiente digital;
* Registrar automaticamente entradas e saídas de produtos;
* Gerar relatórios gerenciais para apoio à tomada de decisão;
* Emitir alertas quando o estoque de um produto atingir nível mínimo;
* Garantir a rastreabilidade de todas as movimentações de materiais.

# 4. ESCOPO DO PROJETO

O SIGE será desenvolvido como uma aplicação web com funcionalidades de controle de estoque, autenticação de usuários e geração de relatórios.

## 4.1 Dentro do Escopo

* Módulo de cadastro e gestão de produtos;
* Registro de entradas e saídas de estoque;
* Dashboard com indicadores em tempo real;
* Sistema de autenticação com controle de acesso;
* Geração de requerimentos e relatórios;
* Histórico completo de movimentações;
* Sistema de alertas para estoque baixo.

## 4.2 Fora do Escopo

* Integração com sistemas externos de saúde (TISS, e-SUS, etc.);
* Aplicativo mobile nativo;
* Módulo financeiro ou de compras.

# 5. BRIEFING DO CLIENTE

A equipe administrativa da unidade de saúde necessita de um sistema que automatize o controle de entrada e saída de produtos, garantindo atualização em tempo real do estoque.

Atualmente o controle é realizado de forma manual, por meio de planilhas e registros em papel, o que gera inconsistências, retrabalho e dificuldades para localizar rapidamente informações sobre a disponibilidade de materiais.

O cliente espera uma solução de fácil uso, acessível pelo navegador, que permita que múltiplos usuários administrem o estoque de forma simultânea e segura.

# 6. PROBLEMA QUE O SISTEMA RESOLVE

O sistema resolve a dificuldade de controle manual de estoque, reduzindo erros e melhorando a organização dos materiais da unidade de saúde.

Os principais problemas identificados que o SIGE resolve são:

* Inconsistência nos registros manuais de entrada e saída de produtos;
* Dificuldade em saber, em tempo real, a quantidade disponível de um item;
* Ausência de histórico confiável de movimentações;
* Falta de alertas para produtos em quantidade crítica;
* Processo lento e propenso a erros para emissão de requerimentos.

# 7. USUÁRIOS DO SISTEMA

Todos os usuários atuam com perfil de administradores do sistema. São eles:

* Amanda
* Daniela
* Miguel

Como administradores, os usuários têm acesso completo a todas as funcionalidades do sistema, incluindo cadastro de produtos, registro de movimentações, geração de relatórios e visualização do dashboard.

# 8. FUNCIONALIDADES PRINCIPAIS

O SIGE disponibilizará as seguintes funcionalidades para seus usuários:

* Cadastro de produtos
* Entrada de produtos
* Saída de produtos
* Atualização automática do estoque
* Histórico de movimentação
* Geração de requerimentos
* Relatórios
* Dashboard
* Alertas de estoque baixo

# 9. REQUISITOS DO SISTEMA

## 9.1 Requisitos Funcionais

Os requisitos funcionais descrevem as funcionalidades que o sistema deve executar:

|  |  |
| --- | --- |
| **ID** | **Descrição** |
| **RF-01** | Registrar entrada de produtos no estoque com data, quantidade e responsável. |
| **RF-02** | Registrar saída de produtos do estoque com data, quantidade e responsável. |
| **RF-03** | Atualizar automaticamente o saldo em estoque após cada movimentação. |
| **RF-04** | Permitir login de usuários com autenticação por e-mail e senha. |
| **RF-05** | Gerar relatórios de movimentação por período, produto ou responsável. |
| **RF-06** | Gerar requerimentos de produtos para solicitação de reposição. |
| **RF-07** | Exibir dashboard com indicadores gerais do estoque em tempo real. |
| **RF-08** | Emitir alertas quando um produto atingir o nível mínimo de estoque. |
| **RF-09** | Manter histórico completo e imutável de todas as movimentações. |
| **RF-10** | Permitir cadastro, edição e exclusão de produtos no sistema. |

## 9.2 Requisitos Não Funcionais

Os requisitos não funcionais estabelecem critérios de qualidade e desempenho do sistema:

|  |  |
| --- | --- |
| **ID** | **Descrição** |
| **RNF-01** | O sistema deve responder a qualquer requisição em até 2 segundos. |
| **RNF-02** | Em caso de falha, a recuperação deve ocorrer em até 30 minutos. |
| **RNF-03** | Todos os dados devem ser armazenados com segurança e acesso restrito. |
| **RNF-04** | A interface deve ser intuitiva e de fácil uso, sem necessidade de treinamento extenso. |
| **RNF-05** | O sistema deve estar disponível continuamente (disponibilidade ≥ 99%). |
| **RNF-06** | O sistema deve ser acessível por qualquer navegador moderno. |
| **RNF-07** | As senhas dos usuários devem ser armazenadas com criptografia. |

# 10. PROTÓTIPO

O protótipo do sistema foi desenvolvido na ferramenta Figma e pode ser acessado pelo link abaixo. O protótipo apresenta as principais telas do SIGE, incluindo a tela de login, dashboard, cadastro de produtos, registro de movimentações e geração de relatórios.

<https://mouse-eel-19872096.figma.site/>

# 11. ORGANIZAÇÃO DAS TAREFAS – TRELLO

A organização e o acompanhamento das tarefas do projeto são gerenciados por meio do Trello. O quadro permite que a equipe visualize o status de cada atividade, distribua responsabilidades e acompanhe o progresso geral do projeto.

<https://trello.com/b/biof70eO/sige>

O quadro está organizado nas seguintes colunas:

* A Fazer – tarefas ainda não iniciadas;
* Em Andamento – tarefas que estão sendo executadas;
* Em Revisão – tarefas concluídas aguardando validação;
* Concluído – tarefas finalizadas e aprovadas.