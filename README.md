# 🤖 MAGAR Finance Agent — Investidor Sempre em Alta

> Mentor e estrategista autônomo de alocação de ativos e finanças pessoais baseado na metodologia Investidor Sempre em Alta (Vinícius Mariño), estruturado no **Padrão DIO (Harness-Native)**.

---

## 📊 Sobre o Repositório

Este repositório reúne materiais educativos, análises e a implementação completa do **MAGAR Finance Agent**, um agente autônomo que não depende de código ou servidores proprietários: sua inteligência é executada de forma nativa por harnesses avançados de IA (como **Google Antigravity** e **Claude Code**) utilizando Markdown puro, instruções orientadas a objetivos e checklists de rigor matemático.

O agente guia o investidor através de uma esteira sequencial de 9 etapas: desde o diagnóstico financeiro profundo da sua vida histórica (anamnese) e o dimensionamento da Reserva de Liquidez e metas de Independência Financeira, até a seleção de ativos perenes na B3 (Ações e FIIs), a blindagem por antiações (Dólar e Ouro) e a internacionalização do patrimônio com ETFs globais nos EUA.

Além disso, o agente automatiza o rebalanceamento mensal sem giro desnecessário de carteira, direcionando novos aportes e dividendos reinvestidos para comprar na baixa e proteger o investidor em qualquer ciclo econômico.

---

## 🚀 Como usar o Agente

1. **Instale um harness compatível**:
   - [Google Antigravity](https://deepmind.google/technologies/antigravity/) ou [Claude Code](https://claude.ai/code).
2. **Clone este repositório**:
   ```bash
   git clone https://github.com/FabioPereira445/investidor-sempre-em-alta.git
   ```
3. **Abra a pasta no harness e converse**:
   - O harness lê o arquivo [`AGENTS.md`](./AGENTS.md) automaticamente e ativa as skills por intenção à medida que você conversa!
   - Exemplos de conversas:
     - *"Quero fazer um diagnóstico da minha vida financeira histórica."*
     - *"Quanto preciso investir por mês para me aposentar com R$ 5 mil?"*
     - *"Analise se a ação TAEE11 passa no checklist do método."*
     - *"Tenho R$ 3.000 de aporte este mês, para onde deve ir o dinheiro na minha MAGAR?"*
     - *"Como começo a investir no exterior sem cair no imposto de herança americano?"*

---

## 🛠️ Skills Disponíveis no Agente

| Skill | Para que serve |
| :--- | :--- |
| [`anamnese-financeira`](./skills/anamnese-financeira/SKILL.md) | Diagnostica a vida financeira histórica, calcula total ganho e gasto na vida e mede a taxa de conversão em ativos geradores de renda. |
| [`planejador-independencia-metas`](./skills/planejador-independencia-metas/SKILL.md) | Dimensiona a Reserva de Liquidez ($3\text{x}, 6\text{x}$ ou $12\text{x}$ custos) e calcula o patrimônio para Independência Financeira (Regra dos 300 / 4% real). |
| [`auditor-seguranca-corretora`](./skills/auditor-seguranca-corretora/SKILL.md) | Audita a solidez de bancos e corretoras, monitora limites do FGC (R$ 250k) e MRP/BSM, e calcula rentabilidade real líquida (Equação de Fisher). |
| [`alocador-renda-fixa-prazos`](./skills/alocador-renda-fixa-prazos/SKILL.md) | Aloca a Reserva (Fundo DI Taxa Zero vs Tesouro Selic), calcula IR regressivo/IOF e elimina títulos com armadilha de juros semestrais. |
| [`analisador-carteira-acoes`](./skills/analisador-carteira-acoes/SKILL.md) | Aplica o checklist quantitativo de 6 critérios em ações na B3, classifica setores em Cruzeiro/Lancha e audita diversificação setorial ($\le 20\%$). |
| [`protetor-antiacoes-ouro-dolar`](./skills/protetor-antiacoes-ouro-dolar/SKILL.md) | Dimensiona o pilar de antiações (Dólar e Ouro) contra a assimetria de perdas e audita a regra inegociável da dupla exposição cambial do ouro. |
| [`potencializador-fiis-titulos-publicos`](./skills/potencializador-fiis-titulos-publicos/SKILL.md) | Aplica o checklist de 11 critérios para FIIs, projeta ganhos com Marcação a Mercado no Tesouro IPCA+ longo (Duration) e apura DARF 6015. |
| [`rebalanceador-magar`](./skills/rebalanceador-magar/SKILL.md) | Define a alocação da carteira MAGAR via Teste do Travesseiro e relação 3:1, governa a esteira sequencial do zero e calcula os aportes mensais sem vendas. |
| [`internacionalizador-magar`](./skills/internacionalizador-magar/SKILL.md) | Estrutura a MAGAR Internacional com ETFs globais (`VOO` e `GLD`), audita a trava de US$ 60k do Estate Tax americano e aplica a Lei 14.754/2023. |

---

## 📁 Estrutura do Repositório (Padrão DIO)

```text
investidor-sempre-em-alta/
├── AGENTS.md                          <- Entrypoint principal do agente (lido pelo harness)
├── CLAUDE.md                          <- Atalho de compatibilidade para Claude Code
├── PROMPT.md                          <- Prompt clássico complementar para ChatGPT
├── README.md                          <- Documentação principal unificada
├── LICENSE                            <- Licença MIT
├── agent/
│   ├── persona.md                     <- Personalidade, valores e tom de voz
│   └── knowledge/
│       └── contexto.md                <- Base de conhecimento do domínio e fórmulas
├── docs/
│   └── glossary.md                    <- Glossário de termos técnicos e financeiros
└── skills/
    ├── README.md                      <- Guia de criação de novas habilidades
    ├── anamnese-financeira/
    │   └── SKILL.md
    ├── planejador-independencia-metas/
    │   └── SKILL.md
    ├── auditor-seguranca-corretora/
    │   └── SKILL.md
    ├── alocador-renda-fixa-prazos/
    │   └── SKILL.md
    ├── analisador-carteira-acoes/
    │   └── SKILL.md
    ├── protetor-antiacoes-ouro-dolar/
    │   └── SKILL.md
    ├── potencializador-fiis-titulos-publicos/
    │   └── SKILL.md
    ├── rebalanceador-magar/
    │   └── SKILL.md
    └── internacionalizador-magar/
        └── SKILL.md
```

---

## 🔗 Materiais Educativos Adicionais

- **NotebookLM:** Acesse o material de estudo complementar no [NotebookLM](https://notebooklm.google.com/notebook/dc1ed9f8-6de3-4fc0-9077-d2b66ec7e211?original_referer=https:%2F%2Fnotebooklm.google%23&pli=1).
- **Prompt ChatGPT:** Instruções detalhadas para análises complementares em [`PROMPT.md`](PROMPT.md).
