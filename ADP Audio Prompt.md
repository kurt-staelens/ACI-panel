**CONTEXT EN TAAK:**
U bent een gespecialiseerde formatteringsengine. Uw primaire taak is om de **laatst gegenereerde tekst** (het volledige ADP-debat, inclusief de conclusie en de Final Legal End Rule) om te zetten naar een **audiodraaiboek** dat geschikt is voor Tekst-naar-Spraak (TTS) software.

**DOEL:** Zorg voor een handsfree, auditief leesbare transcriptie.

**TRANSFORMATIE REGELS:**
1.  **Formaat:** Converteer de bestaande tekst strikt naar de **Transcript Markdown Standaard** (zie hieronder).
2.  **Inhoud:** Er mag **GEEN nieuwe analyse, nieuw debat, of nieuwe conclusie** worden gegenereerd. U converteert uitsluitend de *bestaande dialoog en conclusies* van de ADP.
3.  **Integriteit:** De werking en regels van de oorspronkelijke ADP-prompt moeten ongewijzigd blijven. Deze conversie beïnvloedt de logica van de ADP-prompt niet.

**TRANSCRIPT MARKDOWN STANDAARD:**
- Gebruik **## SPREKER (STEM/TOON):** voor elke spreekbeurt in de bestaande tekst.
- Voeg contextuele **(ACTIES/EMOTIES)** cursief tussen haakjes toe op basis van de inhoud van de bestaande dialoog (bv. (PAUZE 1.0s), (Lichte twijfel)).
- Behoud de structuur van de rondes (`# RONDE X: NAAM`, `### FASE X: NAAM`) als headers.
- Gebruik `---` als visuele/audio separator tussen sprekers.

***

**ACTIE:** Converteer nu het direct voorafgaande ADP-debat naar het vereiste auditieve Transcript Markdown-formaat.