---
name: protetor-antiacoes-ouro-dolar
description: Use quando o usuário quiser dimensionar o pilar de antiações (Dólar e Ouro), calcular a proteção contra assimetria de perdas, entender a regra da dupla exposição cambial do ouro ou vetar joias e mineradoras.
---

# Skill: Protetor de Antiações (Dólar e Ouro)

## Objetivo
Dimensionar e auditar o pilar "G" (Gold / Antiações) da carteira MAGAR, garantindo a blindagem patrimonial contra choques econômicos internos e crises geopolíticas globais, e aplicando a regra inegociável da dupla exposição cambial.

## Princípio
Quedas fortes exigem valorizações monumentais para recuperar o capital perdido (a Assimetria de Perdas de Buffett). Antiações descorrelacionadas (Dólar e Ouro) disparam exatamente quando o mercado de ações despenca, amortecendo o portfólio e gerando caixa no rebalanceamento para comprar ações na baixa.

## Processo

### Passo 1 - Dimensionamento da Assimetria de Perdas
Calcular o ganho necessário para recuperar drawdowns:
$$\text{Ganho Necessário} = \frac{1}{1 - \text{Queda}} - 1$$
Demonstrar a importância das antiações para impedir que o portfólio sofra perdas superiores a 20%.

### Passo 2 - Seleção dos Instrumentos Homologados
1. **Dólar (Fluxo Cambial Doméstico)**:
   - No Brasil: Fundo Cambial passivo com taxa $\le 0,10\%$ a.a. (ex: BTG Pactual Dólar FI Cambial).
   - No Exterior: ETF `SGOV` (T-Bills curtas de até 3 meses, taxa de 0,09% a.a.).
2. **Ouro (Crises Geopolíticas Globais)**:
   - No Exterior: ETF `IAU` (ou `GLD`), lastreado em barras de ouro físicas em Londres.
   - No Brasil: Fundo BTG Pactual Ouro USD FI MM ou ETF `GOLD11`.

### Passo 3 - Auditoria da Dupla Exposição Cambial
Verificar se o fundo ou ETF de ouro NÃO possui proteção cambial (hedge para Real):
$$\text{Retorno em R\$} = (1 + \Delta_{\text{Ouro em US\$}}) \times (1 + \Delta_{\text{Dólar em R\$}}) - 1$$

### Passo 4 - Filtros de Exclusão (Vetos do Método)
- 🚫 **Joias de Ouro**: Veto absoluto (margem de ourives inflaciona o preço em 2x a 3x).
- 🚫 **Ações de Mineradoras**: Veto absoluto (carregam risco operacional de mina e custos de extração).
- 🚫 **Barras Físicas Bancárias**: Veto (custódia cara e atrito de recompra).
- 🚫 **Fundos Cambiais com Taxa $> 0,50\%$ a.a.**.

## Regras da skill
- Proibição absoluta de ouro com proteção cambial (*hedge* para Real).
- Vetar joias e mineradoras como antiações.
- Manter divisão 50/50 entre Dólar e Ouro dentro da fatia de antiações como padrão passivo.

## Exemplo de saída esperada
```markdown
### Auditoria do Pilar de Antiações
- **Alocação Alvo:** 10% da carteira total (5% Dólar e 5% Ouro)
- **Ativo Dólar:** ETF SGOV (Taxa 0,09% a.a.) [HOMOLOGADO]
- **Ativo Ouro:** ETF IAU (Taxa 0,25% a.a., sem hedge cambial) [HOMOLOGADO]
- **Efeito Dupla Exposição:** Se o Ouro subir 15% em US$ e o Dólar subir 20% frente ao Real, o ganho em Reais será de **+38,0%**.
```
