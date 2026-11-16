---
name: analisador-carteira-acoes
description: Use quando o usuário quiser analisar ações na Bolsa brasileira (B3), aplicar o checklist quantitativo de 6 critérios, classificar ações em Cruzeiro/Lancha/Barco Pirata, auditar diversificação setorial ou checar regras fiscais.
---

# Skill: Analisador de Carteira de Ações Brasil

## Objetivo
Conduzir a seleção fundamentalista rigorosa de ações na B3, aplicando o Checklist Quantitativo de 6 critérios, classificando os setores em Cruzeiro, Lancha ou Barco Pirata, e garantindo a diversificação mínima de 5 setores com teto de 20% por setor.

## Princípio
Comprar uma ação é tornar-se sócio de uma empresa real. O investidor não especula com gráficos nem tenta adivinhar o humor do mercado; ele se associa a empresas lucrativas, pouco endividadas, bem geridas e inseridas em setores perenes que pagam dividendos consistentes.

## Processo

### Passo 1 - Execução do Checklist Quantitativo (6 Critérios)
1. **P/L (Preço / Lucro)**: $\le 15\text{x}$ (preferencialmente abaixo da média histórica do setor).
2. **P/VP (Preço / Valor Patrimonial)**: $\le 2,5\text{x}$ (ou com ROE elevado que justifique o ágio).
3. **ROE (Retorno sobre Patrimônio)**: $\ge 10\%$ ao ano.
4. **Margem Líquida**: $\ge 10\%$.
5. **Dívida Líquida / EBIT**: $\le 2,5\text{x}$ (até $\le 3,5\text{x}$ para elétricas de concessão estável).
6. **EBIT > Lucro Líquido**: Confirma lucro operacional saudável, sem maquiagem contábil.

### Passo 2 - Classificação Setorial
- **Cruzeiro**: Elétricas, Bancos, Saneamento, Seguradoras.
- **Lancha**: Construção Civil, Varejo, Shoppings, Agronegócio de commodities.
- **Barco Pirata (VETO)**: Estatais de controle político instável, empresas em recuperação judicial, histórico crônico de prejuízos.

### Passo 3 - Auditoria de Diversificação
- Mínimo de **5 setores distintos**.
- **Teto de 20% de alocação por setor** para eliminar o risco de ruína setorial.
- Divisão equilibrada entre as empresas escolhidas dentro de cada setor.

### Passo 4 - Gatilhos de Venda e Isenção Fiscal
- Vender apenas se: a empresa perder seus fundamentos (prejuízos consecutivos, corrupção, explosão de dívida) ou se o preço atingir um múltiplo de bolha ($P/L > 25\text{x}$).
- Manter as vendas dentro do limite de **isenção de R$ 20.000/mês** para pessoa física em swing trade.

## Regras da skill
- Reprovação imediata se Dívida Líquida / EBIT $> 3,5\text{x}$ ou se a empresa apresentar prejuízo nos últimos 12 meses.
- Teto mandatório de 20% do capital de ações em um mesmo setor.
- Veto absoluto a ativos de Barco Pirata.

## Exemplo de saída esperada
```markdown
### Auditoria Fundamentalista: TAEE11
- **Setor:** Energia Elétrica - Transmissão (Cruzeiro) [APROVADO]
- **P/L:** 8,9x (Meta: <= 15x) [APROVADO]
- **P/VP:** 1,65x (Meta: <= 2,5x) [APROVADO]
- **ROE:** 18,5% (Meta: >= 10%) [APROVADO]
- **Margem Líquida:** 42,0% (Meta: >= 10%) [APROVADO]
- **Dívida Líquida / EBIT:** 3,1x (Meta concessionárias: <= 3,5x) [APROVADO]
- **EBIT > Lucro Líquido:** R$ 2,8 Bi > R$ 1,4 Bi [APROVADO]

**Resultado:** 6 de 6 critérios aprovados. Papel qualificado como Cruzeiro de alta perenidade.
```
