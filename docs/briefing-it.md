# Briefing rapido sull'MCP (italiano)

*Fonti: Wikipedia, "Model Context Protocol" — Sintesi della sezione "Contesto" e informazioni chiave dell'articolo. Preparato per i nuovi assunti che entrano a far parte del team di tooling.*

## Contesto

Il Model Context Protocol (MCP) è stato annunciato da Anthropic nel novembre 2024 come standard aperto per collegare gli assistenti AI a sistemi di dati quali repository di contenuti, strumenti di gestione aziendale e ambienti di sviluppo. Il protocollo è stato creato in Anthropic dagli ingegneri David Soria Parra e Justin Spahr-Summers ed è stato progettato per superare i silos informativi e i sistemi legacy. Prima dell'MCP, gli sviluppatori dovevano spesso creare connettori personalizzati per ogni fonte di dati o strumento, con il conseguente problema di integrazione dei dati che Anthropic ha definito "N×M".

Approcci precedenti — come l'API di "function-calling" di OpenAI del 2023 e il framework dei plug-in di ChatGPT — risolvevano problemi simili, ma richiedevano connettori specifici per ciascun fornitore. L'MCP riutilizza i concetti di flusso dei messaggi del Language Server Protocol (LSP).

Nel dicembre 2025, Anthropic ha donato l'MCP all'Agentic AI Foundation (AAIF), un fondo diretto facente capo alla Linux Foundation, co-fondato da Anthropic, Block e OpenAI, con il supporto di altre aziende. Più avanti nello stesso mese, Anthropic ha inoltre pubblicato Agent Skills, uno standard aperto complementare per il raggruppamento di istruzioni e risorse specifiche per attività, che gli agenti IA caricano su richiesta.

## Informazioni chiave

- Il Model Context Protocol (MCP) è uno standard aperto e un framework open-source introdotto da Anthropic nel novembre 2024 con l'obiettivo di standardizzare il modo in cui i sistemi di intelligenza artificiale (IA), come i modelli di linguaggio di grandi dimensioni (LLM), si integrano e condividono dati con strumenti, sistemi e fonti di dati esterni.
- MCP fornisce un'interfaccia standardizzata per la lettura di file, l'esecuzione di funzioni e la gestione di prompt contestuali.
- In seguito al suo annuncio, il protocollo è stato adottato dai principali fornitori di intelligenza artificiale, tra cui OpenAI e Google DeepMind.
- Nel dicembre 2025, Anthropic ha donato l'MCP all'Agentic AI Foundation, un fondo facente capo alla Linux Foundation.
