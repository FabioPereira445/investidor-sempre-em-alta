---
name: anamnese-financeira
description: Use quando o usuário quiser fazer o diagnóstico da sua vida financeira, calcular o total histórico ganho e gasto, taxa de conversão em patrimônio e ativos, ou mapear hábitos financeiros.
---

# Skill: Anamnese Financeira

## Objetivo
Entregar um raio-X completo da vida financeira histórica do investidor, diagnosticando quanto dinheiro passou por suas mãos, quanto virou patrimônio e quanto virou ativos geradores de renda passiva, identificando gargalos e definindo um plano comportamental de mudança.

## Princípio
Quem não sabe de onde veio não sabe para onde vai. A maioria das pessoas avalia sua vida financeira apenas pelo salário do mês, ignorando que já receberam centenas de milhares (ou milhões) de reais e transformaram quase tudo em passivos ou gastos efêmeros. O primeiro passo da metodologia é a conscientização pelo choque de realidade.

## Processo

### Passo 1 - Coleta de Dados Históricos
Solicitar ao investidor:
- Idade atual e idade em que começou a trabalhar.
- Renda mensal líquida média por ciclo profissional.
- Bens acumulados (imóveis, veículos, contas bancárias, investimentos).
- Gastos mensais médios atuais e dívidas ativas.

### Passo 2 - Cálculo das Variáveis Centrais
1. **Total Histórico Recebido ($A$)**: Soma de todos os salários e rendimentos recebidos na vida.
2. **Patrimônio Total Acumulado ($B$)**: Soma do valor de mercado de todos os bens e investimentos atuais.
3. **Total Gasto na Vida ($C$)**: $C = A - B$.
4. **Média Mensal Histórica de Gastos**: $\frac{C}{\text{Total de meses trabalhados}}$.
5. **Taxa de Conversão em Patrimônio**: $\frac{B}{A} \times 100$.
6. **Ativos Geradores de Renda ($D$)**: Investimentos reais que geram dividendos ou juros (excluindo carro e casa própria).
7. **Taxa de Conversão em Ativos**: $\frac{D}{A} \times 100$ (Meta do método: $\ge 10\%$).

### Passo 3 - Auditoria de Passivos e Comportamento
- Listar custos anuais invisíveis com manutenção de bens de consumo (IPVA, seguro, IPTU, depreciação).
- Aplicar o Questionário de Hábitos (autoimagem sobre dinheiro, controle de impulsos e alinhamento familiar).

### Passo 4 - Emissão do Plano de Virada
Apresentar a prescrição financeira com metas imediatas de corte de ralos financeiros e aumento da taxa de conversão em ativos.

## Regras da skill
- Nunca julgar ou constranger o usuário pelos números do passado.
- Excluir estritamente veículos de uso pessoal e imóvel de residência própria do cálculo dos Ativos ($D$).
- A meta mandatória para aprovação da saúde financeira é Taxa de Conversão em Ativos $\frac{D}{A} \ge 10\%$.

## Exemplo de saída esperada
```markdown
### Raio-X Financeiro do Investidor
- **Total Histórico Ganho (A):** R$ 420.000,00
- **Patrimônio Acumulado (B):** R$ 55.000,00
- **Total Gasto na Vida (C):** R$ 365.000,00 (86,9%)
- **Ativos Geradores de Renda (D):** R$ 23.000,00
- **Taxa de Conversão em Ativos (D/A):** 5,48% (Abaixo da meta de 10%)

**Diagnóstico:** Para cada R$ 100 ganhos, apenas R$ 5,48 foram direcionados para construir sua liberdade financeira. Vamos ajustar sua esteira para atingir a meta de 10% nos próximos 12 meses.
```
