# B3 · 3ª SÉRIE · PROGRAMAÇÃO MOBILE II + SISTEMAS EMBARCADOS — ITA NEGRO

Dois componentes em paralelo (cargas somam ≈5 aulas/semana):
- **Mobile II** (III.12, 80 h-a): habilidades 1.1 ambientes mobile · 1.2 app com acesso a banco
  · 1.3 leiaute para dispositivos móveis · 1.4 recursos avançados (smartphones/tablets). Bases:
  consumo de APIs e serviços Web (HTTP, XML, JSON); localização e mapas; sensores; widgets;
  notificações; permissões; interação com outros apps; dispositivos sem fio.
- **Sistemas Embarcados** (III.16, 80 h-a): habilidades 1.1 características de sistemas
  embarcados · 2.1 programar microcontroladores · 2.2 executar instruções. Bases: placas, IDE,
  linguagem, simuladores; elétrica básica (corrente, tensão, resistência, circuitos serial/
  paralelo); plataforma (placa, shields, protoboards, LEDs, botões); setup()/loop(); E/S digital
  e analógica; timers; memória; fluxo; funções; sensores, sons, interrupções, serial.

- Papel no ITA NEGRO: o produto ganha CORPO — app v1.0 nativo consumindo a API v1.0 (B2) e o
  NÓ SENSOR físico (Arduino) medindo o mundo real. A telemetria do sensor entra na API e
  aparece no app: fecha o ciclo material do produto.
- Formato aula-âmbar: 15 teoria + 30 prática + 5 retrospectiva.

## Trilha A — Mobile II (2–3 aulas/semana)

| Sem | Base tecnológica (plano) | Prática guiada | Evidência |
|-----|--------------------------|----------------|-----------|
| 1 | Diagnóstica + HTTP e JSON no mobile | GET na API v1.0 pelo app (print do JSON na tela) | Ficha diagnóstica |
| 2 | Ambiente nativo/framework escolhido | Projeto novo rodando no celular da turma | App base |
| 3 | Consumindo a API: listagem | Lista de membros/sensores da API | Checkpoint 1 |
| 4 | Login contra a API (token) | Autenticação do app com token do B2 | Login OK |
| 5 | Formulários e envio (POST/PUT) | Cadastrar/editar pelo app | CRUD mobile |
| 6 | Localização e mapas | Mapa com posição dos sensores | Tela de mapa |
| 7 | Sensores do celular | Acelerômetro dispara alerta (versão nativa) | Checkpoint 2 |
| 8 | Widgets e notificações | Notificação push/local de alerta crítico | Notificação OK |
| 9 | Permissões avançadas | Justificativa por permissão (LGPD da casa) | Tela de permissões v2 |
| 10 | Interação com outros apps | Compartilhar relatório do produto (share intent) | Checkpoint 3 |
| 11 | Dispositivos sem fio | Receber telemetria do nó sensor via API (ponte Trilha B) | App+sensor |
| 12 | Leiaute final + revisão cruzada | Polir telas conforme manual de marca; QA cruzado | Relatório QA |
| 13 | Estabilização e build final | APK assinado de testes distribuído à turma | APP v1.0 |
| 14 | RECAP + recuperação contínua | Refazer tela/endpoint com tutoria | Pendências zeradas |
| 15 | MARCO: APP v1.0 | Banca: app instalado e operando contra a API real | App v1.0 taggeado |
| 16 | Defesa + autoavaliação | Portfólio: fluxo completo mobile→API→banco→sensor | Portfólio + menção |

## Trilha B — Sistemas Embarcados (2–3 aulas/semana)

| Sem | Base tecnológica (plano) | Prática guiada | Evidência |
|-----|--------------------------|----------------|-----------|
| 1 | Diagnóstica + intro microcontroladores | O que é uma placa; IDE instalada; blink de teste | Blink OK |
| 2 | Elétrica: corrente, tensão, resistência | Medir com multímetro; LED com resistor calculado | Cálculo do resistor |
| 3 | Circuitos serial e paralelo | Montar os 2 no protoboard | Checkpoint 1 |
| 4 | Estrutura setup()/loop(); compilar/gravar | Programar sequência de LEDs | Firmware v0 |
| 5 | E/S digital (pinMode, digitalWrite, digitalRead) | Botão + LED: alarme manual da casa | Alarme manual |
| 6 | E/S analógica (analogRead/Write) | LDR medindo luz do laboratório | Checkpoint 2: leitura real |
| 7 | Timers e contadores | Piscar sem delay (não bloquear o loop) | Blink sem delay |
| 8 | Fluxo: decisão e laços no firmware | Estados do alarme (armado/disparado/reset) | Máquina de estados |
| 9 | Programação modular: funções e escopo | Extrair funções do firmware | Firmware modular |
| 10 | Bibliotecas e funções predefinidas | Sensor DHT11/temperatura via biblioteca | Checkpoint 3: sensor real |
| 11 | Comunicação serial | Enviar leituras ao PC (serial monitor) | Telemetria serial |
| 12 | Ponte com a API (com o professor de Web III) | Node/ESP enviar leitura → endpoint da API | Sensor→API |
| 13 | Integração final | Sensor no cômodo → dado no app (ponte Trilha A) | Ciclo completo |
| 14 | RECAP + recuperação contínua | Refazer firmware com tutoria | Pendências zeradas |
| 15 | MARCO: NÓ SENSOR v1 | Banca: telemetria do cômodo até o celular | Nó sensor v1 |
| 16 | Defesa + autoavaliação | Portfólio: foto do circuito + código comentado | Portfólio + menção |

## Avaliação (formato plano 612)
- Formativa: retrospectivas + QA cruzado do app + revisão de firmware entre equipes.
- Cumulativa: checkpoints das trilhas + marcos sem. 15 (app v1.0 E nó sensor v1).
- Autoavaliação: portfólio integrado. Recuperação contínua: sem. 14.

## TCC (Desenvolvimento do TCC — 2º semestre)
Neste bimestre o TCC entra em ritmo pleno (o componente III.14 tem 120 h-a no ano):
diagramas de caso de uso e de classes (habilidade 5.1), relatórios de desenvolvimento
(habilidade 3.2), cronograma físico-financeiro (3.1) e gráficos (3.3) com os dados reais
das releases. Sugestão: 1 aula de TCC por semana (terceiro dia de aula dupla).

## Entrega para o bimestre final
Produto v1.0 completo (3 plataformas + sensor físico + API testada) → B4 empacota, documenta
e defende na BANCA FINAL como TCC (protótipo com manual técnico — Portaria 354/2015).
