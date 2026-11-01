# 🧭 Demand-Driven Grant Stacking Map — 2026-11-01

**Snapshot:** 2026-11-01 (UTC)  
**Owner:** Compilatorum / GrantOS  
**Purpose:** inverter a captação: identificar problemas que ecossistemas já declararam prioritários ou para os quais há mecanismos de capital e adaptar módulos do portfólio a entregas verificáveis.  
**Natureza:** inteligência de oportunidades; não é confirmação de elegibilidade, aprovação, orçamento reservado ou aconselhamento jurídico/financeiro.

> **Tese:** não vender “o ecossistema inteiro” a cada financiador. Resolver uma lacuna específica, com um módulo pequeno, interoperável, aberto quando exigido e mensurável; depois compor módulos complementares sem duplicar custos.

## 1. Regra de leitura: problema financiado ≠ dinheiro garantido

Classificar cada oportunidade em quatro dimensões independentes:

- **Need:** existe uma lacuna, RFP, wishlist, problema de protocolo ou categoria de impacto explicitamente reconhecida?
- **Capital:** há grant, bounty, audit subsidy, matching, accelerator ou canal de investimento identificado?
- **Window:** a chamada está aberta, rolling, anunciada, pausada, encerrada ou ainda precisa de confirmação?
- **Fit:** há um entregável Compilatorum que resolve a lacuna sem inventar uma integração ou comunidade?

Status usados: `OPEN-VERIFIED`, `ROLLING`, `UPCOMING`, `MONITOR`, `PAUSED`, `CLOSED`, `CONDITIONAL`. Toda oportunidade deve guardar URL oficial, data de verificação e evidência do status.

## 2. Mapa de problemas do ecossistema → módulos Compilatorum

| Problema recorrente / demanda do ecossistema | Solução concreta que podemos oferecer | Repositórios / ativos | Evidência mínima para proposta | Rotas de capital |
|---|---|---|---|---|
| **Execução insegura por agentes autónomos:** IA pode recomendar swaps/ações com dados obsoletos, slippage, autoridade excessiva ou chaves comprometidas | Policy gate determinístico, validação de oráculo/quote, limites, segregação de autoridade, fail-closed, testes adversariais e SDK reutilizável | `value-curator`, `vc`, `oracle`, `DAO`, `harness-engineering` | Devnet demo, testes de stale feed/deviation/slippage, threat model, métricas de bloqueio seguro, integração real | Solana Foundation; Superteam; Colosseum; Uniswap security/tooling; Arbitrum se deploy nativo |
| **Déficit de segurança em DeFi e smart contracts:** auditoria cara, bugs de integração, ausência de threat model e test harness | Security harness, invariants, fuzz/property tests, threat-model templates, audit-readiness e reprodutibilidade | `value-curator`, `harness-engineering`, `cognitiv`, `neurosimbolic-trader` | Testes reproduzíveis, cobertura, relatório de risco, revisão externa | Uniswap Foundation Security Fund / audit subsidies; Solana ecosystem; Arbitrum; Zcash apenas se privacidade/stack Zcash |
| **Fragmentação de dados onchain e baixa qualidade de analytics:** falta indexação, histórico, lineage e dados prontos para decisão | Data adapters, subgraphs/substreams, pipelines Bronze/Silver/Gold, dashboards e datasets versionados | `lakehouse`, `oracle`, `knowledge-weaver`, `Corpora`, `invest-os`, `pixelcoin` | Um pipeline real em produção/testnet, dataset documentado, latência/completude, consumidor identificado | The Graph; Filecoin; Solana; Arbitrum; Gitcoin; Ethereum ESP quando houver wishlist |
| **Armazenamento e preservação de dados públicos:** dependência de storage centralizado, dados sem integridade ou sem recuperação | Exportação de artefatos, content addressing, backups verificáveis, storage/retrieval adapters e corpus aberto | `lakehouse`, `Corpora`, `knowledge-weaver`, `compilatum`, `InternaResources` | Teste de persistência/recuperação, hashes, custo por GB, política de dados e demo de retrieval | Filecoin Foundation Open Grants / FIL Builder Next Step; Gitcoin; ESP quando houver item ativo |
| **DX ruim e fragmentação de ferramentas para builders:** APIs dispersas, setup frágil, documentação incompleta, workflows não reprodutíveis | CLI/SDK, templates, workflow compiler, documentação, harness e starterkits de integração | `promptcraft`, `omni-laboratory`, `cognitiv`, `compilatum`, `harness-engineering`, `storybook-genui`, `uml-navigator` | Instalação em ambiente limpo, quickstart funcional, testes, issue externa resolvida, usuário independente | Ethereum ESP (quando wishlist/RFP existir); Solana; Filecoin; The Graph; Gitcoin; Arbitrum |
| **Agentes de IA pouco observáveis e sem proveniência:** outputs sem rastreabilidade, contexto, avaliação ou replay | Provenance DAG, eval harness, logs, workflow traces, policy boundary e dataset/eval packs | `omni-laboratory`, `promptcraft`, `cognitiv`, `SLM`, `harness-engineering`, `oracle` | Trace reproduzível, benchmark, avaliação independente, demonstração de lineage | Solana agentic builder programs; Gitcoin; Ethereum ESP quando houver RFP; Filecoin para datasets |
| **Privacidade, segurança e autonomia de dados:** dados sensíveis e infra sem mecanismos de minimização/consentimento | Privacy-by-design, local-first processing, threat model, selective disclosure ou integração ZK somente quando necessária | `SLM`, `prompt-audiofeedback`, `lakehouse`, `oracle`, `cognitiv` | Data-flow map, teste de minimização, consentimento, threat model e prova de conceito ZK se aplicável | Zcash grants (somente contribuição real ao ecossistema); Aleo/ZK ecosystems; Ethereum security/privacy |
| **Adoção e interoperabilidade de stablecoins/pagamentos:** onboarding, UX, rampas, transferências e reconciliação | Pagamentos, funding rails, carteira/UX, reconciliação e integração cross-chain com caso de uso territorial/transfronteiriço | `value-curator`, `pixelcoin`, `sovereign-budget`, `invest-os`, `regenerativo`, `eidos-tokenization` | Fluxo real de pagamento, parceiro/usuário, custos, compliance map, testnet/mainnet integration | Stellar SCF; Solana; Arbitrum; Uniswap/Unichain conforme integração |
| **Transparência e avaliação de impacto de bens públicos:** financiadores não conseguem verificar uso, adoção, adicionalidade ou duplicidade | Evidence ledger, impact claims, allocation ledger, contribution provenance e dashboards públicos | `concurseiro-grants`, `IPIT`, `oracle`, `pixelcoin`, `invest-os`, `sovereign-budget` | Ledger auditável, metodologia de atribuição, evidências externas e regra anti-double-counting | Gitcoin; Giveth; Octant (quando houver época); Hypercerts como camada de evidência; Zcash retroactive apenas para trabalho já feito |
| **Coordenação de comunidades e contribuição aberta:** dificuldade de converter discussão em PRs, mantenedores e trabalho verificável | Farcaster-to-GitHub workflow, issue decomposition, contributor onboarding, review, reputation/evidence | `concurseiro-grants`, `IPIT`, `farcaster-nexus`, `DAO`, `governaut-os` | Piloto com usuários reais, issues abertas/aceitas, contributor retention e reuso externo | Gitcoin; Superteam bounties; community grants; Giveth/Allo |
| **Governança e alocação de capital pouco legíveis:** propostas, decisões e resultados não estão conectados | Governance OS, decision logs, budget allocation, milestone monitoring e mecanismo de feedback | `governaut-os`, `DAO`, `sovereign-budget`, `invest-os`, `concurseiro-grants` | Simulação ou DAO piloto, regras transparentes, audit trail e avaliação de participação | ArbitrumDAO (proposal path); Optimism Governance Fund (missões ativas); Gitcoin/Allo |
| **Financiamento de pesquisa e infraestrutura científica:** resultados dispersos, baixa reprodutibilidade e dificuldade de converter pesquisa em artefato | Research pipelines, dataset registry, experiment tracking, reproducible notebooks, open protocols | `prompt-audiofeedback`, `SLM`, `cadcad-explorer`, `cognitiv`, `lakehouse`, `Corpora` | Protocolo, baseline, resultados replicáveis, ética e limites explicitados | Zcash/academic calls quando tema elegível; Ethereum research; Filecoin; grants de universidades e fundações |
| **Biofeedback e tecnologias digitais centradas em privacidade:** necessidade de ferramentas acessíveis, locais e não diagnósticas | AROS Voice Kernel: features acústicas, baseline idiográfico, feedback autorregulatório, local-first e salvaguardas | `prompt-audiofeedback`, `SLM`, `omni-laboratory` | MVP executável, validação técnica, estudo de usabilidade, privacidade e disclaimers; sem alegações diagnósticas | Research/health-tech grants, universidades, inovação aberta; **não** forçar em grants cripto sem nexo real |
| **Finanças regenerativas e dados territoriais:** falta integração de dados geoespaciais, indicadores e mecanismos de alocação local | Geodata pipeline, indicadores auditáveis, simulação de cenários e budget allocation | `regenerativo`, `lakehouse`, `cadcad-explorer`, `sovereign-budget`, `oracle`, `invest-os` | Dataset territorial, parceiro local, baseline e metodologia de impacto | Stellar (pagamentos/casos de uso), Gitcoin/Giveth/Octant, climate/impact funders |
| **Tokenização sem direitos e mecanismos claros:** confusão entre reputação, créditos, recibos, direitos e instrumentos transferíveis | Registry de work packages, licença/IP, acceptance criteria, contribution receipts e política de transferência; começar sem token | `concurseiro-grants`, `pixelcoin`, `eidos-tokenization`, `IPIT`, `value-curator` | Modelo jurídico-operacional, piloto sem token, consentimento e reconciliação financeira | Research grants, Gitcoin/Allo, crowdfunding; grants de ecossistema só quando a integração for substantiva |

## 3. Situação das fontes verificadas em 2026-11-01

| Fonte | Status observado | Problema/categoria financiável | Fit mais forte | Ação |
|---|---|---|---|---|
| **Stellar Community Fund — SCF #46** | `OPEN-VERIFIED` — página oficial indica formulário de interesse ASAP e deadline 9 nov 2026; convite posterior pode ser necessário | Infraestrutura, integrações, DeFi e soluções globais; tracks Open, Integration e RFP | ValueCurator / PixelCoin / ReFi somente com integração Stellar real | **P0:** avaliar em 48h se há integração e caso de uso prontos; não inventar deployment |
| **Zcash Q4 Coinholder-Directed Retroactive Grants** | `OPEN-VERIFIED` — propostas 30 out–13 nov 2026; review 16 nov–16 dez; voto 17–29 dez | Trabalho já concluído e publicamente verificável, sujeito a voto de coinholders | Somente artefatos concluídos que realmente beneficiem Zcash/privacy | **P0 condicional:** inventariar trabalho já feito; não criar trabalho novo como se fosse retroativo |
| **Solana Foundation Grants & Funding** | `ROLLING` — standard/convertible grants e RFPs; revisão contínua | Public goods, tooling, infra, segurança e produtos com componente público/comercial | ValueCurator / ProofGate / Oracle | **P0:** montar proposta de policy gate + oracle integrity com milestones |
| **Superteam Earn Brazil / LATAM** | `MONITOR` — listagens dinâmicas de grants e bounties; verificar cada listing individualmente | Bounties de desenvolvimento, QA, conteúdo, hackathons e microgrants | ValueCurator, PixelCoin, Farcaster Commons | **P0:** selecionar apenas tasks que correspondam a entregas já executáveis; evitar campanhas de marketing desconectadas |
| **Filecoin Foundation Grants** | `ROLLING` — Open Grants e FIL Builder Next Step anunciados; Next Step divulgado entre US$5k–10k | Developer/data tooling, integrações, pesquisa, storage/retrieval e FVM | Lakehouse / Corpora / Knowledge Weaver | **P1:** criar módulo demonstrável de persistência/retrieval e medir custo/recuperação |
| **The Graph Grants** | `MONITOR` — programa de grants ativo por categorias; página consultada dizia não haver RFPs abertos | Protocol, tooling, subgraphs/substreams, data services e community | Lakehouse / Oracle / PixelCoin | **P1:** propor um subgraph/data service real; não apresentar como RFP aberto |
| **Uniswap Foundation** | `ROLLING/CONDITIONAL` — grants e histórico de funding; audit subsidy disponível conforme processo/eligibilidade | v4 hooks, developer tooling, research, security, Unichain integrations | ValueCurator / security harness / DeFi analytics | **P1:** verificar elegibilidade para security subsidy; desenvolver integração Uniswap v4 se fizer sentido |
| **Arbitrum Foundation** | `ROLLING/CONDITIONAL` — página lista aplicações para dApps e Infrastructure & Tools; confirmar programa e critérios na submissão | dApps e infraestrutura/ferramentas | Oracle / DAO / ValueCurator | **P1:** só candidatar após integração/deployment Arbitrum e milestones |
| **Ethereum Foundation ESP** | `MONITOR` — sem wishlist ativa na página oficial consultada; foco continua em OSS, infra, research, builder tools e community resources | Ferramentas universais, infraestrutura, pesquisa, segurança e bens públicos | Promptcraft / Compilatum / Lakehouse / SLM | Preparar evidência e office-hours; aguardar item/RFP compatível |
| **Gitcoin campaigns** | `MONITOR` — campanhas listadas incluem Protocol Guild e TheDAO Security Fund; Grants 24 e rounds anteriores encerrados | OSS, segurança, public goods e funding comunitário | Farcaster Commons / Promptcraft / Compilatum | Preparar perfil, comunidade e prova de uso; confirmar elegibilidade e janela da campanha |
| **Optimism Retro Funding** | `PAUSED` — Year 4 update diz que não houve novas rounds/missions após Season 7 | Retroactive public goods funding | OSS se houver nova missão futura | Não contabilizar como receita provável; monitorar Governance Fund separadamente |
| **Arbitrum Questbook legacy** | `CLOSED` — programa antigo marcado como completo | Histórico, não oportunidade atual | — | Não reutilizar como chamada aberta |
| **Superteam Agentic Engineering Grant (US$200 USDG)** | `PAUSED` no listing consultado | MVP funcional com integração Solana e uso de ferramentas de IA | Qualquer microproduto Solana pronto para shipping | Não incluir em forecast até reabrir |
| **OpenSats** | `CONDITIONAL` | Bitcoin/Nostr/FOSS e pesquisa de segurança; não é grant genérico Web3/IA | SLM/Promptcraft apenas se houver contribuição Bitcoin/Nostr | Só avançar com entregável nativo do ecossistema |

### Fontes oficiais / páginas de status

- Stellar SCF Awards: https://communityfund.stellar.org/awards
- Zcash Q4 retroactive call: https://forum.zcashcommunity.com/t/q4-coinholder-directed-retroactive-grant-program-call-for-proposals/58598
- Zcash proposals: https://openzcash.org/coinholders/proposals
- Solana Foundation grants: https://solana.org/grants-funding
- Superteam Brazil: https://superteam.fun/earn/regions/brazil/
- Superteam LATAM: https://superteam.fun/earn/regions/latin-america
- Filecoin grants: https://fil.org/grants
- The Graph grants: https://thegraph.com/grants/
- Uniswap Foundation grants: https://www.uniswapfoundation.org/grants
- Uniswap audit subsidy / builder funding: https://developers.uniswap.org/docs/ecosystem/builder-support/get-funded
- Arbitrum grants: https://arbitrum.foundation/grants
- Ethereum ESP wishlist: https://esp.ethereum.foundation/applicants/wishlist
- Ethereum ESP funded projects: https://esp.ethereum.foundation/funded-projects
- Gitcoin campaigns: https://gitcoin.co/campaigns
- Optimism Year 4 budget update: https://gov.optimism.io/t/collective-year-4-budget-update-and-year-5-budget-outlook/10796
- Superteam Agentic Engineering Grant: https://superteam.fun/earn/grants/agentic-engineering/

## 4. Mapa de repositórios: como posicionar o portfólio

A lista abaixo é uma **triagem estratégica por nomes, READMEs e contexto disponível**, não uma auditoria de maturidade de cada repositório. Repositórios com README-template ou documentação incompleta não devem ser apresentados como produto pronto.

| Cluster | Repositórios | Papel financiável / adaptação |
|---|---|---|
| **Capital, DeFi e agentes** | `value-curator`, `vc`, `invest-os`, `neurosimbolic-trader`, `defi-kingdom`, `dfk-pecdoa-postman-cockpit`, `web3-launchpad-pro`, `nft-gen`, `ip-nft`, `eidos-tokenization`, `pixelcoin` | Policy gates, segurança de agentes, risk analytics, interfaces de capital, tokenization rights/receipts. Focar em ValueCurator como produto âncora; demais como módulos ou pesquisa |
| **Dados, oráculos e interoperabilidade** | `oracle`, `lakehouse`, `knowledge-weaver`, `Corpora`, `InternaResources`, `links-vault`, `gdrive-reorg`, `holographic-synthesis` | Indexação, pipelines, provenance, armazenamento, retrieval, data products e geodata |
| **IA, agentes, developer tooling e engenharia** | `omni-laboratory`, `promptcraft`, `cognitiv`, `compilatum`, `harness-engineering`, `SLM`, `cognitive-search-orchestrator`, `NaturalLanguageCognitiveArchitecture`, `neurocoder-pwa`, `molora`, `kaelvive-reversa`, `planner`, `context-planner-pwa`, `uml-navigator`, `storybook-genui`, `lovable-command-center`, `canvas`, `lottie-flow`, `emacs` | Agent observability, evaluation, provenance, CLI/SDK, reproducible workflows, docs, context tooling and developer experience |
| **Governança, grants e commons** | `concurseiro-grants`, `IPIT`, `DAO`, `governaut-os`, `sovereign-budget`, `portfolio`, `farcaster-nexus` | Contribution OS, evidence ledger, grant matcher, budget transparency, governance workflows, community onboarding |
| **Pesquisa, simulação e impacto** | `prompt-audiofeedback`, `cadcad-explorer`, `regenerativo`, `uap-synthesis-project`, `hypervision`, `proterol`, `cult`, `sovereign-html-mockups` | Research tooling, simulation, local-first biofeedback, impact measurement, regenerative finance and territorial data |
| **Integração / arquivo / laboratório** | `monorepo`, `gdrive-reorg`, `links-vault`, `InternaResources`, `kaelvive-reversa` | Build/release engineering, archive, reproducibility, knowledge preservation; funding as shared infrastructure only where costs are allocated |

**Nota:** a organização consultada tinha 55 repositórios acessíveis nesta listagem. O inventário pode mudar; verificar o repositório e a branch antes de escrever propostas. `regenerativo` usa branch default `master`; outros repositórios podem ter documentação divergente.

## 5. Grant stacking: compor sem duplicar

### 5.1 Camadas compatíveis

1. **Core public good:** SDK, schema, tests, docs, reference implementation — grant de ecossistema.
2. **Ecosystem adapter:** integração específica (Solana, Stellar, Filecoin, The Graph, Arbitrum) — outro grant/RFP, desde que o escopo seja adicional e elegível.
3. **Security assurance:** threat model, fuzzing, auditoria independente — audit subsidy ou security fund, sem cobrar novamente custos já financiados.
4. **Community adoption:** onboarding, docs, workshops e bounties — mecanismo comunitário separado.
5. **Commercial extension:** hosted API, enterprise workflow, white-label, support — receita comercial/accelerator, com IP e custos separados.
6. **Impact evidence:** adoption, usage, dependency graph, external reviews — pode sustentar funding futuro/retroativo, mas não é um pagamento garantido.

### 5.2 Regras de integridade

- Um deliverable tem um identificador único e um ledger de custo.
- Cada fonte financia um pacote de trabalho ou parcela claramente identificada.
- Custos compartilhados têm rateio documentado e permitido pelos contratos.
- Informar cofinanciamento e outros pedidos quando exigido.
- Licença, autoria, cessão de IP, dados e direitos de reutilização são definidos antes da execução.
- Não vender um token como liquidez, participação, dívida ou direito de revenda sem estrutura e análise próprias.
- Não pedir retroactive funding para trabalho futuro; não declarar impacto sem prova independente.
- Não criar integrações fictícias apenas para parecer elegível.

### 5.3 Exemplo de composição — ValueCurator

| Pacote | Entrega | Fonte possível | Fronteira de escopo |
|---|---|---|---|
| VC-CORE | Policy engine, schemas, SDK, tests e demo Devnet | Solana Foundation / Superteam | Core genérico e aberto |
| VC-ORACLE | Adapter Pyth, freshness/confidence/deviation checks | Solana ecosystem | Integração oracle específica |
| VC-DEX | Guarded quote/swap adapter e slippage controls | Solana / Uniswap se houver implementação nativa | Não duplicar policy engine |
| VC-SEC | Threat model, fuzz/property tests e auditoria externa | Uniswap security subsidy / programa elegível | Revisão independente, sem reembolsar custos cobertos por outro grant |
| VC-ADOPT | Docs, quickstart, workshops e integração de terceiros | Bounties / community funding | Adoção e educação, não engenharia core |
| VC-COMM | Hosted dashboard, support, white-label e enterprise features | Clientes / accelerator | Separar do OSS financiado |

### 5.4 Exemplo de composição — Lakehouse / Knowledge Infrastructure

| Pacote | Entrega | Fonte possível | Fronteira de escopo |
|---|---|---|---|
| DATA-CORE | Ingestion, canonical schema, provenance e tests | Ethereum ESP quando houver item / Gitcoin | Core aberto |
| DATA-GRAPH | Subgraph/Substreams ou serviço de dados | The Graph | Integração Graph específica |
| DATA-STORE | Content-addressed storage e retrieval | Filecoin | Persistência Filecoin específica |
| DATA-ANALYTICS | Dashboards, datasets e public reports | Gitcoin / community grants | Consumo e evidência |
| DATA-HOSTED | API gerenciada, SLA e suporte | Receita de clientes | Serviço comercial separado |

## 6. Prioridade de execução (próximos 30 dias)

| Prioridade | Ação | Repositórios | Critério de saída |
|---|---|---|---|
| **P0 — até 48h** | Decidir se existe caso Stellar real e elegível para SCF #46; se sim, preparar interest form | `value-curator`, `pixelcoin`, `regenerativo` | Integração e usuário-alvo reais, milestones e budget defensáveis; deadline oficial 9 nov |
| **P0 — até 5 dias** | Fazer inventário de entregas já concluídas que possam beneficiar Zcash e verificar elegibilidade retroativa | `SLM`, `cognitiv`, `promptcraft`, `oracle` | Prova pública anterior à candidatura e benefício explícito ao ecossistema Zcash; deadline 13 nov |
| **P0 — até 7 dias** | Escrever proposta-mãe ValueCurator com threat model, testes e milestones | `value-curator`, `vc`, `oracle`, `harness-engineering` | Demo reproduzível + 3–4 milestones + orçamento por entregável |
| **P1 — 2 semanas** | Criar módulo real de storage/retrieval e pipeline de dados | `lakehouse`, `Corpora`, `knowledge-weaver` | Demo Filecoin com custo, integridade e retrieval medidos |
| **P1 — 2 semanas** | Criar um data product de indexação ou dashboard com The Graph | `lakehouse`, `oracle`, `pixelcoin` | Subgraph/substreams funcional e usuário consumidor |
| **P1 — 3 semanas** | Converter conversas em issues com acceptance criteria e evidências | `concurseiro-grants`, `IPIT`, `farcaster-nexus` | 5 work packages publicados, 2 contributors externos, 1 PR aceito |
| **P2 — 30 dias** | Preparar trilha de pesquisa e validação para AROS e ReFi | `prompt-audiofeedback`, `regenerativo`, `cadcad-explorer` | Protocolo, baseline, parceiro/usuário e evidência experimental |

## 7. O que NÃO fazer

- Não aplicar a 15 ecossistemas com o mesmo pitch genérico.
- Não declarar que uma chamada está aberta apenas porque a fundação tem página de grants.
- Não priorizar o maior cheque; priorizar probabilidade de entrega × reutilização × custo de candidatura.
- Não confundir “problema do setor” com “RFP publicada”.
- Não prometer interoperabilidade sem adapter, deployment e teste.
- Não fragmentar artificialmente um único deliverable para cobrar múltiplas vezes.
- Não sacrificar a arquitetura para perseguir toda chain; adapters são opcionais, o core deve permanecer portátil.

## 8. Modelo de decisão

Para cada oportunidade (o):

[
Score(o)=0.25F+0.20E+0.20P+0.15T+0.10R+0.10C
]

Onde cada variável recebe 0–5: (F)=fit com a demanda; (E)=evidência disponível; (P)=elegibilidade; (T)=timing; (R)=retorno relativo ao esforço; (C)=valor composicional/reuso. Score alto não supera hard gates: chamada fechada, incompatibilidade geográfica, licença não elegível, ausência de integração ou conflito de financiamento eliminam a candidatura.

**Meta operacional:** 3 candidaturas bem qualificadas, 2 bounties executáveis e 1 piloto de funding comunitário — não dezenas de aplicações superficiais.

---

*Atualizar este documento semanalmente. Toda alteração de status deve registrar URL oficial, data/hora de checagem, trecho/evidência e responsável. O GrantOS deve tratar agregadores como descoberta, nunca como fonte final de verdade.*
