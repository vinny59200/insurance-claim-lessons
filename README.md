# Sinistres · Académie assurance

Formation publique et indépendante sur la gestion des sinistres IARD en France. Destinée notamment aux développeurs, analystes et nouveaux gestionnaires. Les cas sont fictifs et les références sont publiques ; ce site ne décrit aucune procédure interne d'un assureur et ne remplace pas un conseil juridique.

## Utilisation

Aucune dépendance, compilation ou configuration applicative. HTML, CSS et JavaScript natifs.

- `index.html` : structure, styles, navigation, recherche et interaction.
- `courses.js` : modules, leçons, cas pratiques, quiz, glossaire et références. Chaque leçon a un identifiant stable.
- Les pages de modules et leçons utilisent des URL partageables (`?module=instruction&lesson=badinter`). La progression est enregistrée dans le navigateur (`localStorage`), sans compte ni serveur.

Pour tester localement, ouvrir `index.html` ou, de préférence, lancer à la racine :

```bash
python -m http.server 8000
```

Puis ouvrir http://localhost:8000.

## GitHub Pages

1. Dans GitHub, ouvrir **Settings → Pages**.
2. Choisir **Deploy from a branch**, sélectionner `main` et `/(root)`, puis **Save**.
3. Attendre la fin du déploiement dans **Actions**.
4. Adresse attendue : https://vinny59200.github.io/insurance-claim-lessons/

## Mise à jour pédagogique

Modifier `courses.js`, conserver les identifiants existants et vérifier les références juridiques à la date d'effet. Les conventions interassureurs et les détails ClaimCenter doivent être vérifiés dans leur version applicable. Ajouter des cas fictifs, sans publier de données de clients ni de procédures internes.

Édition initiale : novembre 2026.
