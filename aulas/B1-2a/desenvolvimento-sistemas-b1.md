# B1 · 2ª SÉRIE · DESENVOLVIMENTO DE SISTEMAS (parte 1 de 2) — ITA NEGRO

- Componente II.16 (plano 612) · Função: Programação de sistemas desktop · Execução
- Carga anual: 120 h-a · Neste bimestre: ≈60 h-a (3–4 aulas/semana)
- Habilidades do plano trabalhadas no B1: 1.1 codificar orientado a objetos · 1.4 técnicas de OO
  (início) · 1.2 ambiente desktop (início)
- Bases tecnológicas deste bimestre: classes, objetos e instanciação; atributos e métodos;
  encapsulamento; construtores; sobrecarga de métodos; herança; sobre-escrita; sobrecarga de
  construtores; polimorfismo; classes abstratas e interfaces; namespaces/organização em pacotes
- Papel no ITA NEGRO: o domínio do produto vira CLASSES — as entidades do schema v1.0 (BD I,
  B4-1ª) e os módulos-núcleo da biblioteca 0.1 migram para OO. Linguagem: a do professor
  (sugestão: Java ou C# — ambas gratuitas e cobradas no mercado).
- Formato aula-âmbar: 15 teoria + 30 prática + 5 retrospectiva.

## Sequência didática

| Sem | Base tecnológica (plano) | Prática guiada (30 min) | Evidência |
|-----|--------------------------|--------------------------|-----------|
| 1 | Diagnóstica + do procedural ao OO | Refazer módulo B1 em 1 classe (comparação lado a lado) | Ficha diagnóstica |
| 2 | Classes, objetos e instanciação | Classe `Membro` da casa: primeiro objeto no `main` | Classe Membro v1 |
| 3 | Atributos e métodos | `Membro`: registrarPonto(), status() | Classe com comportamento |
| 4 | Encapsulamento (getters/setters, validação) | Blindar atributos: dado inválido é recusado | Membro blindado |
| 5 | Construtores + sobrecarga de construtores | Membro com 0, 2 ou 4 dados iniciais | Checkpoint 1 |
| 6 | Sobrecarga de métodos | `alertar(msg)` × `alertar(msg, nivel)` | Biblioteca de alertas |
| 7 | Herança | `Pessoa` → `Membro`, `Visitante` | Hierarquia v1 |
| 8 | Sobre-escrita de métodos | Cada subclasse responde `status()` do seu jeito | Demo polimórfica |
| 9 | Polimorfismo | Lista de `Pessoa` tratada uniformemente | Checkpoint 2 |
| 10 | Classes abstratas | `Sensor` abstrata: cada sensor implementa `ler()` | Sensor abstrata |
| 11 | Interfaces | `Conectavel`: contrato do que se liga à rede da casa | Interface Conectavel |
| 12 | Namespaces e organização em pacotes | Estrutura de pacotes do produto (modelo, serviço, util) | Árvore de pacotes |
| 13 | Diagrama de classes (ponte com B3-1ª) | Desenhar as classes reais que escreveram | Diagrama v1 |
| 14 | REVISÃO + recuperação contínua | Tutoria cruzada; refazer hierarquia pendente | Pendências zeradas |
| 15 | MARCO B1: modelo OO do produto | Banca: domínio completo em classes, com teste de mesa | Modelo OO v1 |
| 16 | Defesa + autoavaliação | Portfólio: comparativo procedural×OO do mesmo código | Portfólio + menção |

## Avaliação (formato plano 612)
- Formativa: retrospectivas + revisão de código entre pares (troca de repositório semanal).
- Cumulativa: checkpoints (sem. 5 e 9) + marco (sem. 15).
- Autoavaliação: portfólio. Recuperação contínua: sem. 14 antes do fechamento.

## Continuação
B2 conclui o componente: padrão MVC, GUI (diálogos, formulários, campos), padrão DAO,
conexão ao banco, CRUD e consultas parametrizadas com prevenção de SQL Injection →
app desktop v0.5 conectado ao schema real.
