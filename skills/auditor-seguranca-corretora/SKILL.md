---
name: auditor-seguranca-corretora
description: Use quando o usuário quiser avaliar a segurança de uma corretora ou banco, calcular a rentabilidade real líquida com a Equação de Fisher, checar limites do FGC ou identificar conflitos de interesses e produtos tóxicos como COEs.
---

# Skill: Auditor de Segurança e Corretora

## Objetivo
Blindar o patrimônio do investidor contra riscos institucionais, auditar a solvência de corretoras e bancos, aplicar a Equação de Fisher para desmascarar promessas enganosas de rentabilidade e vetar ofertas tóxicas ou com conflito de interesses (como COEs e títulos de alto risco).

## Princípio
A primeira regra de Warren Buffett é: nunca perca dinheiro; a segunda regra é: nunca se esqueça da primeira. Corretoras são prestadoras de serviços de custódia e intermediação, não cofres. Antes de buscar rentabilidade, é obrigatório garantir segregação patrimonial e respaldo regulatório.

## Processo

### Passo 1 - Auditoria Institucional da Corretora
Verificar se a instituição possui:
- Registro ativo na CVM e aderência às normas da ANBIMA.
- Acesso ao Homebroker oficial com execução direta na B3.
- Cobertura do BSM / MRP (Mecanismo de Ressarcimento de Prejuízos) até R$ 120 mil por ocorrência operacional.
- Alerta de conta-corrente: saldo não investido em conta de corretora não possui cobertura do FGC.

### Passo 2 - Auditoria de Limites do FGC
- Limite de R$ 250.000 por CPF e por conglomerado financeiro (incluindo capital e juros projetados).
- Teto global de R$ 1.000.000 renovável a cada 4 anos.

### Passo 3 - Cálculo da Rentabilidade Real Líquida (Equação de Fisher)
$$(1 + i_{\text{líquido}}) = (1 + r_{\text{real}}) \times (1 + \text{IPCA}) \implies r_{\text{real}} = \frac{1 + i_{\text{líquido}}}{1 + \text{IPCA}} - 1$$
Descontar o Imposto de Renda regressivo e a inflação projetada para apurar o ganho real.

### Passo 4 - Filtro Anti-Conflito de Interesses
- Veto automático a COEs (Certificados de Operações Estruturadas): produtos com margem opaca e rentabilidade real historicamente defasada.
- Veto a Fundos de Renda Fixa com taxa de administração $> 0,30\%$ a.a.

## Regras da skill
- Saldo parado em conta de corretora deve ser zerado imediatamente (aplicar em Fundo DI Taxa Zero ou Tesouro Selic).
- Nunca ultrapassar R$ 250.000 por emissor bancário.
- Alerta vermelho imediato se a corretora ou assessor oferecer COE ou investimentos com taxa de rebate embutida.

## Exemplo de saída esperada
```markdown
### Relatório de Auditoria de Segurança
- **Instituição Auditada:** Corretora X (Aprovada CVM / BSM)
- **Produto Oferecido:** CDB Pré 14% a.a. (Prazo 3 anos)
- **Rentabilidade Real Líquida:** Com IPCA projetado a 5,5% e IR de 15%, o ganho real líquido é de **+5,88% a.a.**
- **Limite FGC:** Aplicação de R$ 180.000 resulta em R$ 257.000 no vencimento -> **ALERTA: Reduzir aporte inicial para R$ 170.000 para não estourar o teto de R$ 250k**.
```
