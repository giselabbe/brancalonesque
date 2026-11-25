# Branca — Index général du recueil

Version 2.2 — 25 novembre 2026 — choix éditoriaux et direction chromatique.

Cet index est le point d’entrée du projet éditorial BRANCA, recueil illustré de la deuxième campagne de Brancalonia.

## 1. Organisation et source de vérité

Le [dépôt GitHub brancalonesque](https://github.com/giselabbe/brancalonesque), branche `main`, constitue le référentiel maître des documents qui y sont intégrés. Deux projets ChatGPT complémentaires l’utilisent :

- **BRANCA** : reconstitution de la campagne, rédaction et continuité narrative.
- **BRANCA Illustrations** : direction artistique, portraits, scènes, ornements et préparation graphique.

Consulter les fichiers pertinents sur GitHub avant chaque travail. Les versions distantes priment sur les anciennes copies des Sources, sauf indication explicite. Les documents et images absents du dépôt restent à consulter dans les Sources ou auprès de l’utilisateur. GitHub n’est pas synchronisé automatiquement dans le contexte ChatGPT.

Par défaut, ChatGPT consulte le dépôt en lecture seule ; les modifications et commits directs sont possibles sur autorisation explicite de l’utilisateur, limitée au périmètre convenu. Les références visuelles validées restent prioritaires pour les illustrations ; les joindre à la génération si nécessaire.

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
| I — Sourcemolle | [CH01_chapitre01_Sourcemolle_trame.md](../02_Manuscrits/Trames/CH01_chapitre01_Sourcemolle_trame.md) | Récit V2 ; validation finale à confirmer |
| II — Scanzona | [CH2_chapitre02_Scandoza_trame.md](../02_Manuscrits/Trames/CH2_chapitre02_Scandoza_trame.md) | Synthèse neutre |
| III — La traversée vers Sibara | [CH3_chapitre03_les_Pirates_trame.md](../02_Manuscrits/Trames/CH3_chapitre03_les_Pirates_trame.md) | Version de travail 3 |
| IV — Sibara, le bois de Bologne et la réparation de la péniche | [CH4_chapitre04_Vetille_trame.md](../02_Manuscrits/Trames/CH4_chapitre04_Vetille_trame.md) | Chronologie de travail ; questions ouvertes |
| V — Pandosia et le Liber Vetillæ | [Partie 1](../02_Manuscrits/Trames/CH5_chapitre5_Pandosia_partie_1_trame.md) · [Partie 2](../02_Manuscrits/Trames/CH5_chapitre_05_Pandosia_partie_2_trame.md) | Arc terminé ; rédaction définitive à faire |
| VI — La Marmite de Saint Glaude (titre de travail) | À intégrer | Prochain chapitre ; reconstitution à poursuivre |

Les arcs ultérieurs restent à consolider. Conserver les graphies des titres de travail en attendant leur harmonisation.

## 5. GRAPH — Référentiels graphiques

Référentiels disponibles dans [Graphisme/](Graphisme/) :

- [Charte](Graphisme/GRAPH_01_Charte.md) ; [prompts maîtres](Graphisme/GRAPH_03_Prompts_maitres.md) ; [bibliothèque historique](Graphisme/GRAPH_03_Illustrations.md).
- Registres de scènes : [I — Sourcemolle](Graphisme/GRAPH_05_Prompts_CH01_Sourcemolle.md), [II — Scanzona](Graphisme/GRAPH_02_Prompts_CH02_Scanzona.md), [III — Traversée](Graphisme/GRAPH_03_Prompts_CH03_Traversee_Sibara.md), [IV — Vétille](Graphisme/GRAPH_05_Prompts_CH04_Vetille.md), [V — Pandosia](Graphisme/GRAPH_05_Prompts_CH05_Pandosia.md).
- [Décoration](Graphisme/GRAPH_04_Decoration.md), [lieux](Graphisme/GRAPH_06_Lieux.md), [accessoires](Graphisme/GRAPH_07_Accessoires.md), [couverture](Graphisme/GRAPH_08_Couverture.md), [suivi](Graphisme/GRAPH_09_Suivi.md).
- Ancienne bible visuelle `GRAPH_02_Personnages.md` : document historique des Sources, non présent sur GitHub ; utiliser les fiches individuelles pour les références actuelles.

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

Autres références : [échelle de la clique](../04_Illustrations/references/REF_03_Clique_Echelle.png), [Ondine](../04_Illustrations/references/PNJ_ONDINE.jpg), [reine des elfes](../04_Illustrations/references/PNJ_REINE_DES_ELFES.jpg), [croquis](../04_Illustrations/croquis/).

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

## 10. Choix éditoriaux et jalons

Décisions du 25 novembre 2026 : chronique picaresque illustrée, concise et accessible aux joueurs, plutôt qu'un roman développé ; format fini carré **20 × 20 cm** ; intérieur en couleurs. Objectifs indicatifs : 20 000 à 30 000 mots, 120 à 160 pages, 30 à 50 grandes illustrations, complétées de croquis au graphite, vignettes et ornements Renaissance. Couverture rigide mate souhaitée ; tirage envisagé de 5 à 10 exemplaires. Papier, reliure, fond perdu et devis à confirmer auprès de l'imprimeur.

Direction graphique : grandes scènes aux couleurs plus vives, sans dominante parchemin systématique ; effet parchemin et aquarelle réservé principalement aux vignettes. Voir la [charte graphique](Graphisme/GRAPH_01_Charte.md) pour les règles de production. Le dépôt conserve la mémoire détaillée de la campagne ; le livre en propose une sélection fidèle, vivante et agréable à feuilleter.

### Jalons

- Fin janvier 2027 : édition PDF narrative de lecture à partager aux joueurs.
- Mars 2027 : objectif de remise du recueil illustré imprimé au MJ, au début de la troisième campagne.

Les répertoires `03_Ressources/`, `05_Maquette/` et `06_Publication/` restent à créer ou à alimenter selon les besoins. Aucun bestiaire systématique ni pipeline automatique n’est requis à ce stade.

## 11. Mode d’emploi

Le document historique `00_MODE_EMPLOI.md` (migration par ZIP) n’est pas présent dans le dépôt. Les règles de la section 1 du présent index constituent le mode de fonctionnement courant.
