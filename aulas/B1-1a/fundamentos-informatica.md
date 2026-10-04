# B1 · 1ª SÉRIE · FUNDAMENTOS DA INFORMÁTICA — Plano de aulas ITA NEGRO

- Função (plano 612, I.16): Estudos e pesquisas na área de TI · Classificação: Execução
- Carga no bimestre: 80 horas-aula (50 min) · Pressuposto: 5 aulas/semana × 16 semanas
  (ajustar ao calendário da escola; manter a ordem das semanas)
- Competências/habilidades do plano: 1.1 distinguir hardware/software · 1.2 executar comandos
  em CLI · 2.1 utilizar sistemas computacionais
- Valores: criticidade, comportamento ético, respeito às normas
- Papel no ITA NEGRO: cada aluno monta e domina a ESTAÇÃO DE TRABALHO DA CASA (VM Linux)
  e cria o repositório da turma — infraestrutura usada nos 3 anos.
- Formato de toda aula (aula-âmbar): 15 min teoria + 30 min prática guiada + 5 min retrospectiva.

## Papéis TBL da semana (equipes de 4, rotativos por bimestre)
PO · DEV · QA · SEC — no B1 todos exercem todos os papéis ao menos uma vez (requisito de mestria).

## Sequência didática

| Sem | Base tecnológica (plano) | Prática guiada (30 min) | Evidência |
|-----|--------------------------|--------------------------|-----------|
| 1 | Diagnóstica + evolução da informática | Sondagem prática: o que cada um sabe operar; linha do tempo em equipe | Ficha diagnóstica individual |
| 2 | Representação binária, unidades de medida | Converter decimal↔binário; calcular tamanhos (KB/MB/GB) de arquivos reais | Exercício resolvido em equipe |
| 3 | Hardware | Identificar peças (máquina aberta ou fotos); relacionar peça↔função | Quadro hw da equipe |
| 4 | Software; livre vs proprietário | Licenças: comparar Windows/Linux; instalar app livre | Tabela livre×proprietário |
| 5 | Redes de computadores e internet | `ping`, `ip a`/`ifconfig`, traceroute no laboratório | Captura de tela comentada |
| 6 | Virtualização e nuvem | Criar a VM Linux da casa (VirtualBox): disco, memória, snapshot | VM funcional (checkpoint 1) |
| 7 | CLI: navegação básica | `pwd ls cd cat mkdir rm mv cp` — missão: organizar pastas do projeto | Print da árvore de pastas |
| 8 | CLI: manipulação de arquivos | Buscar e filtrar arquivos do repositório da turma | Script de organização |
| 9 | Pipes, redirecionamentos e filtros | `|`, `>`, `grep`, `sort`, `wc` em logs fictícios da casa | One-liners salvos no repo |
| 10 | Permissões | `chmod chown sudo`; caso: quem pode ler o dossiê da casa? | Checkpoint 2 (prático) |
| 11 | Execução de comandos em lote | Primeiro shell script: backup da pasta do projeto | Script no repositório |
| 12 | Processos | `ps top kill`; o que é um serviço | Anotação de laboratório |
| 13 | Interface gráfica + revisão | Configurar ambiente da VM (teclado, temas, atualizações) | VM personalizada |
| 14 | REVISÃO + recuperação contínua | Tutoria cruzada: nível sênior refaz checkpoint com quem ficou na base | Lista de pendências zerada |
| 15 | MARCO B1: montagem final | Prova prática: VM nova do zero em 2 aulas, com checklist | VM + repo `ita-negro` criado |
| 16 | Defesa + autoavaliação | Cada aluno demonstra 3 comandos e explica; portfólio bimestral | Portfólio + menção |

## Avaliação (formato plano 612)
- Diagnóstica: semana 1 (sondagem, não vale menção).
- Formativa: retrospectivas diárias + observação direta nos laboratórios.
- Cumulativa: checkpoints (sem. 6 e 10) + marco (sem. 15).
- Autoavaliação: portfólio (o que fiz, papel exercido, reflexão).
- Recuperação contínua: semana 14, ANTES do fechamento bimestral.

## Ambiente
Laboratório com VirtualBox + ISO Linux (gratuitos), projetor, repositório Git da turma
(criado na semana 15 pelo PO de cada equipe com supervisão).
