# B2 · 2ª SÉRIE · DESENVOLVIMENTO DE SISTEMAS (parte 2 de 2) — ITA NEGRO

- Continuação do II.16 (plano 612) · ≈60 h-a neste bimestre
- Habilidades concluídas aqui: 1.2 ambiente de desenvolvimento desktop · 1.3 conectar aplicações
  com banco de dados · 1.5 construir interface gráfica
- Bases deste bimestre: padrão MVC; GUI (caixas de diálogo, formulários, textos, campos, caixas
  de seleção); padrão DAO; conexão ao banco de dados; CRUD; consultas parametrizadas e
  prevenção de SQL Injection
- Papel no ITA NEGRO: APP DESKTOP v0.5 da casa — as classes do B1 ganham telas e falam com o
  schema v1.0 criado no B4 da 1ª série. Primeira integração OO + GUI + banco.
- Rodízio de papéis TBL: novos PO/DEV/QA/SEC.
- Formato aula-âmbar: 15 teoria + 30 prática + 5 retrospectiva.

## Sequência didática

| Sem | Base tecnológica (plano) | Prática guiada (30 min) | Evidência |
|-----|--------------------------|--------------------------|-----------|
| 1 | Reativação + padrão MVC (conceito e mapa) | Separar o que já existe em Model/View/Controller (papelimoto) | Mapa MVC da equipe |
| 2 | MVC: classes Model | Migrar o domínio B1 para o pacote model | model/ completo |
| 3 | GUI: janelas e caixas de diálogo | Primeira janela do app: "Painel da Casa" | Janela v1 |
| 4 | GUI: formulários, campos de texto, caixas de seleção | Formulário de cadastro de Membro | Formulário funcional |
| 5 | GUI: listas e tabelas | Tabela de membros com seleção | Checkpoint 1: tela de listagem |
| 6 | Conexão ao banco: driver e teste de conexão | Conectar ao SQL Server do schema v1.0 | Conexão OK (print) |
| 7 | Padrão DAO: conceito e interface | `MembroDAO` com assinaturas CRUD | Interface DAO |
| 8 | DAO: CREATE e READ | Cadastrar e listar membros de verdade (via banco) | CRUD parte 1 |
| 9 | DAO: UPDATE e DELETE | Editar e excluir com confirmação | Checkpoint 2: CRUD completo |
| 10 | Consultas parametrizadas | Buscar membros por filtro SEM concatenar string | DAO parametrizado |
| 11 | Prevenção de SQL Injection | Ataque controlado: tentar `' OR 1=1` no campo; depois corrigir | Registro do teste de invasão |
| 12 | MVC: Controller amarrando tudo | Botão→Controller→DAO→Model→View funcionando | Fluxo completo |
| 13 | Organização do projeto + revisão entre equipes | Code review cruzado com checklist (estilo, camadas, segurança) | Relatório de review |
| 14 | REVISÃO + recuperação contínua | Tutoria cruzada; refazer CRUD pendente | Pendências zeradas |
| 15 | MARCO B2: DESKTOP v0.5 | Banca: app instala, cadastra, lista, edita e exclui no banco real | Desktop v0.5 taggeada |
| 16 | Defesa + autoavaliação | Portfólio: diagrama de arquitetura do que foi construído | Portfólio + menção |

## Avaliação (formato plano 612)
- Formativa: retrospectivas + code review cruzado (checklist publicado).
- Cumulativa: checkpoints (sem. 5 e 9) + marco (sem. 15).
- Autoavaliação: portfólio com a arquitetura desenhada. Recuperação contínua: sem. 14.

## Entrega para o próximo componente
Desktop v0.5 (OO + MVC + DAO + banco) → Programação Web II (B2–B3) refaz o mesmo CRUD na
web, agora com sessão e formulários HTTP; o DAO parametrizado vira padrão obrigatório da casa.
