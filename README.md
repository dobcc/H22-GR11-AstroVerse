# H22-GR11-AstroVerse

Le jeu consiste de trois scènes: le menu, le système stellaire, et le quiz.

/Le jeux ouvre sur le menu, ou vous pouvez atteinde le système stellaire ou arrêter le jeu par un interface. interraction se fait par le bouton "saisie"

/une fois dans le système stellaire, sélectionnez des planètes avec le bouton "saisie", puis leur description apparaîtra à votre bras. par le bouton "menu" de votre manette, un menu apparaîtra sur votre bras. vous pourez retourner au menu principal, gérer le son, ou commencer le quiz.

/Une fois dans le quiz, choisissez vos réponses, puis un total de vos points vous sera donné. vous pourez alors recommencer. Le même menu sur votre bras peut vous rammener au menu principal.
_____________
Bugs:
- il devient impossible d'interragir avec le menu du bras après avoir interragit avec une planète: le joueur devient softLocked.
_____________
features non-implimentés:
- le joueur ne peut se déplacer: les propositions de tutoriels n'étaient pas compatibles avec notre pawn
- le joueur ne peut se téléporter: les tracks que les planètes suivent pour leur orbite semblent interférer avec la téléportation. On a donc pas implimenté de navmesh dans les autres scènes et la téléportation ne marche donc pas.
- Le range d'interraction est court: la portion du qui déterminait le range n'a pas été identifiée dans les délais.
--> Vous ne pouvez donc qu'analyser mercure, on vous recommende de tester le reste du jeu avant pour ne pas avoir à le fermer et le réouvrir
