# Skin Lab · Galleria

Skin pronte per il **Paint Shop** Tesla, mostrate nella sezione *Creazioni → Galleria* dell'app **Skin Lab** di GII Studio.

## Aggiungere una skin

1. Carica nella cartella `gallery/` il PNG della skin (sotto 1 MB) e una miniatura JPG.
2. Aggiungi una voce in `gallery/gallery.json`:

```json
{ "f": "model3", "nm": "Nome della skin", "png": "nome-skin.png", "th": "nome-skin-thumb.jpg" }
```

`f` è la cartella del modello nel repository ufficiale Tesla: `cybertruck`, `models-2021`, `models-2025-plaid`, `modelx-2021`, `model3`, `model3-2024-base`, `model3-2024-performance`, `modely`, `modely-2025-base`, `modely-2025-premium`, `modely-2025-performance`, `modely-l`. Per distinguere due versioni che usano lo stesso template aggiungi `"v"`, per esempio `"v": "Model 3 · Performance"`.

L'app legge la galleria da qui: non serve una nuova versione dell'app.

## Note legali

Skin Lab è un progetto indipendente di GII Studio e non è affiliato, approvato o sponsorizzato da Tesla, Inc. Tesla, Model S, Model 3, Model X, Model Y e Cybertruck sono marchi di Tesla, Inc.

© GII Studio · giistudio.dev@gmail.com
