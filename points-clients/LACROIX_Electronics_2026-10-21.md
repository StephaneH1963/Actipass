# Point client – LACROIX Electronics

*Situation au 21/10/2026. Source : boîte mail Actipass (détail des 19-21/10 et historique de juillet à octobre 2026 par thème).*

## En bref

| Sujet | Site | Fournisseur | Statut | Urgence |
|---|---|---|---|---|
| Retards backlog JOVE / arrêt de production | Beaupréau (BPR) | JOVE | Lacroix a arrêté une production faute de PCB | 🔴 |
| Arrêt de ligne KION – 1022414F | BPR / Achats Chine | JOVE | Passage en aérien validé (5 lignes × 500 USD) | 🔴 |
| Hausse de prix SOMFY (top 10 PN) | France / Tunisie | JOVE | Offre JOVE attendue ce matin | 🔴 |
| Blocage des expéditions pour impayés (SOA) | Lacroix France | JOVE | Désaccord sur les conditions de paiement | 🔴 |
| Commande urgente 4200007357 – 1051136A | BPR | FIMA | HAL NP en retard, expédition annoncée le 20/10, non confirmée | 🟠 |
| PO 4501183790 – frais aériens de 200 USD contestés | BPR | JOVE | ✅ JOVE a annulé les frais le 21/10 et expédie en aérien | 🟢 |
| Relation JOVE / Lacroix (prix, service, allocation matière) | Groupe | JOVE | Escalade auprès de Wang Lu, sans réponse de fond depuis le 13/10 | 🔴 |
| Factures FIMA impayées par BPR | BPR | FIMA | 38 013 € échus (relance du 14/10) | 🟠 |
| 1039956B Bosch K40 – arrêt de ligne au 26/10 | Kwidzyn (PL) | JOVE | 4 527 pcs en stock, numéro de suivi demandé | 🟠 |
| Annulation 1030314D (25 kpcs) | Tunisie | JOVE | Annulée puis reprise (« continue production ») | 🟢 |
| 0310262700G (PO 4501173984) | BPR | JOVE | Dédouané, livraison prévue le 20/10 | 🟢 |

---

## 0. Historique de juillet à octobre 2026 : comment on en est arrivé là

### Chronologie

| Date | Événement |
|---|---|
| **03/07** | Pénurie de matière sur un PCB SOMFY (EVB IO 1027877, 400 kpcs/an, Kwidzyn). Lacroix (A. Meritan, C. Liu) demande des matières alternatives. Actipass propose Yinghua YH-8150GT et WAZAM H160HF (offre JOVE du 08/07 à environ 1,05 USD). Le client doit qualifier ces matières. |
| **10/07** | JOVE annonce une nouvelle hausse sur toutes les références pour les livraisons à partir du 01/07, valable jusqu'au 31/08. Elle repose sur l'hypothèse d'une hausse matière inférieure à 45 % au T3. En parallèle, JOVE durcit ses conditions : commandes acceptées seulement à moins de 3 mois, et aucun report une fois les pièces produites. |
| **15/07** | C. Liu refuse : la hausse moyenne est de +33 % alors que l'accord de juin prévoyait de ne répercuter que la part CCL au-delà de 10 %. |
| **20-22/07** | JOVE révise à +19,4 % en moyenne. **Lacroix accepte** (prix dans SAP au 20/07) en échange d'une **garantie de livraison sans décalage**. Lacroix demande aussi une règle pour l'avenir : pas de hausse si la matière augmente de 15 % ou moins, et au-delà, un taux unique pour toutes les références. |
| **03/08** | C. Castagnet invite JOVE au Supplier Day du 14/10, en tant que « partenaire historique ». |
| **10/08** | Visite de Cédric chez JOVE fin août, confirmée par Wang Lu. |
| **21/08** | JOVE annonce une nouvelle hausse (sept.-oct.), justifiée par la pénurie de prépreg (PP) et les cores de plus de 0,8 mm. |
| **25/08** | C. Liu refuse : JOVE demande +44 % depuis le 10/07, soit **+95 % au total**, ce que Lacroix juge « huge and not make sense ». |
| **28/08** | Réunion d'affaires JOVE / Lacroix. Priorité de Lacroix : les pénuries, qui s'aggravent depuis août, et les réponses tardives aux usines. Des écarts de stock en consignation (CMI) sont à nettoyer en Tunisie (2022-2025). |
| **31/08** | JOVE propose de nouveaux prix pour les expéditions du 01/09 au 30/11 : **CCL +30 % en 2 et 4 couches, +20 % en 6 couches et plus, PP +20 %**. |
| **02/09** | « Risk of Supply » : JOVE alloue la matière par client selon le volume de l'année passée, soit environ 2 800 m² par mois pour Lacroix. Actipass prévient que la crise matière peut durer jusqu'à fin 2027 et propose **FIMA en dépannage** pour les échantillons et les commandes urgentes. |
| **04/09** | C. Liu chiffre l'impact : **+73 % sur le prix PCB** au 01/09 et **+134 % cumulés depuis le RFQ 2026**. Le chiffre d'affaires passe d'environ 5,4 MUSD à 13,9 MUSD sur la période de référence. Lacroix conteste les +30 % de CCL de septembre, alors que KB n'annonce que +15 %. |
| **04-08/09** | **Escalade en Tunisie** (A. Ammar, O. Boughoula) : situation « catastrophique », risque d'arrêt de toutes les lignes, sujet remonté à la direction générale. Référence critique : **SOMFY 1035296A** (Situo II), à environ -98 kpcs en S46, sans date de livraison faute de matière. Atlantic, Socomec et d'autres références SOMFY sont aussi en rupture. **C. Castagnet escalade directement auprès de Wang Lu** (08/09). |
| **11/09** | Lacroix entre les nouveaux prix dans son système, valables du 01/09 au 01/12, sous conditions : justificatifs des fournisseurs de stratifié (lettres et factures) et **compensation de l'écart** à la prochaine négociation. |
| **14/09** | C. Liu calcule que l'allocation de 2 800 m² couvre presque les 2 900 m² nécessaires et que Lacroix commande environ 200 jours à l'avance. Lacroix **soupçonne JOVE d'avoir réalloué sa matière à d'autres clients** et liste ses clients finaux mécontents : **SOFREL, SOMFY, ATLANTIC, AKWEL (Renault) et Faurecia/Forvia (JLR)**, avec des pénalités d'arrêt de ligne pour les équipementiers automobiles. Lacroix demande l'implication de la direction de JOVE et des fournisseurs de stratifié. |
| **22/09** | M. Gronau (BPR) : le transport maritime prend désormais 2,5 mois et l'aérien payé par Lacroix ne peut plus être la règle. Elle demande des confirmations de commande systématiques. |
| **01/10** | Long échange avec Cédric. **JOVE est devenu le 1er fournisseur PCB de Lacroix**, mais avec la plus forte hausse du panel (environ +110 %, contre 70 à 80 % en moyenne et +40 % pour le moins cher). Les clients finaux font des comparaisons et trouvent JOVE **20 à 30 % plus cher** sur certaines références. Cédric **doute de la coopération**. |
| **01/10** | KION 1022414F : rupture prévue au 26/10. Lacroix demande un dépannage FIMA (504 pcs par semaine). |
| **05/10** | Offre FIMA pour le dépannage KION : 13,80 € l'unité DDP, à partir de mi-novembre, avec de la matière achetée en express chez Isola. |
| **06/10** | Analyse du backlog BPR par M. Cadoux : sur 123 commandes, 43 (35 %) ont été décalées sans justification. Lacroix exige de l'aérien aux frais de JOVE. |
| **08/10** | Stéphane écrit à Wang Lu : il demande des confirmations de commande sous 48 h, des réponses aux backlogs et aux demandes de prix, et plus de personnel autour de Vincy. Il pose aussi la question d'une matière « sacrifiée » au profit d'autres clients. |
| **12/10** | Forvia exige de Lacroix une justification détaillée des hausses sur 2 références. Fichier transmis à JOVE et rempli le 14/10. |
| **13/10** | Wang Lu se contente de transmettre à son équipe. Vincy répond : réponse aux mails urgents dans la journée, confirmations le samedi, mais **un plafond de crédit est dépassé de décembre à février** (+1 mois sur ces commandes) et **JOVE ne chiffre plus les nouveaux projets 2 et 4 couches**. |
| **13/10** | Règle sur l'aérien fixée par Actipass : commande passée dans les 36 semaines, expédition par mer. Retard du fait de JOVE et nouvelle date refusée par Lacroix, aérien aux frais de JOVE. Commandes antérieures à juillet, au cas par cas. |
| **13-15/10** | KION : Lacroix avance sur la **piste FIMA** (matière ITEQ IT158 TC/BS, résistante au CAF, vernis épargne XV501T). L'analyse du bureau d'études Lacroix est en cours. |
| **14/10** | **LACROIX Partners Day** à Beaupréau, auquel Stéphane assiste. |
| **15/10** | Stéphane refuse la logique de plafond de crédit et l'arrêt des chiffrages : « **We are the supplier that increases the prices the most and at the same time creates the most shortages** ». Il prévient que la hausse au 01/12 ne sera pas acceptée si elle reste supérieure à celle de la concurrence. |
| **16/10** | Nouvelle lettre à Wang Lu avec un benchmark sur **1039956B (Bosch)** : JOVE est à +90 % contre +35 %, +40 % et +59 % chez les concurrents. Avec une matière à +140 % depuis juin et un poids matière de 40 %, la hausse justifiée serait d'environ 56 %. Stéphane demande à Wang Lu : « **Is Jove still considering our customers as strategic?** » |
| **19/10** | Relance à Wang Lu. **Aucune réponse de fond à ce jour.** |
| **19-21/10** | Crise des prix SOMFY, blocage des expéditions pour impayés (SOA), aérien KION, arrêt de production à BPR (voir les sections suivantes). |

### Ce qu'il faut retenir

1. **Le contrat de confiance est rompu.** Lacroix a accepté des hausses supérieures au marché (environ +110 % contre 70 à 80 %) en échange d'une sécurité d'approvisionnement qu'elle n'a pas eue. Cédric Castagnet doute ouvertement de la coopération, et des clients finaux (SOMFY, Forvia) font des comparaisons et contestent les prix.
2. **Le prochain rendez-vous décisif est la révision du 01/12.** C'est la fin de la période de prix du 01/09 au 30/11. Lacroix attend les justificatifs matière promis le 11/09 et une **compensation** de l'écart. Une hausse jugée excessive serait refusée.
3. **La part de JOVE recule déjà au profit de FIMA**, via les dépannages KION et les flex-rigides. Mais FIMA a aussi des problèmes : réactivité d'Alfonso (« Tu ne réponds à aucune de mes demandes », 12/10), retard HAL sur 4200007357, et **38 k€ de factures BPR impayées**.
4. **Côté JOVE, il y a des limites structurelles** : allocation matière par client, plafond de crédit dépassé de décembre à février, arrêt des chiffrages 2 et 4 couches et une seule personne (Vincy) pour suivre le compte. Les engagements obtenus le 13/10 sont jugés insuffisants.
5. **Les flux financiers se tendent dans les deux sens** : JOVE bloque des expéditions pour impayés (119,8 kUSD selon JOVE, contesté par Lacroix) et FIMA relance sur 38 k€. C'est à surveiller pour ne pas ajouter une crise de trésorerie à la crise d'approvisionnement.

---

## 1. JOVE – backlog et pénuries à Beaupréau (BPR)

- **Interlocutrice unique côté Lacroix :** Mélodie Cadoux (EXT), depuis le 15/10. En copie : C. Liu, A. Meritan, S. Jeronimo, M. Gronau, A. Abidi, C. Castagnet.
- **Constat de Lacroix (06/10) :** sur 123 commandes confirmées pour fin 2026, presque toutes seront livrées en retard.
  - 66 sont en retard mais acceptées (53,6 %).
  - 43 (35 %) ont été décalées sans justification. **Lacroix demande qu'elles partent en aérien aux frais de JOVE**, comme convenu à la réunion S40.
  - 11 n'ont pas de date à cause de pénuries matière.
  - 3 sont hors du délai de 36 semaines.
- **Position achats (M. Gronau, 22/09) :** le transit maritime est désormais de 2 à 2,5 mois. Les délais confirmés doivent en tenir compte, et l'aérien payé par Lacroix ne doit plus être la règle.
- **Dernier échange (20/10) :** Lacroix n'avait pas reçu le fichier de suivi et indique **avoir dû arrêter une production faute de PCB**. JOVE (Cara) a renvoyé « JOVE 20.10.xlsx ».
  - Reste dû cette semaine : le fichier complété avec les numéros de suivi, la confirmation que toutes les commandes partent en aérien, et un **second fichier** (stock projeté, avec coûts et délais par mode de transport).
- **Réunions récurrentes :** « JOVE shortage in BPR » le mardi à 10h et « Jove revue » le jeudi à 10h30 (heure de Paris).

## 2. KION – 1022414F (arrêt de ligne)

- Il manquait 3 kpcs, plus 1 kpcs pour le 1er décembre. JOVE ne peut pas changer l'empilage en PP 7628 (tolérance d'épaisseur dépassée). La matière a été obtenue dimanche.
- **Validé le 20/10 par E. Chataigner (Program Leader) :** passage en aérien de 5 lignes, avec un surcoût de 500 USD par ligne.

| PO | Qté | ETD | ETA (aérien) |
|---|---|---|---|
| 4400005828-10 | 1 400 (environ 1 300 prêtes) | 24/10 | 31/10 |
| 4501173322-20 | 1 400 | 16/11 | 23/11 |
| 4501173334-10 | 1 400 | 16/11 | 23/11 |
| 4501173330-10 | 1 400 | 03/12 | 10/12 |
| 4501190627-10 | 1 400 | 20/12 | 03/01 |

- C. Liu demande d'avancer les 2 800 pcs de novembre d'une semaine. Il manquerait sinon 1 000 pcs au 10/12 et 1 000 pcs au 03/01.

## 3. SOMFY – hausse matière (CCL/PP)

- C. Castagnet a appelé le 19/10 : **la situation avec SOMFY est très tendue** et Lacroix ne peut pas attendre jeudi.
- **Cible :** une hausse de **+20 % maximum sur le prix PCB final**, calculée sur le prix précédent (expéditions de juillet-août, coût matière de juillet). Elle porte sur le top 10 des PN SOMFY en 2 et 4 couches : 1035296A, 1043698A, 1034315A, 1036186A, 1031763A, 1035532A, 0310309500B, 0310350200B, 0310290600A et 0310338400A.
- Les livraisons de septembre et octobre sont réglées par un avoir géré directement avec Carol. **La nouvelle offre ne concerne que les expéditions de novembre**, sur la base des prix matière d'octobre.
- **Action en cours :** l'offre JOVE (Vincy) est attendue **ce matin au plus tard**. Si +20 % n'est pas tenable sur certains PN, JOVE doit donner le détail de la hausse CCL/PP appliquée PN par PN.

## 4. Finance – relevé de compte JOVE / Lacroix France

- **JOVE (20/10) :** 66 lignes de factures de juin-juillet, pour un total d'**environ 119,8 kUSD**, seraient échues au 30/09 avec un paiement à 90 jours. **Le service financier de JOVE a bloqué les expéditions.**
- **Réponse de C. Liu :** le passage de 120 à 90 jours ne s'applique qu'aux factures émises à partir du 1er septembre. Avec 120 jours, ces factures ne sont pas encore toutes échues.
- **Risque :** si le blocage est maintenu, il aggrave directement les pénuries de BPR et de KION. Il faut faire trancher ce point rapidement entre JOVE et S. Dorso / C. Liu.
- À suivre aussi : JOVE a demandé à F. Aubriot (19/10) le détail d'un paiement de **154 397,71 USD**.

## 5. FIMA – commande urgente 4200007357 (PCB 1051136A)

- La commande a été passée le 01/10 avec un délai de 10 jours. L'expédition a été annoncée le 15/10, puis le 19/10, puis le 21/10, et finalement **le 20/10 après passage prioritaire en HAL NP**.
- E. Le Cardiec est très mécontent (« not acceptable »). Stéphane a relancé Alfonso (« il faut COMMUNIQUER »).
- **À faire :** aucune confirmation d'expédition ni numéro de suivi depuis le 20/10. Les obtenir de FIMA et les transmettre à E. Le Cardiec.
- **CP Desoutter 1052347A (rigide-flex, Lacroix France, 120 / 340 pcs, besoin supplémentaire de 180 pcs pour le 11/01) :** FIMA ne fait pas de finition HASL sur du flex, il faut donc passer en ENIG. Alfonso est en déplacement et propose de donner l'offre par téléphone. Une demande a aussi été envoyée à JOVE le 20/10.

## 6. Autres points opérationnels

- **PO 4501183790 (1050258A, 1050259A, 1050260A) :** M. Gronau demandait pourquoi **200 USD d'aérien** étaient facturés alors que le transport est inclus dans le prix unitaire. ✅ JOVE (Vincy) s'est excusé le 21/10, a annulé ces frais et expédie en aérien dès que possible.
- **1039956B Bosch K40 Heat Pump (Kwidzyn) :**
  - Le solde de 4501151571-10 (4 527 pcs, arrêt de ligne au 26/10) est en stock et devait partir le 20/10. K. Orkwiszewska attend le numéro de suivi.
  - Les lignes suivantes (4501168208, -169921, -172010 et -177845, de 7 956 pcs chacune) passent en aérien avec un surcoût de 1 550 USD chacune. ETA au 25/11 et au 10/12.
  - 594 pcs de DC 2602 en ENIG sont acceptables sous réserve d'un test de soudabilité et d'une dérogation.
- **1030314D – PO 4501160235/30 (25 kpcs, Tunisie) :** l'annulation demandée le 16/10 aurait coûté 83 803 USD de matière consommée. Lacroix a finalement demandé de **poursuivre la production** (19/10).
- **0310262700G – PO 4501173984 :** 1 380 pcs en aérien (surcoût de 2 000 USD validé par N. Louati). Arrivée le 13/10, dédouanée, livraison prévue le 20/10. Suivi : 936-02777342.
- **POKENODE 1051076A / 4400005945 :** nouvelle commande de Lacroix France, transmise à JOVE le 20/10.

## 7. Prises de commande (19-20/10)

- **Lacroix Poland (L. Golimowski) :** 4501214245, -214247, -214252, -214255, -214257, -214259, -214261, -214262, -214265, -214308, -215076, -215082 et -216462. Livraisons de juin à octobre 2027. Toutes ont été transmises à JOVE.
- **Lacroix France (S. Coreau) :** 4501216601 (livraison le 24/06/2027) et 4501216603 (le 17/06/2027).
- **Lacroix France :** 4400005945 (POKENODE).

## 8. Demandes de prix en cours

| Projet | Site | Statut |
|---|---|---|
| SOMFY Ilmo3 Low Carbon – 1052359A | Tunisie | Transmis à JOVE le 20/10 |
| DISTECH ECS Sensor (2 couches, budgétaire) | France | Transmis à JOVE le 20/10 |
| A35x (A352Out…) | Allemagne (Willich) | Transmis à JOVE le 20/10 |
| CP Desoutter 1052347A (rigide-flex) | France | FIMA / JOVE, voir §5 |
| DL4 – Lacroix Sofrel (15 pcs) | France | Reçu le 19/10 (E. Le Cardiec) |
| PCB 1032461 – demande complémentaire FIMA + JOVE | France | Reçu le 19/10 |
| 2609_L-ACOUSTICS LA7 Mainboard NPI | Kwidzyn | RFQ portail (19/10) |
| 2610_NICE GROUP SB815A1 A2 | — | RFQ portail (20/10) |
| SOCOMEC DX UL | BPR | Reçu de F. Trichet le 20/10 |
| Backlog NPI J. Kula – S43 | Kwidzyn | Reçu le 19/10 |

## 9. Actions prioritaires (Actipass)

1. **SOMFY :** obtenir l'offre JOVE ce matin et la transmettre à C. Castagnet et C. Liu, avec le détail CCL/PP si l'écart dépasse 20 %.
2. **Blocage financier JOVE :** faire lever le blocage des expéditions. Il faut aligner JOVE sur la position de Lacroix (90 jours seulement pour les factures émises à partir du 01/09) et organiser un échange entre JOVE, S. Dorso et C. Liu.
3. **BPR :** s'assurer que JOVE renvoie cette semaine les deux fichiers complétés (suivi des expéditions et confirmation de l'aérien, stock projeté). Préparer une position sur la demande d'aérien aux frais de JOVE pour les 43 commandes décalées.
4. **FIMA 4200007357 :** obtenir la preuve d'expédition et le numéro de suivi, puis les transmettre à E. Le Cardiec.
5. **PO 4501183790 :** confirmer à M. Gronau l'annulation des 200 USD et donner la date d'arrivée en aérien.
6. **Bosch 1039956B :** transmettre le numéro de suivi des 4 527 pcs à Kwidzyn avant l'arrêt de ligne du 26/10.
7. **KION :** obtenir de JOVE l'avancement d'une semaine des 2 800 pcs de novembre. Suivre aussi la décision de Lacroix sur la piste FIMA (IT158).
8. **Wang Lu / direction JOVE :** obtenir une réponse écrite aux courriers des 08, 16 et 19/10 (stratégie vis-à-vis de Lacroix, allocation matière, renfort de l'équipe), si besoin par un appel WeChat.
9. **Révision des prix du 01/12 :** préparer dès maintenant avec JOVE le dossier promis à C. Liu le 11/09 (lettres des fournisseurs de stratifié, factures, taux réels). Il doit inclure la compensation de l'écart de septembre à novembre et un positionnement compatible avec la concurrence.
10. **Chiffrages 2 et 4 couches :** obtenir de JOVE la reprise des chiffrages pour les clients existants (DISTECH, SOMFY Ilmo3 et autres). À défaut, orienter vers FIMA ou un autre partenaire.
11. **FIMA :** faire régler les 38 k€ échus par BPR (S. Jeronimo, A. Meritan) et mettre un cadre de réactivité avec Alfonso.
