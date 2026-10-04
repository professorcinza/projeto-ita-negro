# B4 · 1ª SÉRIE · BANCO DE DADOS I — Plano de aulas ITA NEGRO

- Componente I.18 (plano 612) · Função: Planejamento do modelo conceitual de BD ·
  Classificação: Planejamento
- Carga: 80 h-a no bimestre (5 aulas/semana × 16 semanas)
- Competências/habilidades do plano: 1.1 levantar necessidades de informações ·
  1.2 normalizar tabelas · 1.3 associar tabelas · 1.4 aplicar SQL na construção de tabelas
- Bases tecnológicas: estrutura de BD, modelo conceitual, dicionário de dados, ferramenta CASE,
  modelo lógico (entidades, atributos, relacionamentos, grau, cardinalidade), restrições de
  integridade, autorrelacionamento, normalização (1–4, FNBC), especialização/generalização,
  domínio, projeto lógico, intro SQL Server + DDL
- Valores: organização, resolução de situações-problema, respeito às normas
- Papel no ITA NEGRO: modelar os DADOS DO PRODUTO a partir dos requisitos v1.0 (B3) — o DER
  e o dicionário desta série são usados, sem rework, pelo app desktop (2ª série), pelo web e
  pelo BD II. Schema do TCC começa aqui.
- Formato aula-âmbar: 15 teoria + 30 prática + 5 retrospectiva.

## Sequência didática

| Sem | Base tecnológica (plano) | Prática guiada (30 min) | Evidência |
|-----|--------------------------|--------------------------|-----------|
| 1 | Diagnóstica + evolução e estrutura de BD | Onde há dados na escola? (fichas, planilhas, sistemas) | Ficha diagnóstica |
| 2 | Dicionário de dados | Dicionário dos dados do produto (a partir dos RF/RNF do B3) | Dicionário v1 |
| 3 | Modelo conceitual: entidades | Extrair entidades dos requisitos (cadastro da casa) | Lista de entidades |
| 4 | Modelo conceitual: atributos e domínios | Atributos por entidade; tipos e domínios | DER parcial |
| 5 | Relacionamentos e grau (binário/ternário) | Relacionar entidades; achar 1 ternário no produto | DER v1 |
| 6 | Cardinalidade | Corrigir cardinalidades (1:1, 1:N, N:N) — caso do alarme | Checkpoint 1: DER v2 |
| 7 | Ferramenta CASE (brModelo/draw.io — livres) | Redesenhar o DER na ferramenta CASE | DER no CASE |
| 8 | Restrições de integridade (relacional/referencial) | O que acontece ao apagar um membro da casa? (casos) | Matriz de integridade |
| 9 | Autorrelacionamento (reflexivo/recursivo) | Membro↔membro (hierarquia de papéis da casa) | DER com autorrelação |
| 10 | Normalização: 1FN e 2FN | Suja→1FN→2FN (planilha ruim do "caderno da casa") | Checkpoint 2: exercício FN |
| 11 | Normalização: 3FN e FNBC | Levar o DER à 3FN; debater quando parar | DER normalizado |
| 12 | Especialização/generalização; 4FN (noção) | Pessoa→(Aluno, Professor) no modelo da casa | DER com generalização |
| 13 | Modelo lógico: regras de derivação | DER→modelo lógico (tabelas, chaves, FKs) | Modelo lógico v1 |
| 14 | SQL Server: interface + DDL inicial | `CREATE DATABASE/TABLE` do núcleo do produto no SSMS | Checkpoint 3: tabelas criadas |
| 15 | MARCO B4: schema v1.0 | Banca: DER + dicionário + DDL defendidos com os requisitos na mão | Schema v1.0 no repo |
| 16 | Defesa + autoavaliação | Portfólio: schema evoluído + reflexão; fechamento do ano | Portfólio + menção |

## Avaliação (formato plano 612)
- Diagnóstica: sem. 1 · Formativa: retrospectivas + revisão de DER entre equipes (troca semanal).
- Cumulativa: checkpoints (sem. 6, 10 e 14) + marco (sem. 15, schema v1.0).
- Autoavaliação: portfólio. Recuperação contínua: sem. 14, normalização refeita com tutoria
  antes do fechamento.

## Entrega para o próximo ano
Schema v1.0 (DER + dicionário + DDL) → implementado no SQL Server no Banco de Dados II e
consumido pelo desktop, web e mobile da 2ª série. É o primeiro artefato oficial do TCC.
