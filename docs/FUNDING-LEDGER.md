# 📒 FUNDING-LEDGER.md — Registro de Escopos, Custos e Fontes

**Versão:** 2.0 · **Snapshot:** 2026-10-30

> Este ledger evita dupla cobrança e torna explícita a relação entre módulo, entregável, custo, fonte de capital e evidência. Um repositório pode conter múltiplos escopos financiáveis; cada despesa precisa ter alocação identificável.

## 1. Regras de integridade

1. Cada work package recebe um identificador e critérios de aceite.
2. Cada custo direto recebe um allocation ID e uma única fonte de financiamento.
3. Custos compartilhados são rateados por regra documentada e aprovada.
4. Grant, bounty, crowdfunding, investimento e receita comercial são mecanismos diferentes.
5. Co-financiamento só ocorre quando os termos de todos os financiadores permitem e a alocação é divulgada.
6. Não se reivindica impacto retroativo sem evidência e programa ativo que o aceite.
7. Recompensa, token, reputação e autoria são registros distintos.

## 2. Portfólio de escopos

| Código | Módulo | Classe | Fonte-alvo | Status de trabalho | Escopo exclusivo / evidência pendente |
|---|---|---|---|---|---|
| FCL-01 | Farcaster Commons Lab / IPIT | Bem público + pesquisa experimental | Gitcoin, Giveth, crowdfunding comunitário | Experimento a instrumentar | Um desafio público, conversão conversa→PR, revisão independente e relatório |
| VC-01 | ValueCurator / ProofGate / KAIROS | Infraestrutura aberta + possível produto comercial | Solana Foundation, Superteam Earn, Colosseum | Protótipo Devnet descrito no landscape | SDK/policy gate aberto, testes, threat model e demonstração reproduzível |
| COMP-01 | Compilatum / Promptcraft | Ferramenta OSS | Ethereum ESP, Gitcoin | A delimitar | Extrair um módulo independente com licença, CI, docs e usuário externo |
| DATA-01 | Lakehouse / Oracle | Infraestrutura de dados | The Graph, Filecoin, Interchain | Integração específica pendente | Um adapter/subgraph/pipeline funcional e métricas de uso |
| PIX-01 | PixelCoin / funding rails | Pesquisa/protótipo | Gitcoin, crowdfunding; SCF condicional | Pesquisa/protótipo | Problema de usuário, direitos do instrumento e experimento não especulativo |
| AROS-01 | Prompt Audiofeedback / AROS | Pesquisa aplicada | Editais científicos, saúde digital, pilotos institucionais | Fora da trilha primária Web3 | Protocolo de pesquisa, privacidade, validação e limites de alegações |

## 3. Registro de alocação (preencher antes de submeter)

| Allocation ID | Work package | Cost item | Amount / currency | Funding source | Shared-cost rule | Evidence / invoice | Status |
|---|---|---|---:|---|---|---|---|
| ALLOC-001 | FCL-01 | A definir | — | A definir | Não aplicável até orçamento | — | DRAFT |
| ALLOC-002 | VC-01 | A definir | — | A definir | Não aplicável até orçamento | — | DRAFT |
| ALLOC-003 | COMP-01 | A definir | — | A definir | Não aplicável até orçamento | — | DRAFT |
| ALLOC-004 | DATA-01 | A definir | — | A definir | Não aplicável até orçamento | — | DRAFT |

Do not submit placeholder values as a budget. Replace each row with a real cost estimate and a named source before application.

## 4. Correções de contexto em relação ao ledger anterior

- Optimism Retro Funding não deve ser tratado como fonte prospectiva garantida; o landscape de 2026-10-30 registra a pausa após Season 7. Governance Fund é uma trilha separada.
- O antigo Arbitrum Questbook domain-grants está marcado como concluído; verificar programas atuais da Foundation.
- Colosseum é hackathon/aceleradora/investimento, não grant genérico.
- O ValueCurator pode ter componentes abertos e comerciais; não atribuir automaticamente o custo integral do produto a um grant de public goods.
- Não carregar taxas, percentuais, valores de pedido ou orçamento antigo sem confirmar que pertencem à versão técnica atual e ao escopo específico.

## 5. Ligação com GrantOS

- [Operating Model](GRANTOS-OPERATING-MODEL.md)
- [Project × Funding Map](PROJECT-FUNDING-MAP.md)
- [Microtask Market](MICROTASK-MARKET.md)
- [Grant Landscape](GRANT-LANDSCAPE-2026-10.md)

> **Regra de ouro:** nenhuma candidatura sai sem escopo, orçamento, allocation ID, critério de aceite, evidência esperada e verificação oficial da elegibilidade.
