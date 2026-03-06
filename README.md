# Beslagset Picker

Interactieve tool voor order pickers om de juiste beslagsets samen te stellen per product.

## Producten

| Product | Varianten |
|---------|-----------|
| Bedframe Altaia | 2 elektrisch, 1 vast + 1 elektrisch, 2 vast |
| Bedframe Less | Frame wit/zwart, met/zonder hoofdbord, nachttafels |
| Boxspring Balance | Bodems, nekmotors, Inspirations hoofdbord, nachttafels |
| Hoofdbord Inspirations | Met/zonder verlichting, met/zonder nachttafels |

## Gebruik

Open `index.html` in een browser. Geen installatie nodig.

1. Kies het product
2. Beantwoord de configuratievragen
3. Vink alle items af per doos

## Kenmerken

- **17 beslagset-configuraties** met 106 unieke item-regels
- **Multi-box output**: één bestelling = meerdere dozen
- **Cross-product logica**: Balance + Inspirations hoofdbord detecteert automatisch koppelstukken
- **Nachttafel deduplicatie**: voorkomt dubbele nachttafels bij combinatie-orders
- **100% geverifieerd** tegen brondocumenten (106 items + 105 resolver-scenario's)

## Structuur

```
beslagset-picker/
├── index.html      # Standalone app (vanilla HTML/CSS/JS)
├── docs/           # Brondocumenten (.docx)
└── README.md
```

## Data-integriteit

Alle items en aantallen zijn 1-op-1 geverifieerd met de 16 originele brondocumenten.
Resolver-logica is getest met 105 exhaustieve scenario's (inclusief alle Balance-combinaties).
