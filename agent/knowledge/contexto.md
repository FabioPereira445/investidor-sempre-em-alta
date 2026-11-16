# Contexto de Domínio: Metodologia Investidor Sempre em Alta (MAGAR)

Este documento centraliza as premissas conceituais, fórmulas matemáticas e regras regulatórias do método Vinícius Mariño utilizadas pelo agente.

---

## 1. A Estrutura MAGAR

A carteira MAGAR é uma estratégia de Alocação de Ativos descorrelacionados desenhada para gerar rentabilidade e proteção em qualquer ciclo econômico:
- **M - Moeda / Renda Fixa**: Reserva de Liquidez e ajuste de volatilidade em R$ (Tesouro Selic e Fundo DI Taxa Zero) + Trava de poder de compra (Tesouro IPCA+ longo via Marcação a Mercado).
- **A - Ações Brasil**: Empresas com lucros consistentes e dividendos perenes (foco em setores perenes com teto de 20% por setor).
- **G - Gold / Ouro**: Reserva de valor milenar e antiação descorrelacionada com a bolsa. Deve possuir **dupla exposição cambial** (ouro cotado em dólar sem hedge).
- **A - Ativos Reais (FIIs)**: Renda passiva mensal isenta de IR utilizada como combustível de rebalanceamento. Paridade em percentual com a fatia de Antiações.
- **R - Renda Internacional**: Dolarização soberana do patrimônio via ETF de índice global (`VOO`) e ouro internacional (`GLD`), protegendo contra risco político brasileiro e japonização econômica.

---

## 2. Fórmulas e Princípios Quantitativos

### A. Equação de Fisher (Rentabilidade Real Líquida)
$$(1 + i_{\text{nominal líquida}}) = (1 + r_{\text{real}}) \times (1 + \text{inflação}) \implies r_{\text{real}} = \frac{1 + i_{\text{líquida}}}{1 + \text{IPCA}} - 1$$

### B. Fórmula VCP (Velocidade de Construção Patrimonial)
$$\text{VCP} = \text{VI} \times R \times T$$
Onde $\text{VI}$ é o Valor Investido (Aporte), $R$ é a Rentabilidade Real e $T$ é o Tempo.

### C. Independência Financeira (Regra dos 300)
$$\text{Patrimônio Necessário} = \text{Custo de Vida Mensal Desejado} \times 300 = \frac{\text{Custo Anual}}{0,04}$$
Assume uma Taxa de Retirada Segura de $4\%$ a.a. acima da inflação.

### D. Dupla Exposição Cambial do Ouro
$$\text{Retorno em R\$} = (1 + \Delta_{\text{Ouro em US\$}}) \times (1 + \Delta_{\text{Dólar em R\$}}) - 1$$

### E. Assimetria de Perdas de Warren Buffett
$$\text{Ganho Necessário para Recuperação} = \frac{1}{1 - \text{Queda}} - 1$$
Demonstra que perdas severas demoram anos exponenciais para serem recuperadas (uma queda de $50\%$ exige ganho de $+100\%$; queda de $70\%$ exige $+233\%$).

### F. Marcação a Mercado e Duration
$$PU = \frac{VNA}{(1 + r)^t}$$
Quando as taxas futuras caem, o preço unitário do título longo dispara. Quanto maior o prazo e menor o fluxo de cupons intermediários, maior a sensibilidade do preço (*Duration*).

---

## 3. Checklists de Filtragem

### A. Ações Brasil (Checklist de 6 Critérios)
1. **P/L**: $\le 15\text{x}$ (preferencialmente abaixo da média setorial).
2. **P/VP**: $\le 2,5\text{x}$ (ou justificado por ROE alto).
3. **ROE**: $\ge 10\%$ a.a. (capacidade de rentabilizar o patrimônio líquido).
4. **Margem Líquida**: $\ge 10\%$ (vantagem competitiva e precificação).
5. **Dívida Líquida / EBIT**: $\le 2,5\text{x}$ (ou $\le 3,5\text{x}$ para elétricas perenes de concessão longa).
6. **EBIT > Lucro Líquido**: Confirma que o lucro vem da operação e não de artifícios contábeis ou ganhos não recorrentes.

### B. Classificação Setorial (Ações e FIIs)
- **Cruzeiro**: Navega bem em qualquer mar (Energia, Bancos, Saneamento, Seguros; Galpões Logísticos, Residenciais, Lajes AAA).
- **Lancha**: Acelera muito nos momentos bons, mas chacoalha nas ondas (Varejo, Shoppings, Construção Civil, Hotéis).
- **Barco Pirata**: **VETADOS** (Empresas estatais sem governança, empresas em recuperação judicial, FIIs de agências bancárias, hospitais, educacional, fundos de papel/CRIs e FoFs).

### C. Fundos Imobiliários (11 Critérios)
1. Dividend Yield atrativo frente aos pares.
2. $P/VP \le 1,10\text{x}$.
3. Liquidez média diária $\ge \text{R\$} 500\text{ mil/dia}$.
4. Previsibilidade histórica na distribuição.
5. Mandato de Renda ou Híbrido.
6. Segmentos: Logística, Shoppings, Lajes AAA ou Agro de terras.
7. Contratos: Maioria vencendo após 36 meses.
8. Exposição a CRIs/Papel $\le 20\%$ do PL.
9. Imóveis físicos: Mínimo 3 (multi-imóvel).
10. Inquilinos: Mínimo 3 (multi-inquilino).
11. Vacância física/financeira: Preferencialmente $\le 5\%$.

---

## 4. Legislação Tributária e Regulatória Vigente (2024–2026)

- **Investimentos no Exterior (Lei Federal nº 14.754/2023)**:
  - Extinção da isenção de R\$ 35 mil/mês e do carnê mensal GCAP.
  - Alíquota única de **$15\%$ sobre o ganho de capital líquido apurada na DAA** (Declaração de Ajuste Anual).
  - Permissão expressa para compensação de prejuízos em ativos no exterior.
  - Dividendos americanos retidos em $30\%$ pelo IRS na fonte, compensáveis no IRPF brasileiro.
- **Estate Tax dos EUA (Imposto sobre Herança)**:
  - Isenção de apenas **US\$ 60.000** para investidores não-residentes fiscais nos EUA (alíquota progressiva de até $40\%$ sobre o excedente). Conta conjunta JTWROS não extingue o imposto. Patrimônios acima de US\$ 300.000 exigem estudo de offshore ou ETFs irlandeses (UCITS).
- **Fundos Imobiliários (FIIs)**:
  - Isenção de proventos mensais para pessoa física desde que o fundo tenha **pelo menos 100 cotistas** (*atualização da Lei 14.754/2023*), cotas em Bolsa e o investidor detenha $< 10\%$ das cotas.
  - Ganho de capital na venda de cotas tributado em **$20\%$ via DARF Código 6015** com compensação de prejuízos passados.
