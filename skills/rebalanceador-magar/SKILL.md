---
name: rebalanceador-magar
description: Use quando o usuário quiser definir os percentuais da sua carteira MAGAR, aplicar o Teste do Travesseiro, planejar a montagem da carteira do zero, migrar investimentos existentes ou calcular onde investir no mês sem vendas.
---

# Skill: Rebalanceador e Automatizador MAGAR

## Objetivo
Governar a arquitetura completa da carteira MAGAR, calibrando os percentuais ideais via Teste do Travesseiro e relação 3:1, coordenando a esteira sequencial de entrada e executando o rebalanceamento mensal inteligente sem gerar vendas tributáveis.

## Princípio
A Alocação de Ativos é a maior geradora de retorno de longo prazo. Em vez de adivinhar o mercado, o investidor adota um algoritmo mecânico: direciona novos aportes e 100% dos proventos para os ativos que ficaram para trás, comprando automaticamente na baixa e mantendo a carteira em equilíbrio.

## Processo

### Passo 1 - Dimensionamento da Carteira (Teste do Travesseiro)
1. **Renda Variável ($\text{RV}$)**: Definida pela tolerância psicológica do investidor à volatilidade de curto prazo.
2. **Renda Fixa ($\text{RF}$)**: $\text{RF} = 100\% - \text{RV}$.
3. **Distribuição Interna da RV (Relação 3:1)**:
   - $\% \text{ FIIs} = \% \text{ Antiações}$
   - $\% \text{ Ações} \approx 3 \times \% \text{ FIIs} = 3 \times \% \text{ Antiações}$
   - *Exemplo Clássico*: 50% Renda Fixa, 30% Ações Brasil, 10% FIIs, 10% Antiações.

### Passo 2 - Esteira de Entrada para Iniciantes (Começando do Zero)
Ordem estrita de montagem patrimonial:
```text
1. Pós-fixada (Reserva) -> 2. IPCA+ Longo -> 3. FIIs -> 4. Ações Brasil -> 5. Dólar & Ouro
```

### Passo 3 - Protocolo "Não Force a Barra" (Migração de Carteira)
1. Somar o patrimônio líquido total existente.
2. Desenhar a MAGAR Ideal como se estivesse começando do zero.
3. Auditar os ativos atuais contra os checklists dos módulos anteriores. Vender os reprovados.
4. Para ativos aprovados com excesso desproporcional, vender o excedente para equilibrar a carteira.

### Passo 4 - Algoritmo de Rebalanceamento Mensal por Aporte
1. Calcular o Patrimônio Total Futuro = Saldo Atual + Novo Aporte + Dividendos Recebidos.
2. Calcular o Valor Alvo de cada classe: $\text{Alvo}_i = \text{Patrimônio Futuro} \times \%_{\text{Meta}_i}$.
3. Calcular a Defasagem: $\text{Gap}_i = \text{Alvo}_i - \text{Saldo Atual}_i$.
4. Alocar 100% do capital exclusivamente nas classes com **maior Gap positivo**, sem realizar nenhuma venda.

## Regras da skill
- Nunca realizar vendas no rebalanceamento mensal; usar exclusivamente novos aportes e proventos reinvestidos.
- Vendas parciais só são admitidas no rebalanceamento estrutural periódico (a cada 3, 6 ou 12 meses) se um ativo atingir proporções de bolha.
- Paridade obrigatória: percentual de FIIs deve ser idêntico ao de Antiações.

## Exemplo de saída esperada
```markdown
### Boletim Mensal de Rebalanceamento MAGAR
- **Patrimônio Total Atual:** R$ 100.000,00
- **Aporte + Dividendos Disponíveis:** R$ 5.000,00
- **Diagnóstico de Gaps:**
  - Renda Fixa (Meta 50%): Saldo R$ 46.000 -> Gap: +R$ 6.500
  - Ações (Meta 30%): Saldo R$ 33.000 -> Gap: -R$ 1.500 (Acima da meta)
  - FIIs (Meta 10%): Saldo R$ 12.000 -> Gap: -R$ 1.500 (Acima da meta)
  - Antiações (Meta 10%): Saldo R$ 9.000 -> Gap: +R$ 1.500
- **Ordem de Aporte:** Injetar R$ 3.500 em Renda Fixa e R$ 1.500 em Antiações (Zero vendas necessárias).
```
