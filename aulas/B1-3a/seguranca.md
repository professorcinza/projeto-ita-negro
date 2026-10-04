# B1 · 3ª SÉRIE · INTERNET, PROTOCOLOS E SEGURANÇA DE SISTEMAS DA INFORMAÇÃO — ITA NEGRO

- Componente III.13 (plano 612) · Função: Configuração de serviços de rede com rotinas de
  segurança física e lógica · Classificação: Execução e Controle · Carga: 80 h-a no bimestre
- Competências/habilidades do plano: 1.1 modelos de referência de redes · 1.2 protocolos de
  rede e comunicação de dados · 2.1 identificar ameaças · 2.2 técnicas de segurança ·
  2.3 operar mecanismos de segurança
- Bases tecnológicas: OSI/ISO, meios e topologias; camadas física/enlace/rede (endereçamento
  físico e IP, roteamento, ARP/DHCP, NAT, firewall, proxy); protocolos de aplicação (FTP,
  acesso remoto, VPN, e-mail); conceitos de segurança; Cartilha de Segurança Internet (CERT.br);
  mecanismos e características de segurança; políticas; criptografia e firewall; segurança em
  redes e dispositivos móveis; vulnerabilidades; engenharia social; varredura; DoS/DDoS;
  testes de penetração; SQL Injection; footprint
- Valores: comportamentos éticos, resolução de situações-problema, respeito às normas
- Papel no ITA NEGRO: PENTEST DO PRÓPRIO PRODUTO — a turma ataca o sistema que construiu
  (web v0.8 + app + desktop) num laboratório controlado, documenta as falhas e propõe as
  correções que serão executadas no B2 (Web III). Ética: alvo autorizado, ambiente isolado.
- Formato aula-âmbar: 15 teoria + 30 prática + 5 retrospectiva.

## Sequência didática

| Sem | Base tecnológica (plano) | Prática guiada (30 min) | Evidência |
|-----|--------------------------|--------------------------|-----------|
| 1 | Diagnóstica + modelos OSI/TCP-IP | Camadas na prática: rastrear uma requisição do app até o banco | Ficha diagnóstica |
| 2 | Meios, topologias, endereçamento físico/IP | Mapear a rede do laboratório (ip a, arp) | Mapa da rede |
| 3 | Roteamento, ARP, DHCP | Montar rede virtual entre 2 VMs; diagnosticar falha plantada | Rede de teste OK |
| 4 | NAT, firewall, proxy | Bloquear/permitir portas com firewall da VM | Checkpoint 1 |
| 5 | Protocolos de aplicação (FTP, SSH, e-mail) | Acesso remoto seguro vs inseguro (SSH×telnet) | Comparativo |
| 6 | VPN e tunelamento | Túnel simples entre VMs; por que a casa usaria VPN | Registro do túnel |
| 7 | Conceitos de segurança + Cartilha CERT.br | Ler cartilha e extrair os 10 riscos do produto | Lista de riscos v1 |
| 8 | MARCO PARCIAL: política de segurança da casa | Escrever política de senhas, backup e acesso | Checkpoint 2: política v1 |
| 9 | Engenharia social | Simulação ética: phishing interno autorizado (quem cai?) | Relatório da simulação |
| 10 | Footprint e varredura (nmap em lab isolado) | Mapear serviços do servidor de testes da casa | Inventário de serviços |
| 11 | Identification de vulnerabilidades | Avaliar web v0.8: validação, sessão, permissões | Lista de vulnerabilidades |
| 12 | SQL Injection e DoS (conceito + demo controlada) | Repetir o ataque do B3-2ª agora com análise formal | Análise da injeção |
| 13 | Criptografia e firewall no produto | HTTPS com certificado self-signed; hash de senhas | HTTPS ativo |
| 14 | REVISÃO + recuperação contínua | Refazer varredura/vulnerabilidades com tutoria | Pendências zeradas |
| 15 | MARCO B1: RELATÓRIO DE PENTEST | Banca: falhas documentadas + plano de correção priorizado | Relatório de pentest v1 |
| 16 | Defesa + autoavaliação | Portfólio; assinar termo de uso ético da sala de segurança | Portfólio + menção |

## Avaliação (formato plano 612)
- Formativa: retrospectivas + revisão dos relatórios entre equipes.
- Cumulativa: checkpoints (sem. 4 e 8) + marco (sem. 15, relatório de pentest).
- Autoavaliação: portfólio. Recuperação contínua: sem. 14.

## Entrega para o próximo bimestre
Relatório de pentest com correções priorizadas → Web III (B1–B2) executa as correções ao
migrar para framework; Qualidade e Teste (B2) cria os testes que provam a correção.

## TCC neste bimestre (PTCC — 1º semestre, ≈30 h-a)
Semanas 1–8: cenário da área, problematização, CANVAS do produto, construção de hipóteses,
objetivos (geral/específicos) e justificativa — usando os requisitos v1.0 da 1ª série como base.
