# Banque de conseils — Fiches PFMP

> Ce fichier contient **tous les conseils** que l'app pourra afficher aux élèves.
>
> **Workflow** :
> 1. Tu rédiges un conseil ici (ou tu me dictes le texte et j'écris).
> 2. Tu choisis sa **date de première sortie** (champ `showFrom`).
> 3. À cette date, le conseil apparaît à l'élève à l'ouverture de l'app — une seule fois.
> 4. Si `replay: true`, le conseil peut **revenir aléatoirement** plus tard, en mode « rappel », au maximum une fois tous les 5 jours par téléphone.
> 5. Si `replay: false`, le conseil n'apparaît qu'une seule fois et c'est tout.

---

## Format à respecter

Chaque conseil commence par `## ` suivi d'un **identifiant unique** (jamais le réutiliser, jamais le modifier une fois publié), puis ses méta-données, puis le texte du conseil.

```
## identifiant-unique-2026-04-26

- showFrom : 2026-04-26   (ou : null pour disponible immédiatement)
- replay   : true          (ou : false)
- title    : 💡 Titre court avec emoji optionnel

Le texte du conseil ici. Plusieurs lignes possibles.

Mise en forme légère :
• Lignes commençant par "• " deviennent des puces.
• Mots entourés de **double étoiles** apparaissent en gras.
```

**Conseils pour bien rédiger** :
- Garder court (3-5 lignes max idéalement)
- Une idée par conseil — pas trop de chose à la fois
- Commencer par un emoji parlant dans le titre (📷 photos, 🛠 outils, 📅 organisation, 🔒 sécurité, etc.)
- Mettre en gras les **2-3 mots clés** qui doivent retenir l'attention

---

# Conseils actifs

## tuteur-2026-04-26

- showFrom : null
- replay   : true
- title    : 💡 Demandez à votre tuteur

N'hésitez pas à montrer l'application à votre tuteur et à lui demander son aide sur :

• Le **matériel utilisé** (quel matériel sélectionner)
• La **compétence mise en œuvre** pour le travail
• La **bonne activité** réalisée

En cas de doute, partagez-lui ce travail — il connaît son métier mieux que personne et sera ravi de vous aider à bien renseigner votre fiche.

---

# Brouillons et idées (commentés — pas affichés)

> Ces conseils sont prêts à être activés. Pour les mettre en ligne :
> 1. Choisis une date `showFrom` (ou `null` pour une sortie immédiate).
> 2. Déplace-les au-dessus, dans la section « Conseils actifs ».
> 3. Demande-moi de redéployer.

<!--

## photos-quality-EXEMPLE

- showFrom : 2026-05-03
- replay   : true
- title    : 📷 Astuce photo

Pour des photos lisibles et exploitables :

• Bonne **lumière** (pas à contre-jour)
• Cadrage **stable** (calez-vous contre un mur si besoin)
• Une photo doit montrer **une seule chose à la fois**

## securite-EXEMPLE

- showFrom : 2026-05-10
- replay   : true
- title    : 🦺 Sécurité d'abord

Avant chaque intervention, vérifiez :

• Vous portez vos **EPI** (casque, gilet, chaussures)
• La zone est **sécurisée** (cônes, signalétique)
• Vous avez **prévenu** votre tuteur de l'opération

-->
