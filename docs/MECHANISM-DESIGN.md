# ⚙️ MECHANISM-DESIGN.md — Separação de Instrumentos & Sequência A–D

## 1. Três Instrumentos Distintos (Evitando Especulação Prematura)
Não utilizamos um único token para representar simultaneamente mérito, governança, acesso e dinheiro:

1. **Reputação (Off-chain / Attestation):** Histórico contextual de contribuições aceitas e revisadas.
2. **Créditos de Utilidade (Ledger Simulado):** Direito de solicitar análises, revisões técnicas ou execuções no laboratório.
3. **Token Transferível (Devnet / Testnet):** Ativo on-chain (`SPL Token-2022` na Solana Devnet / `ERC-1155` na Superchain Testnet) usado para testar liquidação, carteiras e regras programáticas.

## 2. Sequência de Experimentos (A → B → C → D)
- **Experimento A — Ledger de Contribuições:** Registra desafios, evidências, revisões e créditos simulados (sem movimentar ativos reais).
- **Experimento B — Token em Testnet/Devnet:** Ciclo end-to-end com `eidos-tokenization` e `valuecurator` na Devnet.
- **Experimento C — Recompensas Reais de Baixo Valor:** Apenas mediante orçamento validado e regras transparentes.
- **Experimento D — Mecanismo Econômico Avançado:** Mercados ou curvas apenas quando uma pergunta experimental específica exigir.
