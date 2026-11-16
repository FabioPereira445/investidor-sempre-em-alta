---
name: planejador-independencia-metas
description: Use quando o usuário quiser dimensionar sua Reserva de Liquidez, calcular o valor e tempo para a Independência Financeira, aplicar a fórmula VCP ou montar a Tabela de Metas com aportes mensais.
---

# Skill: Planejador de Metas e Independência Financeira

## Objetivo
Estruturar o plano mestre de metas financeiras do investidor (curto, médio e longo prazo), dimensionando a Reserva de Liquidez necessária, calculando o patrimônio para a Independência Financeira (IF) e projetando os aportes mensais exatos via fórmula VCP.

## Princípio
Sonhos sem data e sem valor monetário são apenas ilusões. A metodologia transforma desejos em metas matemáticas tangíveis divididas em quatro colunas claras: O Quê? Quando? Quanto? e Aporte Mensal Necessário.

## Processo

### Passo 1 - Dimensionamento da Reserva de Liquidez
Calcular o valor da reserva com base no perfil de estabilidade profissional:
- Funcionário Público / Renda Estável: $3\text{x}$ o custo de vida mensal.
- CLT / Renda Moderada: $6\text{x}$ o custo de vida mensal.
- Autônomo / Empresário / Renda Variável: $12\text{x}$ o custo de vida mensal.

### Passo 2 - Cálculo do Patrimônio para Independência Financeira
1. **Método Simplificado (Regra dos 300)**:
   $$\text{Patrimônio IF} = \text{Renda Mensal Desejada} \times 300$$
2. **Método Completo (Taxa Real Acima da Inflação)**:
   $$\text{Patrimônio IF} = \frac{\text{Renda Anual Desejada}}{\text{Taxa Real Líquida (ex: 4% a 5% a.a.)}}$$

### Passo 3 - Aplicação da Fórmula VCP
$$\text{VCP} = \text{VI} \times R \times T$$
Simular o tempo e a força dos juros compostos para atingir o valor acumulado necessário.

### Passo 4 - Elaboração da Tabela de Metas
Calcular o aporte mensal necessário para cada objetivo em função do prazo e da taxa real esperada. Caso a soma dos aportes supere a capacidade de poupança atual, aplicar o rebalanceamento de prazos.

## Regras da skill
- A Reserva de Liquidez é pré-requisito inegociável antes de alocar em ações ou FIIs.
- Não utilizar taxas nominais infladas; projeções devem sempre adotar taxa de rentabilidade real líquida (acima da inflação).
- Se os aportes mensais necessários superarem a capacidade de poupança, ajustar os prazos das metas antes de propor investimentos arriscados.

## Exemplo de saída esperada
```markdown
### Tabela de Metas do Investidor
| Objetivo (O Quê?) | Prazo (Quando?) | Custo Total (Quanto?) | Aporte Mensal Necessário |
| :--- | :---: | :---: | :---: |
| **Reserva de Liquidez (6x)** | 12 meses | R$ 15.000,00 | R$ 1.250,00 |
| **Viagem Internacional** | 24 meses | R$ 20.000,00 | R$ 795,00 |
| **Independência Financeira (R$ 5k/mês)** | 180 meses | R$ 1.500.000,00 | R$ 3.820,00 |
```
