# B2 · 2ª SÉRIE · PROGRAMAÇÃO WEB II (parte 1 de 2) — ITA NEGRO

- Componente II.14 (plano 612) · Função: Desenvolvimento de sistemas para internet com banco
  de dados · Execução · Carga anual: 80 h-a (≈40 neste bimestre, 2–3 aulas/semana)
- Habilidades trabalhadas no B2: 1.1 codificar software em linguagem para Web (lado servidor) ·
  1.3 interface baseada em navegador
- Bases deste bimestre: scripts lado servidor; geração dinâmica de páginas; arquitetura em
  camadas (navegador, servidor web, aplicação); variáveis/tipos, decisão, laços, funções;
  comunicação navegador↔aplicação (URL, QueryString, POST/GET, formulários, sessões, cookies)
- Papel no ITA NEGRO: o site vitrine (Web I, 1ª série) ganha BACK-END — páginas dinâmicas e o
  painel de login da casa. Stack a critério do professor (sugestão: PHP ou Node.js, ambos
  gratuitos e rodando em hospedagem simples).
- Formato aula-âmbar: 15 teoria + 30 prática + 5 retrospectiva.

## Sequência didática

| Sem | Base tecnológica (plano) | Prática guiada (30 min) | Evidência |
|-----|--------------------------|--------------------------|-----------|
| 1 | Diagnóstica + arquitetura em camadas | Requisição na mão: browser→servidor→página (telnet/curl) | Ficha diagnóstica |
| 2 | Primeiro script lado servidor | Página que mostra a hora e o nome via QueryString | Primeiro .php/.js dinâmico |
| 3 | Variáveis, tipos e decisão no servidor | Roteador simples: URL decide qual página carregar | Mini-roteador |
| 4 | Laços e funções no servidor | Página que lista membros de um array | Lista dinâmica |
| 5 | Formulários: GET vs POST | Formulário de busca que processa no servidor | Checkpoint 1 |
| 6 | URL e QueryString na prática | Filtro de listagem por parâmetro de URL | Lista filtrável |
| 7 | Sessões | Login: guarda usuário na sessão | Login v1 |
| 8 | Cookies | "Lembrar-me" da casa (cookie com prazo) | Checkpoint 2: login completo |
| 9 | Geração dinâmica + template simples | Cabeçalho/rodapé incluídos em todas as páginas | Layout reaproveitado |
| 10 | CONTROLE: painel protegido | Área restrita: sem sessão, volta pro login | Painel protegido |
| 11 | Funções e organização do código | Separar auth.php (ou auth.js) do resto | Biblioteca de auth |
| 12 | Segurança básica de sessão | Logout que destrói tudo; regenerar id de sessão | Checklist de sessão |
| 13 | Integração com o repositório da casa | Deploy manual no servidor de testes da escola | App no servidor de testes |
| 14 | REVISÃO + recuperação contínua | Refazer login/painel com tutoria | Pendências zeradas |
| 15 | MARCO B2: portal com login | Banca: site dinâmico com área restrita funcionando | Portal v1 taggeado |
| 16 | Defesa + autoavaliação | Portfólio: fluxo desenhado do login (diagrama de sequência simples) | Portfólio + menção |

## Avaliação (formato plano 612)
- Formativa: retrospectivas + testes invasivos amigáveis entre equipes (tentam burlar o login
  da equipe parceira — combinado, com registro).
- Cumulativa: checkpoints (sem. 5 e 8) + marco (sem. 15).
- Autoavaliação: portfólio. Recuperação contínua: sem. 14.

## Continuação
B3 conclui o componente: persistência em banco (conexões, SQL, CRUD, consultas
parametrizadas, sanitização/SQL Injection) → web v0.8 com dados reais do schema da casa.
