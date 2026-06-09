## Hypothèses de Validation — Pastef University

### HMW Définitif

**Comment pourrions-nous** permettre aux agents de collecte de Dakar de signaler les zones critiques en temps réel et intégrer leur expérience terrain dans l'optimisation des tournées, **afin de** réduire les passages à vide et maximiser l'impact de chaque circuit de collecte ?

---

### Hypothèses CRITIQUES
*(Si fausse → le MVP ne fonctionne pas)*

#### Hypothèse C1
**Affirmation :** Nous croyons qu'Oumar et les agents de collecte accepteront d'utiliser un système de signalement SMS si celui-ci a été conçu avec leur participation directe et s'il leur apporte un bénéfice visible (circuit ajusté, moins de reproches citoyens) plutôt que de les exposer à un contrôle disciplinaire

**Indicateur :** Nous le saurons si au moins 3 agents sur 5 utilisent le système de signalement de façon autonome pendant 5 jours consécutifs sans relance de l'équipe projet

**Méthode :** Co-design d'une session de 2h avec Oumar et 2 collègues pour définir ensemble les codes SMS, suivi d'un test terrain de 5 jours avec observation non participante

**Qui valide :** Oumar + 2 agents volontaires des Parcelles Assainies, observés par un membre de l'équipe Pastef University

**Délai S3 :** Semaine 1 (co-design) → Semaine 2 (test terrain) → résultat semaine 2

---

#### Hypothèse C2
**Affirmation :** Nous croyons qu'un responsable hiérarchique (chef de dépôt ou coordinateur de zone) est disposé à consulter les alertes SMS remontées par les agents chaque soir et à modifier au moins un circuit de collecte le lendemain matin en conséquence

**Indicateur :** Nous le saurons si le chef de dépôt consulte le récapitulatif des alertes et valide ou ajuste un circuit au moins 3 fois sur 5 jours de pilote, sans relance systématique de l'équipe projet

**Méthode :** Entretien de cadrage avec le chef de dépôt avant lancement pour obtenir un engagement formel, puis suivi quotidien du nombre de circuits modifiés sur la base des alertes reçues

**Qui valide :** Chef de dépôt du secteur Parcelles Assainies ou équivalent accessible à l'équipe

**Délai S3 :** Semaine 1 (entretien + engagement) → Semaine 2 (mesure sur 5 jours)

---

#### Hypothèse C3
**Affirmation :** Nous croyons qu'un SMS envoyé depuis le téléphone basique d'Oumar dans les Parcelles Assainies arrive de façon fiable au numéro centralisé du dispatcher, sans dépendance au crédit personnel de l'agent ni rupture de réseau bloquante

**Indicateur :** Nous le saurons si 90 % des SMS de test envoyés depuis 3 points différents du circuit d'Oumar sont reçus par le dispatcher dans les 5 minutes, sur 20 envois répartis sur 2 jours

**Méthode :** Test technique de fiabilité réseau — envoi de SMS codés depuis le téléphone d'Oumar (ou équivalent basique) vers un numéro dédié, avec horodatage de réception, sur un numéro gratuit entrant (SIM prépayée projet)

**Qui valide :** Membre technique de l'équipe Pastef University + Oumar comme opérateur terrain

**Délai S3 :** Semaine 1 — avant tout autre test, c'est le prérequis technique absolu

---

### Hypothèses IMPORTANTES
*(Si fausse → expérience dégradée mais MVP utilisable)*

#### Hypothèse I1
**Affirmation :** Nous croyons que les 14 ans d'expérience terrain d'Oumar lui permettent d'identifier et de nommer avec précision les zones critiques de son circuit en utilisant des codes simples (numéro de zone ou nom de quartier), sans formation longue ni support visuel

**Indicateur :** Nous le saurons si Oumar envoie des SMS de signalement correctement formatés (zone + niveau d'urgence) sans erreur lors de 8 tests sur 10 après une seule session d'explication de 10 minutes

**Méthode :** Session de formation express de 10 minutes suivie d'un jeu de rôle terrain — Oumar simule 10 signalements depuis son camion pendant une tournée réelle

**Qui valide :** Oumar, observé par un membre de l'équipe projet

**Délai S3 :** Semaine 1, lors de la session de co-design (Hypothèse C1)

---

#### Hypothèse I2
**Affirmation :** Nous croyons qu'un dispatcher humain peut gérer les alertes de 5 agents simultanément avec un simple tableau Excel ou un cahier structuré, sans outil numérique avancé, et produire un récapitulatif exploitable pour le chef de dépôt en moins de 30 minutes chaque soir

**Indicateur :** Nous le saurons si le dispatcher produit un récapitulatif complet et lisible en moins de 30 minutes lors de chacune des 5 soirées du pilote, sans assistance de l'équipe projet au-delà du premier jour

**Méthode :** Simulation à blanc d'une soirée de dispatch — un membre de l'équipe joue le rôle du dispatcher avec un flux de 5 SMS fictifs chronométrés, puis ajustement du modèle de tableau avant le pilote réel

**Qui valide :** Membre de l'équipe Pastef University en rôle de dispatcher, supervisé par le chef de dépôt

**Délai S3 :** Semaine 1 (simulation) → ajustement avant semaine 2

---

#### Hypothèse I3
**Affirmation :** Nous croyons que les citoyens des quartiers couverts par le pilote perçoivent une amélioration de la réactivité du service de collecte après 2 semaines de fonctionnement du système, même si les circuits ne sont modifiés qu'une fois sur deux

**Indicateur :** Nous le saurons si au moins 6 habitants sur 10 interrogés en fin de pilote déclarent que "le service a semblé plus réactif" ou "les déchets ont été ramassés plus vite qu'avant" lors d'un micro-sondage de 3 questions

**Méthode :** Micro-sondage oral de 3 questions auprès de 10 habitants proches des zones signalées, en fin de pilote semaine 2

**Qui valide :** Membre de l'équipe Pastef University, avec un questionnaire standardisé de 3 questions fermées

**Délai S3 :** Semaine 2, dernier jour du pilote

---

### Hypothèses SECONDAIRES
*(À valider après le MVP)*

#### Hypothèse S1
**Affirmation :** Nous croyons qu'un déploiement à 50 agents sur 10 quartiers produirait des données suffisantes pour convaincre la DGPD d'intégrer le système dans son protocole officiel de planification des tournées

**Indicateur :** Nous le saurons si un responsable DGPD accepte une réunion de présentation des résultats du pilote et formule une demande formelle de proposition d'extension

**Méthode :** Présentation des résultats chiffrés du pilote (taux d'utilisation, circuits modifiés, retours citoyens) lors d'une réunion institutionnelle post-MVP

**Qui valide :** Responsable opérationnel DGPD ou Direction de la Propreté de la Ville de Dakar

**Délai S3 :** Après la fin du pilote — à planifier en semaine 3 ou en S4

---

#### Hypothèse S2
**Affirmation :** Nous croyons que le modèle SMS peut être étendu aux agentes de collecte à pied (profil Fatou) avec le même protocole, sans adaptation majeure du système de codage ni du back-office dispatcher

**Indicateur :** Nous le saurons si Fatou utilise le système correctement dès la première semaine avec la même formation de 10 minutes, et si le dispatcher traite ses alertes sans créer de colonne ou de catégorie supplémentaire dans son tableau

**Méthode :** Intégration de 2 agentes à pied dans une extension du pilote post-MVP, avec observation comparative des taux d'erreur de signalement

**Qui valide :** Fatou + une collègue agente à pied, observées par l'équipe projet

**Délai S3 :** Post-MVP — semaine 3 si le calendrier le permet, sinon S4

---

### Priorité de Validation S3

La première chose à tester en S3 : **envoyer 20 SMS de test depuis le téléphone basique d'Oumar sur son circuit réel et mesurer le taux de réception** — si cette hypothèse C3 échoue, toutes les autres sont sans objet.