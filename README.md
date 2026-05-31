# BC Extensions — by WALYCONSEIL

Site vitrine des extensions Business Central développées par WALYCONSEIL.

## Structure

```
bc-extensions/
├── index.html                    ← Hub — catalogue des extensions
├── franco-fournisseur.html       ← Page commerciale Franco Fournisseur
├── franco-fournisseur-docs.html  ← Documentation technique (FR/EN)
├── vercel.json                   ← Config Vercel (clean URLs)
└── README.md
```

## URLs propres (après déploiement Vercel)

| Fichier | URL |
|---|---|
| `index.html` | `bc-extensions.io/` |
| `franco-fournisseur.html` | `bc-extensions.io/franco-fournisseur` |
| `franco-fournisseur-docs.html` | `bc-extensions.io/franco-fournisseur/docs` |

## Déploiement Vercel

1. Pusher ce repo sur GitHub
2. Connecter le repo sur [vercel.com](https://vercel.com)
3. Framework Preset → **Other**
4. Root Directory → `/` (racine)
5. Build Command → *(laisser vide)*
6. Output Directory → *(laisser vide)*
7. Deploy

## Domaine

Brancher votre domaine (ex. `bc-extensions.io`) dans Vercel → Settings → Domains.

## Mise à jour d'une page

Modifier le fichier HTML → `git add . && git commit -m "update" && git push` → Vercel redéploie automatiquement.

---

*WALYCONSEIL — contact@walyconseil.com*
