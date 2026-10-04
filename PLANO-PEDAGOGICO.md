# PROJETO ITA NEGRO
## Otimização das aulas do Técnico em Desenvolvimento de Sistemas (ETEC — Plano de Curso 612, Período Integral)

Norte: Plano de Curso 612 MTec-PI (atualizado 23-02-2023), Centro Paula Souza.
Fundamentos usados: desenvolvimento por competências (BNCC 10 competências gerais + Eixo
Estruturante), metodologias ativas (ABP, PBL, TBL, STEM/STEAM, prototipagem), trabalho
interdisciplinar por área, avaliação diagnóstica/formativa/cumulativa/somativa com recuperação
contínua, e TCC como produto final (Portarias CETEC 354/2015 e 2429/2022).

---

## 1. Conceito do projeto

ITA NEGRO ("pedra preta" em tupi) = a turma opera como uma casa de software real ao longo das
3 séries, produzindo um produto único e crescente. Cada série entrega uma versão:

- 1ª série → FUNDAÇÃO: identidade, site, lógica, dados. Produto v0.1 (estático + repositório).
- 2ª série → SISTEMA: desktop OO, web com banco, mobile v1. Produto v0.9 (MVP multiplataforma).
- 3ª série → ENDURECIMENTO: framework MVC, mobile II, segurança ofensiva/defensiva, testes,
  embarcados. Produto v1.0 + TCC.

Nível sênior: o aluno não é espectador — rotaciona por papéis de trabalho (dev, QA, segurança,
UX, product owner) a cada bimestre, com trilha de mestria (todos chegam ao topo com evidência).

O tema do produto é decidido pela turma no B1-1ª (canvas coletivo), mas o esqueleto técnico é fixo.
Sugestão de identidade que amarra os 3 anos: um sistema de comunicação/monitoramento
comunitário (app + web + sensor) — conversa com segurança, redes e embarcados da 3ª série.

---

## 2. Mapa por série (componentes do Plano 612 e o que o ITA NEGRO faz em cada um)

### 1ª SÉRIE — FUNDAÇÃO (520 h-a técnicas)

| Bim | Componente (h-a) | No ITA NEGRO | Habilidade (plano) | Produto/evidência |
|-----|------------------|--------------|--------------------|-------------------|
| B1 | Fundamentos da Informática (80) | Ambiente da casa: Linux, VM, CLI, git inicial | 1.2, 2.1 | Máquina pronta + repo `ita-negro` criado |
| B1 | Design Digital (80) | Identidade visual: logo, paleta, tipografia | 1.1 | Manual de marca v1 |
| B1–B2 | Técnicas de Programação e Algoritmos (120) | Lógica: fluxograma → código dos módulos-núcleo | 1.1, 2.1, 2.2 | Módulos lógicos testados em mesa + IDE |
| B2 | Programação Web I (80) | Site institucional do produto (HTML5/CSS/JS, responsivo) | 1.1–1.3 | Site publicado (gh-pages/000webhost) |
| B3 | Análise e Projeto de Sistemas (80) | Requisitos do produto: entrevista, user story, cascata vs ágil | 1.1, 1.2, 2.2 | Documento de requisitos + escolha do método |
| B4 | Banco de Dados I (80) | Modelo conceitual/lógico do produto, 1FN–3FN, DDL inicial | 1.1–1.4 | DER + dicionário de dados + SQL Server |

Interdisciplinar (matriz B1: 680 h-a BNCC): site do PW I usa tema de Química/Biologia/História
(o próprio plano sugere coleções interativas e timelines) — o professor de Web alinha com a BNCC.

### 2ª SÉRIE — SISTEMA (400 h-a técnicas)

| Bim | Componente (h-a) | No ITA NEGRO | Habilidade (plano) | Produto/evidência |
|-----|------------------|--------------|--------------------|-------------------|
| B1 | Ética e Cidadania Organizacional (40) | Código de conduta da casa; LGPD do produto | 1.1–3.1 | Código de ética + política de dados |
| B1–B2 | Desenvolvimento de Sistemas (120) | Módulo desktop OO (MVC, DAO, CRUD, GUI) | 1.1–1.5 | App desktop v0.5 conectado ao BD |
| B2–B3 | Programação Web II (80) | Web dinâmica: sessão, formulários, CRUD parametrizado anti-SQLi | 1.1–1.3 | Web v0.8 com login e persistência |
| B3 | Banco de Dados II (80) | DDL/DML/DQL avançado, views, triggers, índices, relatórios | 1.1, 2.1, 2.2 | Relatórios analíticos do produto |
| B4 | Programação de Aplicativos Mobile I (80) | App v1 em blocos: telas, galeria, GPS, notificação | 1.1–1.3 | APK v1 instalado nos celulares da turma |

Marco do fim da 2ª série: MEGASSESSÃO — a turma demonstra o MVP em 3 plataformas
(desktop, web, mobile) para banca interna (professores da área).

### 3ª SÉRIE — ENDURECIMENTO (520 h-a técnicas)

| Bim | Componente (h-a) | No ITA NEGRO | Habilidade (plano) | Produto/evidência |
|-----|------------------|--------------|--------------------|-------------------|
| B1 | Internet, Protocolos e Segurança (80) | Modelos OSI/TCP-IP; ameaças; pentest do próprio produto: footprint, varredura, SQLi, DoS, engenharia social; criptografia, firewall | 1.1, 1.2, 2.1–2.3 | Relatório de pentest + correções |
| B1–B2 | Programação Web III (80) | Migração para framework MVC: ORM, rotas, templates, auth, APIs REST/JSON | 1.1, 2.1, 2.2 | Web v0.9 em framework + API pública |
| B2 | Qualidade e Teste de Software (80) | Plano e casos de teste, TDD, níveis unidade→sistema, MPS.BR/CMMI | 1.1, 1.2 | Suíte de testes verde no CI |
| B3 | Programação de Aplicativos Mobile II (80) | App consome a API própria: mapas, sensores, notificações, permissões | 1.1–1.4 | App v1.0 conectado ao backend real |
| B3 | Sistemas Embarcados (80) | Nó sensor do produto (Arduino): leitura analógica/digital, serial, envio de dados | 1.1, 2.1, 2.2 | Protoboard + firmware v1 enviando telemetria |
| B1–B4 | TCC — PTCC + Desenvolvimento (120) | O próprio ITA NEGRO vira o TCC: canvas, hipóteses, UML (caso de uso + classe), cronograma, relatórios | EMIFCG11/12, EMIFFTP11/12, 1.1–5.2 | TCC escrito + banca final |

Marco final: BANCA ITA NEGRO — produto v1.0 endurecido (pentest corrigido + testes + sensor +
3 plataformas) defendido como TCC. Tipologia admitida pelo plano: software/aplicativo +
protótipo com manual técnico (Portaria 354/2015).

---

## 3. Otimização didática (o que muda na aula)

1. Aula-âmbar (50 min = 15 teoria + 30 prática guiada + 5 retrospectiva). Teoria nunca passa de
   1/3; o plano manda prever prática em todos os componentes.
2. Mesa de trabalho (TBL): equipes de 4 com papéis rotativos por bimestre — PO, DEV, QA, SEC.
   Trocar de papel é requisito de mestria.
3. Trilha de mestria por competência: cada aluno comprova a habilidade do plano em 3 níveis
   (base → aplicado → ensino-outro). "Sênior" = só sai da trilha quem ensinou o colega.
4. Revisão por pares obrigatória: todo push passa por 1 revisor (pull request no repo da turma);
   o versionamento já é habilidade 2.2 de Técnicas de Programação.
5. Recuperação contínua embutida: a cada marco bimestral, quem não atinge o nível base refaz
   com tutoria do nível sênior — antes da soma bimestral, não depois (plano 4.6/avaliação).
6. Segurança desde a 1ª série: sanitização e versionamento são "higiene" desde o início; a 3ª
   série apenas formaliza (pentest, teste de intrusão) — conteúdo que já está nas bases
   tecnológicas do componente III.13.
7. Interdisciplinaridade real: 1 entrega por semestre usa conteúdo da BNCC (timeline, wiki,
   coleção interativa — sugestões literais do plano em I.13/I.15).

## 4. Avaliação (formato do plano 612)

- Diagnóstica: B1 de cada série — sondagem de trilha (onde cada aluno entra).
- Formativa: retrospectivas quinzenais + feedback nos PRs (observação direta do desempenho).
- Cumulativa: marcos bimestrais da tabela (entrega + defesa oral de 5 min por papel).
- Somativa: megasessão (2ª série) e banca TCC (3ª série).
- Autoavaliação: portfólio individual no repo (papel exercido, evidências, reflexão) por bimestre.

## 5. Checklist de implementação

- [ ] Divisão de classes em turmas (laboratório) — prevista no plano, item 4.9, para todos os
      componentes técnicos.
- [ ] Ambientes: laboratório com Linux/VM (B1-1ª), SQL Server (BD), IDE mobile em blocos
      (2ª), framework MVC + Arduino/protoboard (3ª).
- [ ] Repositório da turma + individual (GitHub ou GitLab da escola) no primeiro bimestre.
- [ ] Calendário de marcos publicado no primeiro dia de cada bimestre (transparência avaliativa).
- [ ] TCC: registrar aderência à Portaria 2429/2022 desde o 1º semestre da 3ª série.

## Fontes

- Plano de Curso 612 — Técnico em Desenvolvimento de Sistemas, Período Integral, CPS
  (atualizado 23-02-2023): matriz (p. 27–29), componentes I.13–I.18 (p. 66–76),
  II.14–II.18 (p. 116–125), III.11–III.16 (p. 160–173), fundamentos pedagógicos e avaliação
  (p. 174–176), TCC (p. 166–170, 186–187).
- PDF local: ~/.hermes/cache/scratch/etec-ds-PI.pdf
