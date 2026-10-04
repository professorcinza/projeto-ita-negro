# B1 · 3ª SÉRIE · PROGRAMAÇÃO WEB III (parte 1 de 2) — ITA NEGRO

- Componente III.11 (plano 612) · Função: Desenvolvimento de sistemas e serviços para Web ·
  Execução · Carga anual: 80 h-a (≈40 neste bimestre, 2–3 aulas/semana)
- Habilidades trabalhadas no B1: 1.1 framework de desenvolvimento Web (início)
- Bases deste bimestre: padrão MVC (classes Model/View/Controller); framework MVC (roteamento,
  templates, scaffolding); integração com serviços Web (requisições assíncronas, AJAX)
- Papel no ITA NEGRO: MIGRAÇÃO do web v0.8 artesanal (2ª série) para um framework MVC —
  já incorporando as correções do pentest (B1-3a Segurança). Stack a critério do professor
  (sugestão: Laravel, Django ou Express — todos livres).
- Formato aula-âmbar: 15 teoria + 30 prática + 5 retrospectiva.

## Sequência didática

| Sem | Base tecnológica (plano) | Prática guiada (30 min) | Evidência |
|-----|--------------------------|--------------------------|-----------|
| 1 | Diagnóstica + por que framework | Listar o que o web v0.8 faz "na mão" que o framework dá pronto | Ficha diagnóstica |
| 2 | Instalação e estrutura do framework | Projeto novo rodando; tour nos diretórios | App base |
| 3 | MVC no framework: rotas | Rota → controller → view "Olá casa" | Primeira rota |
| 4 | MVC: controllers e views | Migrar a home do v0.8 | Home no framework |
| 5 | MVC: models e ORM (mapeamento objeto-relacional) | Mapear as tabelas do schema v1.2 como models | Checkpoint 1: models |
| 6 | Migrations e versionamento do banco | Schema do banco sob controle de versão | Migrations no repo |
| 7 | Templates e layouts | Layout único com o manual de marca | Layout da casa |
| 8 | Autenticação do framework | Login/logout com o mecanismo nativo (hash + sessão segura) | Checkpoint 2: auth |
| 9 | CRUD scaffolding | CRUD de membros gerado e ajustado | CRUD no framework |
| 10 | Requisições assíncronas e AJAX | Lista atualiza sem recarregar página | Ajax básico |
| 11 | Validação de formulários no servidor | Regras do produto (senha forte, campos obrigatórios) | Validações |
| 12 | Aplicar correções do pentest (1/2) | Corrigir falhas de sessão/validação do relatório B1 | Correções 1/2 |
| 13 | Aplicar correções do pentest (2/2) + revisão cruzada | Corrigir falhas restantes; code review entre equipes | Correções 2/2 |
| 14 | REVISÃO + recuperação contínua | Refazer CRUD/model com tutoria | Pendências zeradas |
| 15 | MARCO B1: WEB v0.9 | Banca: mesmo produto, agora em framework, com falhas do pentest corrigidas | Web v0.9 taggeada |
| 16 | Defesa + autoavaliação | Portfólio: comparativo v0.8 artesanal × v0.9 framework | Portfólio + menção |

## Avaliação (formato plano 612)
- Formativa: retrospectivas + code review cruzado.
- Cumulativa: checkpoints (sem. 5 e 8) + marco (sem. 15).
- Autoavaliação: portfólio. Recuperação contínua: sem. 14.

## Continuação
B2 conclui o componente: APIs REST/JSON, consumo de APIs públicas, XML/JSON, segurança e
internacionalização → web v1.0-beta com API própria que o Mobile II (B3) vai consumir.

## TCC neste bimestre (PTCC — 1º semestre, ≈30 h-a)
Semanas 9–16: pesquisa e compilação de dados (referencial teórico), definição de termos
técnicos, escolha dos procedimentos metodológicos e cronograma do TCC.
