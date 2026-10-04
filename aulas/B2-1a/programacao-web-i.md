# B2 · 1ª SÉRIE · PROGRAMAÇÃO WEB I — Plano de aulas ITA NEGRO

- Componente I.13 (plano 612) · Função: Desenvolvimento de páginas para internet · Execução
- Carga: 80 h-a no bimestre (5 aulas/semana × 16 semanas) — componente integral neste bimestre
- Competência/habilidades do plano: 1.1 linguagem de marcação · 1.2 linguagem de script
  para Web · 1.3 folhas de estilo
- Bases tecnológicas (plano): HTML5 (elemento raiz, metadados, seções, semântica, hyperlinks,
  imagens/SVG, tabelas, formulários) · CSS (cascata, seletores, box model, pré-processador,
  estilização de conteúdo e formulários) · leiaute (posicionamentos, float/z-index, largura
  fixa/líquida/elástica/híbrida, media queries mobile-first) · Bootstrap (grade, componentes,
  formulários) · JavaScript (sintaxe, variáveis, escopo, controle de fluxo, erros, laços,
  cookies) · jQuery (função $, seletores, eventos)
- Valores (plano): criatividade, organização, resolução de situações-problema
- Papel no ITA NEGRO: publicar o SITE DA CASA — vitrine do produto, usando o manual de marca v1
  (Design Digital, B1) e exibindo dados dos módulos-núcleo (Técnicas, B1–B2).
- Interdisciplinar (sugestão literal do plano): tema das páginas alinhado com História/Arte
  (timeline da arte até a Era Digital) ou Ciências (coleção interativa) — combinar com os
  professores da BNCC.
- Formato aula-âmbar: 15 teoria + 30 prática + 5 retrospectiva.

## Sequência didática

| Sem | Base tecnológica (plano) | Prática guiada (30 min) | Evidência |
|-----|--------------------------|--------------------------|-----------|
| 1 | Diagnóstica + como a Web funciona (cliente/servidor) | Primeiro .html no navegador; inspecionar um site real | Ficha diagnóstica |
| 2 | HTML: elemento raiz, metadados, scripting | Estrutura mínima válida; title, meta, charset | Página esqueleto |
| 3 | HTML: seções e agrupamento | header/nav/main/section/aside/footer do site da casa | Estrutura semântica |
| 4 | HTML: semântica textual e hyperlinks | Página "Sobre a casa" com links internos/externos | Página sobre |
| 5 | HTML: imagens, vetores SVG e conteúdo embutido | Logo (vetor do B1) como SVG; vídeo/mapa embutido | Home com mídia |
| 6 | HTML: tabelas | Tabela de sensores/cômodos com thead/tbody | Checkpoint 1 |
| 7 | HTML: formulários | Formulário "fale com a casa" (todos os tipos de input) | Formulário v1 |
| 8 | CSS: cascata, regra, seletores, atributos | Estilizar a home com o manual de marca (paleta B1) | Home estilizada |
| 9 | CSS: box model + formatação | Cards dos módulos com espaçamento e borda | Cards v1 |
| 10 | CSS: estilização de conteúdo e formulários; pré-processador (demo) | Formulário bonito e acessível; demo Sass ao vivo | Checkpoint 2 |
| 11 | Leiaute: posicionamento padrão/absoluto/relativo, float, z-index | Barra de navegação fixa | Nav fixa |
| 12 | Leiaute: largura fixa, líquida, elástica, híbrida + media queries mobile-first | Home responsiva (celular primeiro) | Home responsiva |
| 13 | Bootstrap: grade responsiva, componentes, formulários | Rebuild da home em Bootstrap comparando com CSS puro | Home Bootstrap |
| 14 | JS: sintaxe, variáveis, escopo, controle de fluxo, erros, laços | Menu que calcula/valida (ex.: checklist de status da casa) | Script de validação |
| 15 | MARCO: JS final (cookies) + jQuery ($, seletores, eventos) + publicação do site | Cookie de visitante; eventos jQuery; deploy no gh-pages/000webhost | SITE DA CASA no ar |
| 16 | Defesa + autoavaliação | Pitch: cada equipe apresenta o site; portfólio bimestral | Portfólio + menção |

Observação de carga: JS/jQuery entram nas semanas 14–15 como INICIAÇÃO (o plano coloca o
aprofundamento de script no PW II, 2ª série). Se a turma avançar rápido, antecipar laços JS.

## Avaliação (formato plano 612)
- Diagnóstica: sem. 1 · Formativa: retrospectivas + code review entre equipes (PR no repo).
- Cumulativa: checkpoints (sem. 6 e 10) + marco site publicado (sem. 15).
- Autoavaliação: portfólio com URL do site. Recuperação contínua: sem. 14, refação guiada
  do checkpoint para quem ficou na base, antes do fechamento.

## Entrega para o próximo componente
Site no ar + formulário v1 → o formulário e a tabela de sensores recebem back-end no
Programação Web II (2ª série). Wireframes do Design Digital são o critério de usabilidade.
