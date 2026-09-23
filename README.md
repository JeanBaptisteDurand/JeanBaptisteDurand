# Jean-Baptiste Durand — AI Engineer · RAG, agents & MCP

Je construis des **systèmes RAG** et des **agents LLM** qui tournent en production : recherche hybride, outils exposés en MCP, réponses ancrées dans la source, tests et mesures.
Le jour, mainframe z/OS chez AXA — d'où un croisement rare : **COBOL × agents LLM**.

**4 hackathons remportés** · ETHOnline 2026 (prix Uniswap Foundation) · Open Agents 2026 · MBC 2025 Miami · SUI Paris 2025 · IBM AI Builders Challenge

```
RAG        chunking · recherche hybride (vectoriel + mots-clés) · reranking · evals · citations ancrées
Agents     tool calling · MCP (serveur et client) · LangGraph · ReAct · garde-fous et reprise d'erreur
Stack      Python · FastAPI · TypeScript · PostgreSQL/pgvector · Neo4j · Docker · GitHub Actions
Modèles    IBM Granite / watsonx.ai · BeeAI · OpenAI · Anthropic · embeddings
```

## 🔭 Ce que je construis

### [COBOL Explorer](https://github.com/JeanBaptisteDurand/cobol-explorer) — RAG agentique sur un parc mainframe · [démo en ligne](https://cobol-explorer.fr)
Un parc COBOL entier — programmes, paragraphes, copybooks, tables DB2, transactions CICS, jobs JCL, chaînes d'ordonnancement — devient un **graphe de dépendances interrogeable en langage naturel**.

- **Recherche hybride** : parcours de graphe déterministe + recherche vectorielle (embeddings Granite), orchestration ReAct via BeeAI.
- **Ancrage** : chaque réponse est citée jusqu'à la ligne de code source. Pas de réponse sans source.
- **3 outils MCP** exposés à IBM Bob : `graph_lookup`, `search_code`, `read_source_lines`. L'IA est auditée comme un collègue : rôles, revue, journal d'audit infalsifiable.
- **Mesuré** : 158 tests back + 51 end-to-end, CI verte, 2 parcs réels indexés (339 et 1 157 nœuds), analyse d'impact ramenée de plusieurs jours à ~30 secondes.

### [TARE](https://github.com/JeanBaptisteDurand/ETH_Online_2026) — ce qu'un hook Uniswap v4 prélève vraiment · [tare-hooks.tech](https://tare-hooks.tech)
125 072 mesures rejouables. Tu choisis ta route sur un Ledger, avec le prélèvement de chaque hook affiché, **avant** que MetaMask ne s'ouvre. Taux attestés sur Hedera.
*Prix « Best Uniswap Stack Contribution » · 1 des 8 finalistes sur 814 projets (ETHOnline 2026).*

### [LPLens](https://github.com/JeanBaptisteDurand/Open_Agent_2026) — agent autonome de sauvetage de positions LP · [lplens.xyz](https://lplens.xyz)
Agent avec identité ENS et mémoire on-chain, sur la stack 0G. *1 des 7 finalistes sur 468 projets, en solo (ETHGlobal Open Agents 2026).*

### [GuardLens](https://github.com/JeanBaptisteDurand/Ledger_Agent_Stack) — coupe-circuit matériel pour agents crypto
L'agent compose la transaction, un moteur de politique déterministe la filtre, **un Ledger signe en dernier ressort**. Parce qu'une clé chaude dans un `.env` n'a pas de coupe-circuit. *Bounty Ledger N3XT.*

### [BaseLens](https://github.com/JeanBaptisteDurand/MBC_2025) — analyse de smart contracts par IA + agent on-chain
RAG sur le code des contrats vérifiés, décompilation de repli, découverte récursive des proxies ; agent AgentKit exécutant des instructions en langage naturel, smart wallets ERC-4337, paiements x402. *Gagnant MBC 2025, Miami.*

### [CorLens](https://github.com/JeanBaptisteDurand/CORlens) — risk intelligence et conformité DeFi sur XRPL
Cartographie et audit des paiements cross-border, agent de conformité autonome. [cor-lens.xyz](https://cor-lens.xyz)

## 🧪 En cours
Un RAG agentique qui **choisit sa recherche** selon la question : vectoriel (pgvector), mots-clés (BM25), ou graphe (Neo4j) — fusion RRF, reranking par cross-encoder, evals chiffrées par type de question, traces et coûts (Langfuse, Prometheus, Grafana).

## 📚 Aussi ici
Mainframe (COBOL, JCL, CICS, DB2, et un serveur web écrit en COBOL), backend Go et Java Spring, cursus 42 en C/C++ (IRC, webserv, transcendence), et une distribution Linux construite depuis les sources.

📫 group.jbjd@gmail.com · [X](https://x.com/JBD_Dev) · disponible immédiatement, télétravail complet bienvenu
