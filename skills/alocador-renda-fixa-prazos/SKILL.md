---
name: alocador-renda-fixa-prazos
description: Use quando o usuário precisar alocar recursos de curto ou médio prazo, escolher onde guardar a Reserva de Liquidez (Fundo DI Taxa Zero vs Tesouro Selic), calcular IR regressivo/IOF ou filtrar títulos com juros semestrais.
---

# Skill: Alocador de Renda Fixa e Prazos

## Objetivo
Estruturar com precisão a alocação de curto e médio prazo do investidor (incluindo a Reserva de Liquidez e metas programadas), aplicando a Trindade Impossível dos investimentos, calculando o impacto de impostos (IR regressivo e IOF) e eliminando armadilhas de juros semestrais.

## Princípio
Não existe ativo que entregue ao mesmo tempo Rentabilidade Máxima, Liquidez Imediata e Segurança Total (A Trindade Impossível). Para a Reserva e objetivos de curto prazo, o investidor deve abrir mão da rentabilidade em favor da liquidez e da segurança absoluta.

## Processo

### Passo 1 - Escolha do Veículo da Reserva de Liquidez
Comparar os dois únicos destinos aprovados:
1. **Fundo DI Simples Taxa Zero**: Resgate diário imediato, isento da taxa de custódia da B3 (0,20% a.a.). Ideal para a primeira fatia da reserva.
2. **Tesouro Selic**: Segurança soberana do Governo Federal, liquidez D+1, com isenção de taxa de custódia para saldos até R$ 10.000.

### Passo 2 - Auditoria de Tributação e Prazos
1. **Tabela Regressiva de IR**:
   - Até 180 dias: $22,5\%$
   - 181 a 360 dias: $20,0\%$
   - 361 a 720 dias: $17,5\%$
   - Acima de 720 dias: $15,0\%$
2. **Tabela Regressiva de IOF**: Zera no 30º dia de aplicação.

### Passo 3 - Filtro Anti-Juros Semestrais
Auditar se o título público ou privado paga cupom semestral. Se pagar, **vetar para investidores em fase de acumulação**, pois antecipa o pagamento de IR na alíquota mais alta e destrói o efeito dos juros compostos.

### Passo 4 - Triagem de Crédito Privado
Auditar debêntures, CRIs e CRAs: se o spread de prêmio sobre o Tesouro IPCA+ não compensar a falta de garantia do FGC e o risco de crédito da empresa, direcionar para Títulos Públicos Federais.

## Regras da skill
- Reserva de Liquidez nunca é aplicada em renda variável, fundos com carência ou debêntures.
- Vetar títulos com juros semestrais para objetivos de acumulação patrimonial.
- Priorizar Fundo DI Taxa Zero sobre Tesouro Selic para saldos superiores a R$ 10.000 para economizar a taxa de custódia de 0,20% da B3.

## Exemplo de saída esperada
```markdown
### Alocação de Renda Fixa e Reserva
- **Destino da Reserva (R$ 30.000):**
  - R$ 10.000 em Tesouro Selic (Taxa de custódia B3 = 0%).
  - R$ 20.000 em Fundo DI Simples Taxa Zero (Economia de 0,20% a.a. e liquidez D+0).
- **Meta de 2 anos (R$ 50.000):** CDB de banco sólido a 105% do CDI sem liquidez diária, com resgate após 721 dias (alíquota mínima de 15% de IR).
```
