# Skills do MAGAR Finance Agent

Este diretório contém todas as habilidades modulares (**Skills**) que compõem a esteira de processos do método *Investidor Sempre em Alta*. Cada skill é autocontida e orientada a uma etapa específica da jornada do investidor.

---

## Como criar uma nova skill

1. **Crie uma pasta em `skills/`** com o nome descritivo em kebab-case (ex: `skills/minha-nova-skill`).
2. **Adicione um arquivo `SKILL.md`** seguindo rigorosamente o template do Padrão DIO:
   - Cabeçalho YAML com `name` e `description` (especificando um gatilho claro de intenção).
   - Seções:
     - `# Skill: [Nome da Skill]`
     - `## Objetivo` (O que entrega)
     - `## Princípio` (A filosofia por trás)
     - `## Processo` (Passo a passo numerado)
     - `## Regras da skill` (Travas e limites)
     - `## Exemplo de saída esperada` (Formato concreto da resposta)
3. **Registre a nova skill em dois lugares obrigatórios**:
   - Na tabela de Skills do [`AGENTS.md`](../AGENTS.md) (para que o harness ative a skill por intenção).
   - Na tabela de Skills do [`README.md`](../README.md) (para documentação aos usuários humanos).
