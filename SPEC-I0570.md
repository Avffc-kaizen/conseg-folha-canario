# Folha I0570 — spec visual (simulador vivo)

App: Consórcio · folha.ts do conseg-site.
Paleta: paper #f6f1e4 · card #fffcf6 · navy #12233f · gold #c6a46a · mute #6b6558 · label #8a8376 · sub #5c574c.
Tipo: Fraunces/Georgia display · Inter corpo · C serif círculo r=26 stroke gold.
Formato: 1080×1520 P1+P2. WA = P1 sem reflow.

## P1 sempre
- Título: Sua proposta de Consórcio. Nome só se o lead deu.
- Sub sem “sem juros”.
- KPI: PARCELA AGORA · CRÉDITO · PRAZO · REDUTOR (ou TX ADM se não houver redutor mapeado).
- Ranking só covering real. Nunca inventar IM180/150/100.
- 4 faixas só se o grupo tiver simulação oficial.

## P2 só se mapeado
Lances · taxas · pós “não simulada” · disclaimer FIO.

## Omitir
Logo Porto Bank · juros 0% · emoji · x:game · custo total no herói · site.json.

## Deploy do site
conseg-site: `npm run deploy` → wrangler (Cloudflare Worker `consegseguro`).
