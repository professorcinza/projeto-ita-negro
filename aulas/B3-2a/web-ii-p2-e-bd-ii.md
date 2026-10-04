# B3 · 2ª SÉRIE · PROGRAMAÇÃO WEB II (parte 2 de 2) + BANCO DE DADOS II — ITA NEGRO

Dois componentes correm em paralelo neste bimestre (cargas semanais somam ≈5 aulas):
- **Web II parte 2** (II.14, conclusão): habilidade 1.2 — banco de dados relacionais para
  persistência. Bases: conexões, execução de comandos SQL, CRUD, consultas parametrizadas,
  sanitização e prevenção de SQL Injection.
- **Banco de Dados II** (II.15, 80 h-a anual ≈40 no bimestre, 2–3 aulas/semana): habilidades
  1.1 usar SGBD · 2.1 SQL com melhor desempenho · 2.2 relatórios analíticos. Bases: DDL/DML/DQL,
  blocos SQL, exceções, funções, gatilhos, visões, índices, merge e permissões.

- Papel no ITA NEGRO: WEB v0.8 com dados reais (Web II) alimentada por um banco TUNADO
  (BD II) — views, triggers e índices do produto. É o bimestre da INTEGRAÇÃO.
- Formato aula-âmbar: 15 teoria + 30 prática + 5 retrospectiva.

## Trilha A — Web II parte 2 (2–3 aulas/semana)

| Sem | Base tecnológica (plano) | Prática guiada | Evidência |
|-----|--------------------------|----------------|-----------|
| 1 | Conexão servidor↔banco (driver) | Conectar o portal ao SQL Server da casa | Conexão OK |
| 2 | Execução de comandos SQL do app | Listar membros do banco na página | Lista real |
| 3 | CRUD web: create/read | Cadastrar membro pelo navegador | CRUD parte 1 |
| 4 | CRUD web: update/delete | Editar/excluir com confirmação | CRUD completo |
| 5 | CHECKPOINT: consultas parametrizadas | Refazer tudo SEM concatenação de string | Checkpoint 1 |
| 6 | Sanitização de entrada | Validar/limpar todo input (função única da casa) | Sanitizador |
| 7 | SQL Injection: ataque controlado | `' OR 1=1 --` no login da equipe parceira (combinado) | Relatório do ataque |
| 8 | Correção + prepared statements | Fechar as falhas achadas na semana 7 | Checkpoint 2: web blindada |
| 9 | Organização em camadas do web app | Separar view/lógica/acesso a dados | Estrutura em camadas |
| 10 | Mensagens e estados (erro/sucesso) | Feedback ao usuário em toda operação | UX de operações |
| 11 | Regras de negócio no servidor | Senha forte obrigatória; papel (admin/membro) | Regras implementadas |
| 12 | Revisão cruzada entre equipes | Code review com checklist de segurança | Relatório de review |
| 13 | Estabilização + deploy final | Corrigir bugs do review; publicar | WEB v0.8 no ar |
| 14 | RECAP + recuperação contínua | Refazer CRUD com tutoria | Pendências zeradas |
| 15 | MARCO: WEB v0.8 | Banca: cadastrar/listar/editar/excluir em dados reais | Web v0.8 taggeada |
| 16 | Defesa + autoavaliação | Portfólio: comparativo desktop×web do mesmo CRUD | Portfólio + menção |

## Trilha B — Banco de Dados II (2–3 aulas/semana)

| Sem | Base tecnológica (plano) | Prática guiada | Evidência |
|-----|--------------------------|----------------|-----------|
| 1 | Criação/exclusão de banco; variáveis | Recriar o schema v1.0 em script versionado | schema.sql no repo |
| 2 | DDL avançado (ALTER, constraints) | Evoluir schema sem perder dados | schema v1.1 |
| 3 | DML em lote (INSERT/UPDATE/DELETE) | Popular banco de testes com dados da casa | Seed de dados |
| 4 | DQL: SELECT avançado (JOIN, GROUP BY) | Consultas que o produto precisa | Catálogo de consultas |
| 5 | CHECKPOINT: consultas do produto | 10 consultas reais do backlog | Checkpoint 1 |
| 6 | Subconsultas e blocos SQL | "Membros sem alerta no mês" em bloco SQL | Bloco SQL |
| 7 | Tratamento de exceções | O que fazer quando dado não existe/está errado | Rotinas de erro |
| 8 | Funções no banco | Função `nivel_alerta(membro)` usada pelo web | Checkpoint 2: funções |
| 9 | Gatilhos (triggers) | Trigger: log automático de toda exclusão | Trigger de auditoria |
| 10 | Visões (views) | View "painel da casa" consumida pelo web | View publicada |
| 11 | Índices e desempenho | Medir consulta lenta; criar índice; medir de novo | Antes/depois |
| 12 | Merge e permissões | Upsert de leituras; usuários do banco com papel mínimo | Permissões aplicadas |
| 13 | Relatórios analíticos | Relatório mensal por cômodo (para o TCC) | Relatório analítico |
| 14 | RECAP + recuperação contínua | Refazer consultas com tutoria | Pendências zeradas |
| 15 | MARCO: BANCO v1.2 | Banca: schema + views + triggers + relatório | Banco v1.2 taggeado |
| 16 | Defesa + autoavaliação | Portfólio: print do plano de execução e do relatório | Portfólio + menção |

## Avaliação (formato plano 612)
- Formativa: retrospectivas + revisão cruzada (código web) e troca de DER (banco).
- Cumulativa: checkpoints das duas trilhas + marcos da semana 15 (web v0.8 E banco v1.2).
- Autoavaliação: portfólio integrado (o que o banco entregou para o web).
- Recuperação contínua: sem. 14 em ambas as trilhas, antes do fechamento.

## Entrega para o próximo bimestre
Web v0.8 + banco v1.2 → Mobile I (B4) constrói o app que consome esse mesmo back-end;
a view "painel da casa" vira a tela inicial do app.
