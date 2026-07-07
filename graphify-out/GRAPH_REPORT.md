# Graph Report - /Users/neary/Desktop/AETHERA/site  (2026-07-07)

## Corpus Check
- 2 files · ~97,376 words
- Verdict: corpus is large enough that graph structure adds value.

## Summary
- 28 nodes · 36 edges · 5 communities
- Extraction: 92% EXTRACTED · 8% INFERRED · 0% AMBIGUOUS · INFERRED: 3 edges (avg confidence: 0.5)
- Token cost: 0 input · 0 output

## Community Hubs (Navigation)
- [[_COMMUNITY_AETHERA Setting|AETHERA Setting]]
- [[_COMMUNITY_Noèses and Feutre|Noèses and Feutre]]
- [[_COMMUNITY_Human Settlements|Human Settlements]]
- [[_COMMUNITY_Deep Chronology|Deep Chronology]]
- [[_COMMUNITY_Drowned Ruins|Drowned Ruins]]

## God Nodes (most connected - your core abstractions)
1. `An 3000` - 14 edges
2. `Noèses` - 5 edges
3. `Le Feutre` - 5 edges
4. `Villes-récifs` - 5 edges
5. `60 million humans` - 4 edges
6. `AETHERA` - 2 edges
7. `Monde remplacé` - 2 edges
8. `+4 °C stabilized climate` - 2 edges
9. `Programmes de Maintien` - 2 edges
10. `Le Versement` - 2 edges

## Surprising Connections (you probably didn't know these)
- `Pierre poussée` --grown_by--> `Le Feutre`  [INFERRED]
  index.html → index.html  _Bridges community 1 → community 2_
- `An 3000` --includes_place--> `Côtes Australes`  [EXTRACTED]
  index.html → index.html  _Bridges community 0 → community 1_
- `An 3000` --includes_place--> `La Mer Basse`  [EXTRACTED]
  index.html → index.html  _Bridges community 0 → community 4_
- `An 3000` --has_marker--> `60 million humans`  [EXTRACTED]
  index.html → index.html  _Bridges community 0 → community 2_
- `Programmes de Maintien` --evolve_into--> `Noèses`  [EXTRACTED]
  index.html → index.html  _Bridges community 3 → community 1_

## Communities (5 total, 0 thin omitted)

### Community 0 - "AETHERA Setting"
Cohesion: 0.25
Nodes (7): AETHERA, Énergie bleue, Year 297 of l’Étale, La Mer Amazone, Métal remonté, +72 m sea rise, An 3000

### Community 1 - "Noèses and Feutre"
Cohesion: 0.40
Nodes (6): Côtes Australes, Le Feutre, Liya, Non-Traduite, Noèses, +4 °C stabilized climate, Monde remplacé

### Community 2 - "Human Settlements"
Cohesion: 0.33
Nodes (6): Feux longs, Les Hauts, Les Laisses, Pierre poussée, 60 million humans, Les Tenures

### Community 3 - "Deep Chronology"
Cohesion: 0.50
Nodes (4): L’Étale, La Montée, Programmes de Maintien, Le Versement

### Community 4 - "Drowned Ruins"
Cohesion: 0.67
Nodes (3): La Mer Basse, La remonte, Villes-récifs

## Knowledge Gaps
- **7 isolated node(s):** `+72 m sea rise`, `Year 297 of l’Étale`, `La Mer Amazone`, `La remonte`, `Feux longs` (+2 more)
  These have ≤1 connection - possible missing edges or undocumented components.

## Suggested Questions
_Questions this graph is uniquely positioned to answer:_

- **Why does `An 3000` connect `AETHERA Setting` to `Noèses and Feutre`, `Human Settlements`, `Deep Chronology`, `Drowned Ruins`?**
  _High betweenness centrality (0.726) - this node is a cross-community bridge._
- **Why does `60 million humans` connect `Human Settlements` to `AETHERA Setting`?**
  _High betweenness centrality (0.224) - this node is a cross-community bridge._
- **Why does `Villes-récifs` connect `Drowned Ruins` to `AETHERA Setting`, `Noèses and Feutre`, `Human Settlements`?**
  _High betweenness centrality (0.162) - this node is a cross-community bridge._
- **What connects `+72 m sea rise`, `Year 297 of l’Étale`, `La Mer Amazone` to the rest of the system?**
  _7 weakly-connected nodes found - possible documentation gaps or missing edges._