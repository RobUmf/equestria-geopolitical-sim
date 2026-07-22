# equestria-geopolitical-sim
Geopolitical simulator tracking factional alignments, economic models, and delegate O.Cs across Equestria. Structured framework for maintaining LLM narrative consistency and visual asset uniformity.

# Equestria Geopolitical Simulator

Geopolitical simulator tracking factional alignments, economic models, and delegate O.Cs across Equestria.

This repository provides a structured framework for maintaining narrative consistency and visual uniformity across AI-generated stories and character designs. Along with the geopolitical simulator, it serves as a standardized database for tracking regional ideologies, macro-economic dependencies, and individual delegate profiles to ensure high-fidelity simulation outcomes.

---

## 🗺️ Active Factions & Ideological Landscapes

The simulation tracks seven distinct core city-state systems, each run by a primary Delegate O.C.:

| Faction / City | Economic Model & Ideology | Key Delegate |
| :--- | :--- | :--- |
| **Canterlot** | Classical Traditionalist Aristocracy | [Azure Etiquette](database/delegates/canterlot_azure/AzureEtiquette.md) |
| **Cloudsdale** | High-Altitude Industrial Meritocracy | [Gale Gauge](database/delegates/cloudsdale_gale/GaleGauge.md) |
| **Manehattan** | Hyper-Capitalist Corporate Meritocracy | [Ticker Tape](database/delegates/manhattan_ticker/TickerTape.md)|
| **The Equality Settlement** | Totalitarian Collectivist Neutrality | [Parity](database/delegates/ourtown_parity/Parity.md) |
| **Ponyville** | Grassroots Agrarian Decentralization | [Apple-Graft](database/delegates/ponyvile_apple/AppleGraft.md) |
| **Appleloosa** | Frontier Agrarian Expansion & Cartography | [Buckskin Trail](database/delegates/appleloosa_buckskin/BuckskinTrail.md) |
| **Los Pegasus** | Laissez-Faire Resort & Entertainment Capitalism | [Roulette](database/delegates/lospegasus_roulette/Roulette.md) |

---

## 📂 Repository Architecture

To maintain cross-session memory alignment when feeding data into Large Language Models (LLMs), the project relies on a strict directory layout:

*   `templates/` — Holds the empty baseline templates to ensure all future character additions follow identical data schemas.
*   `database/delegates/` — Individual Markdown files mapping character personality flaws, rhetorical styles, and precise visual asset indexes.
*   `database/factions/` — Dossiers outlining regional infrastructure biases, trade resources, and political leverage conditions.

---

## 🛠️ Simulation Mechanics & LLM Deployment

This framework is built to operate as a prompt-engineered, turn-based simulation. When initializing a session with an AI model:
1. **Load the Database:** Inject the relevant `.md` files from `database/` to ground the AI's contextual knowledge base.
2. **Inject the Prompt:** Provide a systemic geopolitical event (e.g., a regional resource shortage or trade tariff dispute).
3. **Execute the Turn:** The AI will evaluate how each delegate responds based on their strict city alignment matrices, behavioral quirks, and economic vulnerabilities.
