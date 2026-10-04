# B2 · 3ª SÉRIE · PROGRAMAÇÃO WEB III (parte 2 de 2) + QUALIDADE E TESTE DE SOFTWARE — ITA NEGRO

Dois componentes em paralelo (cargas somam ≈5 aulas/semana):
- **Web III parte 2** (III.11, conclusão): habilidades 1.1 framework (conclusão) · 2.1 recursos
  de dispositivos móveis na integração de aplicativos · 2.2 construir aplicativos para internet.
  Bases: consumo de APIs públicas; criação/exposição de APIs com Web services; REST;
  WSDL/SOAP (conceito); XML e JSON; segurança e internacionalização.
- **Qualidade e Teste de Software** (III.15, 80 h-a no bimestre): habilidades 1.1 softwares de
  apoio ao teste · 1.2 verificar/validar correspondência especificação×produto. Bases:
  modelos de qualidade (CMMI, MPS.BR), testes funcionais/não funcionais, níveis
  (unidade/integração/sistema), plano e casos de teste, ferramentas, TDD.

- Papel no ITA NEGRO: API REST do produto (web v1.0-beta) protegida por SUÍTE DE TESTES —
  o app do B3 consome essa API; nada entra no ramo principal sem teste verde.
- Formato aula-âmbar: 15 teoria + 30 prática + 5 retrospectiva.

## Trilha A — Web III parte 2 (2–3 aulas/semana)

| Sem | Base tecnológica (plano) | Prática guiada | Evidência |
|-----|--------------------------|----------------|-----------|
| 1 | JSON e XML: padrões de transferência | Serializar dados do produto nos 2 formatos; comparar | Exemplo json/xml |
| 2 | REST: conceitos (recursos, verbos, sem estado) | Mapear os recursos da casa (membros, sensores, alertas) | Tabela recurso×verbo |
| 3 | Expor API REST do framework | GET /api/membros retornando JSON | Checkpoint 1: GET OK |
| 4 | API: POST/PUT/DELETE | CRUD completo via API | CRUD via API |
| 5 | Autenticação de API (token) | Token por equipe; rota protegida | Checkpoint 2: auth de API |
| 6 | Consumir API pública (ex.: IBGE/viacep) | Preencher endereço do membro via CEP | Integração externa |
| 7 | Documentação da API | Documentar endpoints (ex.: coleção compartilhável) | Doc da API |
| 8 | Internacionalização e segurança de API | Mensagens em 2 idiomas; rate limit básico | Checkpoint 3 |
| 9 | Web services com estado (SOAP/WSDL — conceito) | Comparar REST×SOAP num caso real | Quadro comparativo |
| 10 | Web mobile (PWA) | Instalar o painel como app na tela inicial | PWA instalável |
| 11 | Integração com app (ponte p/ Mobile II) | Contrato da API congelado e publicado | API v1 congelada |
| 12 | Revisão cruzada | Testar a API da equipe parceira com casos do QA | Relatório de review |
| 13 | Estabilização | Corrigir achados; publicar | WEB v1.0-beta |
| 14 | RECAP + recuperação contínua | Refazer endpoint com tutoria | Pendências zeradas |
| 15 | MARCO: API v1.0 | Banca: API documentada, autenticada e estável | API v1.0 taggeada |
| 16 | Defesa + autoavaliação | Portfólio: mapa de endpoints da casa | Portfólio + menção |

## Trilha B — Qualidade e Teste de Software (2–3 aulas/semana)

| Sem | Base tecnológica (plano) | Prática guiada | Evidência |
|-----|--------------------------|----------------|-----------|
| 1 | Diagnóstica + modelos de qualidade (CMMI, MPS.BR) | Onde a casa está num modelo de maturidade? | Ficha diagnóstica |
| 2 | Testes funcionais × não funcionais | Classificar 15 testes do produto | Matriz de testes |
| 3 | Níveis: unidade | Primeiro teste unitário do domínio (classes B1-2ª) | Teste unitário v1 |
| 4 | Níveis: unidade (casos-limite) | Cobrir entradas inválidas e limites | Checkpoint 1 |
| 5 | Níveis: integração | Testar DAO+banco (desktop) e controller+model (web) | Teste de integração |
| 6 | Plano de testes do produto | Plano formal: escopo, recursos, cronograma, riscos | Plano de testes v1 |
| 7 | Casos de teste (estrutura formal) | 10 casos: entrada, passos, esperado, obtido | Checkpoint 2: casos |
| 8 | Ferramentas de teste | Rodar suíte automatizada no framework (pytest/jest/phpunit) | Suíte verde |
| 9 | TDD: ciclo vermelho-verde-refatorar | Nova função da casa escrita ANTES pelo teste | Função TDD |
| 10 | TDD aplicado à API | Testar endpoint antes de implementá-lo | Checkpoint 3: TDD |
| 11 | Verificação × validação (especificação×produto) | Conferir API v1 contra requisitos v1.0 da 1ª série | Matriz rastreabilidade |
| 12 | Testes não funcionais básicos | Tempo de resposta da API; comportamento sob carga leve | Relatório de desempenho |
| 13 | CI simples: testes no repositório | Rodar suíte a cada push (hook/ação gratuita) | CI ativo |
| 14 | RECAP + recuperação contínua | Refazer plano/casos com tutoria | Pendências zeradas |
| 15 | MARCO: SUÍTE DE TESTES v1 | Banca: CI verde + relatório de cobertura resumido | Suíte v1 no repo |
| 16 | Defesa + autoavaliação | Portfólio: bug mais difícil que os testes pegaram | Portfólio + menção |

## Avaliação (formato plano 612)
- Formativa: retrospectivas + review cruzado (API testada pela equipe parceira).
- Cumulativa: checkpoints das trilhas + marcos sem. 15 (API v1.0 E suíte v1).
- Autoavaliação: portfólio. Recuperação contínua: sem. 14.

## TCC (Desenvolvimento — 2º semestre começa no B3)
Portfólio do TCC: no B2, cada equipe junta referencial teórico + metodologia (já pronto) e
começa os diagramas UML (caso de uso e classes) que serão entregues no B3 (habilidade 5.1).

## Entrega para o próximo bimestre
API v1.0 congelada + suíte de testes no CI → Mobile II (B3) consome a API; Embarcados (B3)
envia telemetria que entra nela; TCC usa a matriz de rastreabilidade como evidência.
