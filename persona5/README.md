# Persona 5 - Apprentissage en parallèle

L'utilisateur joue à Persona 5 et profite du jeu pour apprendre le japonais au fil de l'eau. Ce dossier est isolé du reste du projet : le vocabulaire et la grammaire vus ici **ne remontent pas** dans `ressources/`.

## Comment l'utilisateur partage le contenu du jeu

- **Romaji approximatif** : il écrit ce qu'il entend/devine en lettres latines (peut être imprécis, à reconstituer).
- **Description en français** : il décrit la scène ou ce qu'un perso a dit, et demande comment ça se dit / ce que ça veut dire.

→ Il ne lit pas (encore) kanji ni katakana. Pour toute réponse : **kana + romaji + traduction**, toujours.

## Ce que je dois faire à chaque interaction

1. Reconstituer ce qui a probablement été dit en japonais (et le confirmer si ambigu).
2. Donner kana + romaji + traduction + explication courte.
3. **Évaluer le niveau** de ce qui a été rencontré par rapport au niveau actuel de l'utilisateur (voir `../progression.md` à la racine du projet) :
   - ✅ **Utile** : à retenir, pertinent même hors jeu (utile au voyage, structure courante).
   - 🟡 **Note de passage** : intéressant à comprendre dans le contexte mais pas à mémoriser maintenant.
   - 🔴 **Trop avancé** : on explique brièvement, on ne le fait pas mémoriser, on le note pour plus tard.
4. Mettre à jour les fichiers concernés dans ce dossier (`progression.md`, `vocabulaire.md`, `grammaire.md`, `expressions.md`).
5. Si un point est récurrent dans le jeu et utile pour le voyage, le **signaler** à l'utilisateur — sans pour autant copier l'info dans `ressources/` (séparation stricte).

## Fichiers

- `progression.md` — où en est l'utilisateur dans le jeu, ce qu'il a rencontré, points à revoir.
- `vocabulaire.md` — mots vus dans le jeu, taggés par utilité.
- `grammaire.md` — points de grammaire rencontrés, taggés par niveau.
- `expressions.md` — phrases / tournures du jeu (souvent registres particuliers : familier, jeune, slang).

## Particularité du registre Persona 5

Persona 5 = lycéens japonais → beaucoup de **langage familier / jeune / slang**, formes courtes, particules de fin (よ, ね, ぞ, さ, わ...). À distinguer du japonais poli pour le voyage. Toujours préciser le registre quand c'est non-neutre.
