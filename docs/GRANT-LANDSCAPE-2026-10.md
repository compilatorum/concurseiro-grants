# 🌐 Grant Landscape & Funding Strategy — Compilatorum

**Snapshot:** 2026-10-30  
**Purpose:** mapear fontes de financiamento descentralizado e associar cada mecanismo aos ativos, experimentos e linhas de pesquisa do Compilatorum.  
**Status:** inteligência estratégica; não constitui confirmação de elegibilidade nem promessa de rodada aberta.

> **Tese:** o portfólio não deve depender de um único grant. Deve converter trabalho em evidências reutilizáveis e distribuir cada entregável pelo mecanismo de capital adequado.

## 1. Taxonomia: mecanismos não são intercambiáveis

| Mecanismo | O que remunera | Melhor uso |
|---|---|---|
| Direct / milestone grant | Entregáveis futuros, orçamento e marcos | MVP, infraestrutura, pesquisa aplicada |
| RFP / wishlist | Resposta a uma lacuna definida pelo ecossistema | Propostas estreitas e alinhadas a prioridades |
| Retroactive funding | Impacto já demonstrado | OSS usado por terceiros, adoção, documentação e bens públicos |
| Quadratic funding (QF) | Apoio comunitário distribuído + matching | Projetos públicos com comunidade mobilizável |
| Bounty / microtask | Tarefa verificável e delimitada | Issues, testes, integrações, docs, adapters |
| Hackathon / accelerator | Protótipo, demonstração, tração e potencial de negócio | ValueCurator, apps e experiências onchain |
| Donations / crowdfunding | Convicção de apoiadores | Experimentos públicos, pesquisa e commons |
| Ecosystem investment | Potencial comercial, crescimento e retorno | Produtos SaaS, fintech e infraestrutura comercial |

## 2. Landscape priorizado

### A. Primeira linha — aderência alta

| Fonte | Mecanismo / foco | Fit Compilatorum | Recomendação e cautela |
|---|---|---|---|
| **Ethereum Foundation — Ecosystem Support Program (ESP)** | Grants, wishlist, RFPs, office hours; infraestrutura, pesquisa, tooling e recursos comunitários OSS | **Muito alto:** Promptcraft, Lakehouse, SLM, Compilatum, Oracle, Knowledge Weaver, PixelCoin como tooling aberto | Preparar propostas independentes por lacuna concreta. O programa exige outputs abertos; grants pagos em ETH e onboarding/KYC. Na checagem de 30/10, não havia RFP nem wishlist ativos, mas há office hours e canal geral. |
| **Gitcoin Grants** | Rodadas sazonais, QF, deep funding e community rounds | **Muito alto:** Compilatorum Commons, Promptcraft, PixelCoin, Lakehouse, Farcaster Commons Lab | Priorizar domínios de Developer Tooling & Infrastructure, Interop/Analytics e Public Goods R&D quando houver rodada compatível. Não pressupor que toda rodada esteja aberta. |
| **Solana Foundation Grants & Funding** | Grants por milestones, convertible grants para bens públicos com componente comercial e RFPs | **Muito alto:** ValueCurator, ProofGate/KAIROS, agentes financeiros, oráculos e tooling | Uma das rotas mais fortes porque ValueCurator já tem starterkit público e deployment Devnet. Formular o pedido em torno de segurança de execução de agentes, policy gates, oracle integrity e SDK reutilizável. |
| **Superteam Earn** | Bounties, grants patrocinados e oportunidades para builders Solana | **Alto:** ValueCurator, Farcaster/Solana integrations, PixelCoin | Monitorar tarefas patrocinadas e grants com escopo explícito; usar como trilha de caixa e prova de execução, não como grant institucional garantido. |
| **Colosseum** | Hackathons, aceleradora e investimento no ecossistema Solana | **Muito alto:** ValueCurator e micro-venture builder | Tratar como canal de validação, distribuição e potencial investimento, não como grant puro. Reaproveitar protótipo, métricas e demonstração. |
| **Stellar Community Fund (SCF)** | Build Track: Open, Integration e RFP; até US$150 mil em XLM conforme o programa | **Alto:** ValueCurator, PixelCoin, ReFi, pagamentos e funding rails | Candidato concreto se houver integração Stellar real e caso de uso transfronteiriço/pagamentos. SCF #46: página oficial indicava submissão de interesse até 9 nov. 2026; confirmar critérios e convite antes de investir esforço. |

### B. Segunda linha — alta aderência temática, mas depende de escopo/ecossistema

| Fonte | Mecanismo / foco | Fit Compilatorum | Recomendação e cautela |
|---|---|---|---|
| **Arbitrum Foundation Grants** | Grants para dApps, infraestrutura e tooling; programas temáticos | Oracle, DAO, Lakehouse, ValueCurator | A página oficial lista programas ativos, incluindo segurança e stablecoin growth. Aplicar somente com deployment/integração Arbitrum e milestones específicos. O antigo programa Questbook de domain grants está marcado como concluído. |
| **Optimism Collective** | Governance Fund e histórico de Retro Funding | Compilatum, Promptcraft, libraries e dev tooling | Manter como observatório de missões e grants do Governance Fund. **Não projetar receita de Retro Funding agora:** a atualização orçamentária Year 4 informa pausa do programa após Season 7. |
| **Sui Foundation** | Grants, RFPs, pesquisa acadêmica e programas de builders | Oracle, agentes, ferramentas de dados, SLM | Entrar apenas se houver tese técnica nativa Sui; acompanhar academic research awards e programas de builders. |
| **Interchain Foundation / Cosmos** | Grants, RFPs e desenvolvimento do stack interchain | Lakehouse, Oracle, interoperabilidade, governança | Bom fit para conectores, indexação, analytics, interoperabilidade e infraestrutura de dados multi-chain. |
| **The Graph Foundation** | Grants para indexação, subgraphs e dados Web3 | Lakehouse, Oracle, analytics e dashboards | Alta aderência se o entregável for subgraph, indexação ou ferramenta de dados usada por outros builders. |
| **Uniswap Foundation** | Grants e apoio a tooling/segurança/Unichain | ValueCurator, DeFi risk tooling, analytics | Só avançar com contribuição concreta para Uniswap v4, Unichain, segurança ou developer tooling. |
| **Filecoin / Protocol Labs ecosystem** | Grants e programas para infraestrutura de dados, armazenamento e bens públicos | Lakehouse, Corpora, Knowledge Weaver, arquivo de evidências | Explorar armazenamento verificável, datasets abertos e infraestrutura de conhecimento. |
| **Zcash Community Grants / ZF** | Grants comunitários para privacidade e infraestrutura | SLM, ferramentas de privacidade, pesquisa | Fit condicional: precisa haver contribuição real a privacidade, segurança ou tooling Zcash. |
| **OpenSats** | Grants globais para Bitcoin OSS, long-term support e reembolso de compute para pesquisa de segurança | SLM/Promptcraft apenas se houver contribuição Bitcoin/FOSS; tooling de segurança | Não é fonte genérica para IA/Web3. Forte somente com entregável Bitcoin, Nostr ou segurança OSS; candidatura global. |
| **Aleo / Starknet / ZKsync / Zcash** | Grants e programas de ecossistema orientados a ZK/privacy | SLM, Oracle, identity/privacy, data provenance | Acompanhar RFPs; não pulverizar candidaturas sem protótipo ou necessidade específica de ZK. |
| **Rootstock Collective / Stacks / Algorand xGov** | Grants comunitários, bounties ou funding retroativo por ecossistema | PixelCoin, funding rails, Oracle e ferramentas | Rotas oportunísticas se houver integração e comunidade ativa. Validar janela, KYC, regras e disponibilidade no ciclo. |

### C. Capital comunitário e infraestrutura de funding

| Fonte / ferramenta | Papel | Uso recomendado |
|---|---|---|
| **Giveth** | Doações cripto e rodadas QF | Página pública para Compilatorum Commons e projetos de impacto; mobilizar apoiadores reais, sem fabricar comunidade. |
| **Octant** | Distribuição de rewards de staking para bens públicos, via épocas | Monitorar próximas épocas; a rodada de 2026 listada nos agregadores estava encerrada. |
| **Hypercerts** | Representação de impacto e evidências financiáveis | Registrar claims de impacto de microcontribuições, sem tratar o certificado como grant ou liquidez garantida. |
| **Karma GAP** | Acompanhamento de grantees e milestones | Usar como referência de prestação de contas e transparência. |
| **Open Source Observer** | Analytics de impacto OSS | Medir dependentes, adoção, uso e contribuições para retrofunding e grants. |
| **Drips / Tea Protocol** | Funding contínuo e incentivos para dependências OSS | Direcionar apoio a bibliotecas e mantenedores; investigar elegibilidade e adoção antes de depender da receita. |
| **Juicebox / Allo Protocol** | Infraestrutura de tesouraria e alocação programável | Experimentos de crowdfunding e matching; não confundir infraestrutura com capital disponível. |
| **Dework / Layer3 / POIDH** | Bounties, quests e provas de conclusão | Dividir roadmap em tarefas pequenas, com critérios de aceite, recompensa e prova pública. |

## 3. Mapeamento projeto × fonte

Legenda: **A** = prioridade alta; **B** = oportunidade condicional; **C** = monitorar / baixa prioridade no momento.

| Projeto / cluster | Fontes prioritárias | Mecanismo ideal |
|---|---|---|
| **ValueCurator / ProofGate / KAIROS** | Solana Foundation, Superteam Earn, Colosseum, Gitcoin, Stellar SCF, Arbitrum | Milestone grants + hackathon/accelerator + bounties |
| **Farcaster Commons Lab / concurseiro-grants / IPIT** | Gitcoin, Giveth, Octant, Hypercerts, Optimism Governance Fund, Artizen | QF + crowdfunding + retroactive impact |
| **Compilatum / monorepo / harness engineering** | Ethereum ESP, Gitcoin, Optimism (quando reabrir), Arbitrum, Superteam | OSS tooling grant + bounty + retrofunding |
| **Promptcraft / Knowledge Weaver / Corpora** | Ethereum ESP, Gitcoin, Filecoin, The Graph, Interchain | Research/tooling grant + QF |
| **Oracle / AIAA / DAO / Governaut** | Ethereum ESP, Arbitrum, Interchain, Sui, Gitcoin | Infra grant + RFP + milestones |
| **Lakehouse / data & analytics / cadCAD Explorer** | Ethereum ESP, The Graph, Filecoin, Interchain, Gitcoin | Data infrastructure grant + RFP |
| **PixelCoin / eidos-tokenization / funding rails** | Gitcoin, Giveth, Stellar SCF, Arbitrum, Colosseum | QF + hackathon + integration grant |
| **SLM / pesquisa de avaliação de modelos** | Ethereum ESP (se houver conexão com ecossistema), OpenSats (apenas segurança Bitcoin), Sui academic research, chamadas científicas externas | Research grant + compute reimbursement |
| **Prompt Audiofeedback / AROS** | Editais de ciência, saúde digital, inovação e pesquisa aplicada fora do universo Web3 | Pesquisa aplicada / parceria / piloto; baixa prioridade para grants cripto |
| **Regenerativo / ReFi / geodados** | Gitcoin, Giveth, Stellar SCF, Filecoin, ReFiDAO e fundos bioregionais | QF + impact funding + pilotos |

## 4. O que a checagem de 30/10/2026 muda na estratégia

1. **Ethereum ESP:** canal permanente de relacionamento e apoio, mas sem wishlist/RFP ativos na página consultada. Preparar proposta e usar office hours; não tratar como chamada aberta imediata.
2. **Optimism Retro Funding:** pausa oficial após Season 7. Oportunidades do Governance Fund são uma trilha distinta e devem ser verificadas por missão.
3. **Arbitrum Questbook:** o antigo domínio de grants está concluído; a página da Foundation lista outras iniciativas ativas. Não reciclar candidatura antiga sem conferir o programa atual.
4. **Stellar SCF:** oportunidade com janela próxima; verificar imediatamente o SCF #46 e sua etapa de manifestação de interesse.
5. **OpenSats:** candidaturas globais, mas escopo Bitcoin/FOSS é requisito material.
6. **Gitcoin:** GG24 apresenta domínios específicos de developer tooling, interoperabilidade, analytics e public goods R&D; selecionar a rodada adequada em vez de uma candidatura genérica.
7. **Octant:** manter no radar, sem presumir que a época listada esteja aceitando aplicações.

## 5. Arquitetura operacional: GrantOS

Cada oportunidade deve virar um nó estruturado:

- `Funder`: organização, ecossistema, URL oficial e mecanismo.
- `Program`: rodada, tese, status, janela, ticket, rede e geografia.
- `Eligibility`: pessoa/equipe/empresa, KYC, jurisdição, licença, token e restrições.
- `Project`: repositório, owner, dependências e estágio.
- `Milestone`: escopo, custo, prazo, aceite e evidência.
- `Impact`: usuários, dependentes, transações, downloads, contribuições e externalidades.
- `Application`: narrativa, orçamento, anexos, responsável e status.
- `Award`: valor, moeda, vesting, obrigações, prestação de contas e riscos.

### Score de priorização

[
S = 0.25F + 0.20E + 0.20P + 0.15T + 0.10R + 0.10C
]

Onde cada variável é normalizada de 0 a 5:

- **F** fit estratégico e temático;
- **E** evidência e prontidão técnica;
- **P** probabilidade/clareza de elegibilidade;
- **T** timing e janela de submissão;
- **R** retorno líquido em relação ao esforço;
- **C** valor de composição (reputação, integração e novas rotas).

Penalizar separadamente custo de compliance, KYC, obrigações de token e dependência de uma chain. Não somar esses riscos como se fossem benefícios.

## 6. Pipeline recomendado: 90 dias

### Onda 1 — monetizar evidências existentes (0–15 dias)
- Montar um pacote de evidências para ValueCurator: Devnet, SDK, testes, arquitetura de policy gate e demonstração.
- Verificar a janela SCF #46 e oportunidades atuais de Superteam Earn.
- Preparar 2 propostas distintas para Gitcoin: (i) tooling/infra; (ii) Farcaster Commons / public goods.
- Fazer triagem de bounties pequenos que produzam commits e referências verificáveis.

### Onda 2 — transformar infraestrutura em bens públicos (15–45 dias)
- Delimitar um módulo open source de Promptcraft/Compilatum com usuários externos e documentação.
- Definir uma proposta de dados/indexação para The Graph, Filecoin ou Interchain, conforme stack real.
- Publicar métricas e relatórios de impacto no Farcaster Commons Lab.
- Fazer office hours com Ethereum ESP e ajustar a proposta à wishlist/RFP quando surgir uma lacuna compatível.

### Onda 3 — funding composto (45–90 dias)
- Rodar crowdfunding/QF para o commons com apoiadores orgânicos.
- Empacotar entregáveis já realizados como evidência retroativa para programas que efetivamente estejam ativos.
- Converter módulos comerciais em pilotos, API/SaaS, suporte ou licenciamento; não financiar indefinidamente produto comercial com grant de bem público.

## 7. Princípios de candidatura

1. **Uma candidatura = uma lacuna + um entregável.** Evitar “financiar o Compilatorum” em abstrato.
2. **Separar bem público de IP comercial.** O grant financia a parte aberta, reutilizável e acessível; o produto comercial pode monetizar serviços, hospedagem, suporte e módulos adicionais sem prometer exclusividade sobre o output financiado.
3. **Onchain quando necessário, não por decoração.** Explicar por que a cadeia, contratos, attestations ou pagamentos são necessários ao problema.
4. **Evidência antes de narrativa.** Demo, testes, usuários, dependentes, releases e documentação reduzem risco percebido.
5. **Não confundir status de agregador com status oficial.** Confirmar sempre na página do financiador, especialmente prazos, elegibilidade e disponibilidade.
6. **Sem grant farming.** Não duplicar custos ou reivindicar o mesmo entregável em dois financiadores sem transparência e autorização.

## 8. Fontes e links oficiais / de monitoramento

- Ethereum Foundation ESP — https://esp.ethereum.foundation/
- ESP applicants — https://esp.ethereum.foundation/applicants
- ESP wishlist — https://esp.ethereum.foundation/applicants/wishlist
- ESP RFPs — https://esp.ethereum.foundation/applicants/rfp
- ESP funded projects — https://esp.ethereum.foundation/funded-projects
- Gitcoin Grants — https://gitcoin.co/program
- Gitcoin Grants 24 — https://grants.gitcoin.co/
- Solana Foundation Grants & Funding — https://solana.org/grants-funding
- Superteam Earn — https://earn.superteam.fun/
- Colosseum — https://www.colosseum.org/
- Stellar Community Fund — https://communityfund.stellar.org/awards
- Arbitrum Grants — https://arbitrum.foundation/grants
- Optimism Grants — https://gov.optimism.io/c/grants/87
- Sui — https://www.sui.io/grants
- Interchain Foundation — https://interchain.io/
- The Graph Grants — https://thegraph.com/grants/
- OpenSats — https://opensats.org/apply
- Giveth — https://giveth.io/
- Octant — https://octant.app/
- Grants.watch — https://grants.watch/programs?view=cadence&wire=crypto
- Web3Grant — https://www.web3grant.com/grants
- Ethereum.org grant directory — https://ethereum.org/community/grants

---

## Síntese executiva

**Prioridade imediata:** ValueCurator → Solana Foundation / Superteam / Colosseum; Gitcoin → Compilatorum Commons + developer tooling; Stellar SCF → somente se a integração Stellar for real e o prazo for viável.

**Prioridade estrutural:** Ethereum ESP para tooling e pesquisa OSS; The Graph/Filecoin/Interchain para dados e interoperabilidade; Giveth/Hypercerts/Open Source Observer para medir e financiar impacto.

**Não priorizar agora:** candidaturas genéricas a Optimism Retro Funding (pausado), Questbook Arbitrum (programa antigo concluído), OpenSats sem entrega Bitcoin, ou grants de saúde para AROS sem aderência temática.

> **Filosofema:** *Grant não é salário para uma ideia; é capital condicionado para produzir um bem verificável. O portfólio aprende a transformar cada entrega em evidência, cada evidência em reputação e cada reputação em novas opções de capital.*
