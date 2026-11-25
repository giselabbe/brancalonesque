# Branca — Index général du recueil

Version 2.0 — 25 novembre 2026 — proposition à valider.

Cet index est le point d’entrée du projet éditorial BRANCA, recueil illustré de la deuxième campagne de Brancalonia.

## 1. Organisation et source de vérité

Le [dépôt GitHub brancalonesque](https://github.com/giselabbe/brancalonesque), branche `main`, constitue le référentiel maître des documents qui y sont intégrés. Deux projets ChatGPT complémentaires l’utilisent :

- **BRANCA** : reconstitution de la campagne, rédaction et continuité narrative.
- **BRANCA Illustrations** : direction artistique, portraits, scènes, ornements et préparation graphique.

Consulter les fichiers pertinents sur GitHub avant chaque travail. Les versions distantes priment sur les anciennes copies des Sources, sauf indication explicite. Les documents et images absents du dépôt restent à consulter dans les Sources ou auprès de l’utilisateur. GitHub n’est pas synchronisé automatiquement dans le contexte ChatGPT.

L’utilisateur gère les modifications, commits et push ; ChatGPT consulte le dépôt en lecture seule. Les références visuelles validées restent prioritaires pour les illustrations ; les joindre à la génération si nécessaire.

## 2. RECIT — Référentiels narratifs

| Document | Fonction |
|---|---|
| [RECIT_00_Sommaire.md](Narration/RECIT_00_Sommaire.md) | Structure et état des chapitres |
| [RECIT_01_Chronologie.md](Narration/RECIT_01_Chronologie.md) | Événements et ordre narratif |
| [RECIT_02_Personnages.md](Narration/RECIT_02_Personnages.md) | Répertoire narratif ; futur index des fiches individuelles |
| [RECIT_03_Lieux.md](Narration/RECIT_03_Lieux.md) | Lieux et itinéraires |
| [RECIT_04_Lore.md](Narration/RECIT_04_Lore.md) | Univers, magie, institutions et objets |
| [RECIT_05_Points_a_confirmer.md](Narration/RECIT_05_Points_a_confirmer.md) | Questions ouvertes et corrections à recueillir |

Statuts existants : D = documenté dans le corpus, S = souvenir à recouper, P = proposition éditoriale, ? = information incertaine. D ne signifie pas validation finale.

## 3. PERSO — Fiches individuelles communes

Les fiches de `Perso/` regroupent les caractéristiques structurées (en-tête YAML), le récit libre et le prompt graphique de référence. Un personnage possède un identifiant stable et une fiche individuelle ; les index narratifs et graphiques ont vocation à pointer vers celle-ci, sans duplication. La migration est en cours : signaler les divergences sans les résoudre arbitrairement.

### Personnages joueurs

- [PJ_PSODIA — Psodia](Perso/pj/PJ_PSODIA.md)
- [PJ_TITO — Tito](Perso/pj/PJ_TITO.md)
- [PJ_MAREE_DE_NUIT — Marée de Nuit](Perso/pj/PJ_MAREE_DE_NUIT.md)
- [PJ_PERSONNE — Personne](Perso/pj/PJ_PERSONNE.md)
- [PJ_SISPEO — Sispéo (C3PO)](Perso/pj/PJ_SISPEO.md)

### PNJ et familiers

- [PNJ_SULTAN — Sultan](Perso/pnj/PNJ_SULTAN.md)
- [PNJ_TRUFFINO — Truffino](Perso/pnj/PNJ_TRUFFINO.md)

Autres PNJ : fiches à créer progressivement. Les YAML sont réservés aux personnages ; les autres documents restent en Markdown libre. Conserver les prompts originaux et distinguer validation graphique et narrative. Les champs inconnus restent non renseignés ou à `null`.

## 4. MANUSCRIT — Chapitres

| Chapitre | Fichier | Statut de travail |
|---|---|---|
| I — Sourcemolle | [RECIT_01_chapitre01_trame.md](../02_Manuscrits/Chapitres/RECIT_01_chapitre01_trame.md) | Récit V2 ; validation finale à confirmer |
| II — Scanzona | [RECIT_01_chapitre02_trame.md](../02_Manuscrits/Chapitres/RECIT_01_chapitre02_trame.md) | Synthèse neutre |
| III — La traversée vers Sibara | [RECIT_01_chapitre03_trame.md](../02_Manuscrits/Chapitres/RECIT_01_chapitre03_trame.md) | Version de travail 3 |
| IV — Cibara, le bois de Bologne et la réparation de la péniche | [RECIT_01_chapitre04_trame.md](../02_Manuscrits/Chapitres/RECIT_01_chapitre04_trame.md) | Chronologie de travail ; questions ouvertes |
| V — Le Liber Vetillæ | À intégrer | Texte absent du dépôt vérifié |

Les arcs ultérieurs restent à consolider. Conserver les graphies des titres de travail en attendant leur harmonisation.

## 5. GRAPH — Référentiels graphiques

Documents existants dans les Sources de BRANCA Illustrations, à intégrer ou réorganiser dans `01_Referentiel/Graphisme/` (répertoire absent du dépôt au 25 novembre 2026) :

- `GRAPH_01_Charte.md` : direction artistique, palettes, décoration et impression.
- `GRAPH_02_Personnages.md` : ancienne bible visuelle ; futur index graphique vers les fiches `Perso/`.
- `GRAPH_03_Illustrations.md` : bibliothèque de prompts et inventaire des scènes, lieux et accessoires ; découpage ultérieur possible.

Les prompts des personnages sont désormais intégrés aux fiches individuelles. Ne pas recréer une copie concurrente des prompts. Les planches `REF_01` à `REF_05` présentes dans les Sources restent utilisables comme références complémentaires.

## 6. ILLUSTRATIONS — Références visuelles sur GitHub

Répertoire : [04_Illustrations/references/](../04_Illustrations/references/).

| Personnage | Références individuelles |
|---|---|
| Psodia | [Portrait](../04_Illustrations/references/PJ_PSODIA_REF.png) · [Variantes](../04_Illustrations/references/REF_PSODIA_VARIANTES.png) |
| Tito | [Début](../04_Illustrations/references/PJ_TITO_DEBUT_REF.png) · [Fin](../04_Illustrations/references/PJ_TITO_FIN_REF.png) |
| Marée de Nuit | [Portrait](../04_Illustrations/references/PJ_MAREE_DE_NUIT_REF.png) |
| Personne | [Portrait](../04_Illustrations/references/PJ_PERSONNE_REF.png) |
| Sispéo | [Portrait](../04_Illustrations/references/PJ_SISPEO_REF.png) |
| Sultan | [Portrait](../04_Illustrations/references/PNJ_SULTAN_REF.png) |
| Truffino | [Portrait](../04_Illustrations/references/PNJ_TRUFFINO_REF.png) |

Planches complémentaires : [Psodia](../04_Illustrations/references/REF_PSODIA.png), [Tito](../04_Illustrations/references/REF_TITO.png), [Marée de Nuit](../04_Illustrations/references/REF_MAREE_DE_NUIT.png), [Personne et Truffino](../04_Illustrations/references/REF_PERSONNE_TRUFFINO.png), [Sispéo et Sultan](../04_Illustrations/references/REF_SISPEO_SULTAN.png).

La présence des fichiers sur GitHub ne garantit pas leur transmission directe au générateur d’images. Conserver les originaux haute définition et les références nécessaires dans les Sources.

## 7. LORE — Documentation officielle existante

Conserver les noms actuels. Documents recensés dans les Sources du projet BRANCA ; non présents sur le dépôt vérifié. Ne pas publier les documents commerciaux sans autorisation.

- `BRANCALONIA_Livre_1_Livre-de-base_FR_09-07-22.pdf`
- `BRANCALONIA_Supplement_1_Macaronicon_FR_09-07-22.pdf`
- `006_Un_monde_de_canailles.pdf`
- `Carte Brancalonia 1-1.pdf`
- `Turquoises, Féérie et Cocagne .pdf`

## 8. MJ — Documents de campagne existants

Documents recensés dans les Sources du projet BRANCA ; non présents sur le dépôt vérifié.

- `Chronologie.pdf`
- `Campagne saison 2 - Trame.pdf`
- `Du dit des nains et des elfes-1.pdf`
- `Liber Vetillæ.pdf`
- `Critiques culinaires.pdf`
- `Sibara - Ecoles de magie.pdf`
- `Le porte Malheur.pdf`

## 9. Règles de continuité et de validation

- Les documents du MJ ne constituent pas automatiquement des scènes jouées.
- Distinguer faits documentés, souvenirs, hypothèses des héros et propositions éditoriales.
- Respecter la chronologie des révélations, les transformations et les acquisitions d’objets.
- Ne jamais considérer une proposition comme validée sans confirmation.
- Signaler les contradictions dans le registre des points à confirmer.
- Préserver les originaux et utiliser Git pour l’historique des documents suivis.
- Ne pas divulguer prématurément les révélations dans les légendes, illustrations ou documents destinés aux lecteurs.

## 10. Jalons éditoriaux

- Fin janvier 2027 : édition PDF narrative de lecture à partager aux joueurs.
- Mars 2027 : objectif de remise du recueil illustré imprimé au MJ, au début de la troisième campagne.

Les répertoires `03_Ressources/`, `05_Maquette/` et `06_Publication/` restent à créer ou à alimenter selon les besoins. Aucun bestiaire systématique ni pipeline automatique n’est requis à ce stade.

## 11. Mode d’emploi

[00_MODE_EMPLOI.md](00_MODE_EMPLOI.md) — document historique de migration par ZIP, à actualiser pour le fonctionnement GitHub. En attendant sa révision, les règles de la section 1 du présent index constituent la proposition de fonctionnement courant.
