# B2 · 1ª SÉRIE · TÉCNICAS DE PROGRAMAÇÃO E ALGORITMOS (parte 2 de 2) — ITA NEGRO

- Continuação do I.17 (plano 612). Carga neste bimestre: ≈60 h-a (3–4 aulas/semana × 16 semanas)
- Habilidades do plano concluídas aqui: 2.1 programação estruturada (decisão múltipla, laços) ·
  2.2 depurar e versionar programas em IDE
- Bases tecnológicas deste bimestre: decisão múltipla, iteração/laços, IDE (breakpoints, call
  stack, variáveis em tempo de execução), programação modular (sub-rotinas, funções, escopo),
  vetores e matrizes, versionamento (repo local/remoto, commit, checkin/checkout), práticas
  (estilo, programação em par, testes unitários)
- Papel no ITA NEGRO: os 3 módulos-núcleo do B1 viram uma BIBLIOTECA VERSIONADA em repositório
  remoto, com testes — a primeira "integração contínua" da casa.
- Rodízio de papéis TBL: novos PO/DEV/QA/SEC (quem foi SEC no B1 vai de DEV, etc.).
- Formato aula-âmbar: 15 teoria + 30 prática + 5 retrospectiva.

## Sequência didática

| Sem | Base tecnológica (plano) | Prática guiada (30 min) | Evidência |
|-----|--------------------------|--------------------------|-----------|
| 1 | Reativação + decisão múltipla (switch/case) | Módulo 3 refatorado: menu de níveis de alerta | Módulo 3 v2 |
| 2 | Laços (while) | Sensor lendo até condição: loop de monitoramento | Loop de sensores |
| 3 | Laços (for) e iteração | Relatório de leituras: somar, média, máximo | Função de relatório |
| 4 | Validação com laço + decisão | Entrada robusta: não aceita dado inválido (menu repete) | Validador reutilizável |
| 5 | IDE: navegação, autocomplete, marcas de erro | Tour guiada na IDE; corrigir projeto com 10 erros plantados | Print antes/depois |
| 6 | IDE: breakpoints e execução passo a passo | Caçar bug de laço infinito com breakpoint | Checkpoint 1 (prático) |
| 7 | IDE: variáveis em tempo de execução, call stack | Rastrear chamadas do módulo de alerta | Ficha de depuração |
| 8 | Modularização: sub-rotinas e funções | Extrair funções dos módulos 1–3 (uma responsabilidade cada) | Biblioteca v0.1 |
| 9 | Argumentos e escopo de identificadores | Variável global vs local: caso do "dossiê vazado" | Exercício de escopo |
| 10 | Vetores | Histórico de leituras em vetor; buscar mínimo/máximo | Módulo com vetor |
| 11 | Matrizes | Grade da casa: matriz de sensores por cômodo | Mapa de sensores |
| 12 | Versionamento: conceitos, repo local | `init`, `add`, `commit`, `log` — história da biblioteca | Repo local versionado |
| 13 | Versionamento: repo remoto, checkin/checkout | Push/pull no repositório remoto; primeiro conflito resolvido | Repo remoto ativo |
| 14 | Testes unitários + programação em par | Escrever 3 testes por módulo em pares; estilo e legibilidade | Suíte de testes verde |
| 15 | MARCO B2: release 0.1 da biblioteca | Banca: cada equipe versiona, testa e demonstra os módulos | Release 0.1 taggeada |
| 16 | Defesa + autoavaliação | Portfólio: evolução B1→B2 dos módulos; reflexão por papel | Portfólio + menção |

## Avaliação (formato plano 612)
- Formativa: retrospectivas + revisão de código em par (um revisa o do outro por semana).
- Cumulativa: checkpoint (sem. 6) + marco release 0.1 (sem. 15).
- Autoavaliação: portfólio comparativo B1→B2. Recuperação contínua: tutores refazem checkpoint
  com quem ficou na base durante as sem. 13–14, antes do fechamento.

## Entrega para o próximo componente
Biblioteca 0.1 versionada (repo remoto) → será consumida pelo Banco de Dados I (B4) e citada
no TCC. O repositório remoto criado aqui é o mesmo da casa até a 3ª série.
