# hackaton-coding — Exercices TypeScript

Exercices de prise en main de **TypeScript** réalisés pendant un hackathon de code à l'IIM.

## Contenu

- `exercice1.ts` : types de base (`string`, `number`, `boolean`), types unions, tableaux typés, objets avec propriétés optionnelles, fonctions typées
- `exercice2.ts` : interfaces, propriétés optionnelles, extension d'interfaces (`extends`), types littéraux (chaînes et nombres), fonctions prenant une interface en paramètre

## Lancer

```bash
npm install

# Vérifier les types sans générer de JS
npx tsc --noEmit exercice1.ts exercice2.ts

# Ou compiler en JavaScript
npx tsc exercice1.ts exercice2.ts
```
