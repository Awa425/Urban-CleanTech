## Contraintes MVP — Pastef University

### Persona
Oumar, 42 ans — Chauffeur de camion-benne, 14 ans d'ancienneté · Parcelles Assainies, Dakar, Sénégal · Téléphone basique — appels et SMS uniquement

---

### Contraintes Non Négociables

#### Contrainte 1
**Critère :** Le MVP DOIT fonctionner intégralement via SMS ou appel vocal, sans nécessiter de smartphone, d'application mobile, ni de connexion data à aucune étape du parcours agent

**Origine :** Chapeau Blanc

**Élimine :** Toute interface mobile (application Android/iOS), tout formulaire web, tout système de géolocalisation GPS actif, toute notification push — autant de fonctionnalités inaccessibles à un téléphone basique

---

#### Contrainte 2
**Critère :** Le MVP DOIT produire une réponse visible et traçable à chaque signalement d'Oumar dans un délai maximum de 24 heures — que ce soit une confirmation de prise en compte, une modification de circuit ou un accusé de réception SMS

**Origine :** Chapeau Noir

**Élimine :** Tout système de collecte de données sans boucle de retour vers l'agent — les dashboards destinés uniquement aux managers, les outils d'agrégation sans confirmation terrain, les logiciels de BI déconnectés du terrain

---

#### Contrainte 3
**Critère :** Le MVP DOIT être co-construit avec au minimum 2 agents terrain (dont Oumar) lors d'une session de test avant tout déploiement, afin que le protocole de signalement soit perçu comme un outil d'appui et non de surveillance

**Origine :** Chapeau Noir

**Élimine :** Tout déploiement top-down imposé par la hiérarchie sans validation terrain préalable — les pilotes lancés sans formation ni consentement des agents, les systèmes de tracking de position en temps réel des agents

---

#### Contrainte 4
**Critère :** Le MVP NE DOIT PAS dépendre du crédit téléphonique personnel des agents pour fonctionner — le coût des SMS de signalement doit être nul ou remboursé par le projet

**Origine :** Chapeau Noir

**Élimine :** Tout modèle où l'agent supporte un coût financier pour signaler — les numéros surtaxés, les applications avec data payante, les solutions qui transfèrent la charge économique sur l'utilisateur le plus vulnérable de la chaîne

---

#### Contrainte 5
**Critère :** Le MVP DOIT pouvoir être opéré par un dispatcher humain (chef de dépôt ou coordinateur) sans outil numérique avancé — une feuille de calcul ou un tableau blanc suffit pour le back-office du pilote

**Origine :** Chapeau Blanc

**Élimine :** Tout back-office complexe nécessitant une formation longue, un algorithme d'optimisation automatique, ou une infrastructure serveur dédiée pour la phase pilote

---

### Fonctionnalités Éliminées

- **Application mobile de signalement** → éliminée parce qu'Oumar n'a pas de smartphone et que toute solution app-first exclut le profil d'agent le plus représentatif du terrain
- **Géolocalisation GPS en temps réel des camions** → éliminée parce qu'elle nécessite un smartphone, une connexion data permanente et un budget infrastructure hors de portée du MVP
- **Algorithme d'optimisation automatique des tournées** → éliminée parce que le back-office du pilote doit pouvoir tourner avec un dispatcher humain et un tableau Excel, sans dépendance technologique lourde
- **Dashboard manager en temps réel** → éliminée parce que sans boucle de retour vers l'agent, un outil orienté management seul aggrave le sentiment de surveillance sans apporter de valeur terrain
- **Système de tracking de position des agents** → éliminée parce qu'elle serait perçue comme un outil de contrôle disciplinaire, détruisant la confiance nécessaire à l'adoption du système par les agents
- **Notifications push et alertes in-app** → éliminées parce qu'elles supposent un smartphone et une connexion active, deux prérequis absents chez le persona principal
- **Inscription via formulaire web** → éliminée parce qu'elle crée une barrière d'entrée immédiate pour tout agent sans smartphone ni accès internet

---

### Critère de Validation Final

Le MVP est valide si et seulement si : Oumar peut signaler une zone critique depuis son téléphone basique en moins de 60 secondes, reçoit une confirmation de prise en compte dans les 24 heures, et déclare spontanément que le système lui est utile — sans avoir été formé plus de 10 minutes.