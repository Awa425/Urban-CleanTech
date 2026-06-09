## Métriques de Succès — Pastef University

### MVP
Système de signalement SMS permettant à Oumar de signaler une zone critique depuis son téléphone basique en moins de 60 secondes, avec confirmation de prise en compte dans les 24 heures, sans formation de plus de 10 minutes.

---

### ⭐ Métrique Nord

**Indicateur :** Taux de circuits modifiés le lendemain d'un signalement — proportion de jours où au moins une zone critique signalée par un agent a entraîné un ajustement concret du circuit de collecte le jour suivant

**Valeur cible à 30 jours :** 60 % des signalements entraînent un ajustement de circuit dans les 24 heures

**Comment mesurer :** Cahier de bord tenu par le dispatcher — une ligne par signalement reçu, une colonne "circuit modifié oui/non", relu chaque vendredi par le chef de dépôt et un membre de l'équipe projet

---

### 📈 Métriques de Progression

#### Métrique P1
**Indicateur :** Taux d'utilisation autonome du système — nombre de jours consécutifs où Oumar envoie au moins un SMS de signalement sans relance de l'équipe projet

**Valeur cible à 30 jours :** 5 jours consécutifs d'utilisation autonome sans relance

**Comment mesurer :** Journal des SMS reçus sur le numéro dispatcher — l'équipe coche chaque jour avec ou sans relance de sa part, conservé dans le cahier de bord du pilote

---

#### Métrique P2
**Indicateur :** Délai moyen de confirmation — temps écoulé entre l'envoi du SMS de signalement par l'agent et la réception de l'accusé de réception par le dispatcher

**Valeur cible à 30 jours :** 100 % des signalements confirmés en moins de 24 heures, avec une médiane sous les 4 heures en semaine 4

**Comment mesurer :** Horodatage manuel dans le cahier de bord — heure d'envoi notée par l'agent sur son téléphone, heure de réception notée par le dispatcher à la réception, écart calculé en fin de journée

---

#### Métrique P3
**Indicateur :** Score de confiance agent — déclaration spontanée d'Oumar sur l'utilité perçue du système, recueillie lors d'un entretien informel de 5 minutes en fin de semaine

**Valeur cible à 30 jours :** Oumar déclare spontanément que le système "lui est utile" ou "a changé quelque chose" lors de l'entretien de fin de pilote, sans que la question soit suggestive

**Comment mesurer :** Entretien de 5 minutes chaque vendredi avec une seule question ouverte — "Est-ce que ce système a changé quelque chose dans ta semaine ?" — réponse notée mot pour mot dans le cahier de bord, sans reformulation

---

### 🚨 Métriques d'Alerte

#### Alerte A1
**Signal :** Taux de non-réponse hiérarchique — nombre de signalements consécutifs sans aucune modification de circuit ni accusé de réception du chef de dépôt

**Seuil :** 3 signalements consécutifs sans réponse ni ajustement → le système devient une boîte noire, risque d'abandon imminent par les agents

**Action corrective :** Réunion d'urgence avec le chef de dépôt dans les 48 heures pour identifier le blocage — si l'engagement ne peut pas être réactivé, suspendre le pilote plutôt que de laisser les agents envoyer des alertes ignorées

---

#### Alerte A2
**Signal :** Taux d'échec technique SMS — proportion de SMS de signalement envoyés par Oumar qui ne sont pas reçus par le dispatcher dans les 60 minutes

**Seuil :** Plus de 2 SMS non reçus sur une même semaine — la fiabilité du canal est compromise, le système n'est plus utilisable comme outil de signalement en temps réel

**Action corrective :** Test immédiat de couverture réseau sur les zones concernées — si le problème est localisé, définir un point de relais fixe (appel vocal en secours) ; si généralisé, basculer sur un protocole appel vocal uniquement pour les zones mortes

---

### Tableau de Bord S6

À la démo S6, nous présenterons ces 3 chiffres :

1. **Métrique Nord** — % de signalements ayant entraîné un ajustement de circuit dans les 24h · Cible : 60 % · Valeur réelle : [à compléter]
2. **Métrique P1** — Nombre de jours consécutifs d'utilisation autonome sans relance · Cible : 5 jours · Valeur réelle : [à compléter]
3. **Alerte A1** — Nombre de signalements consécutifs sans réponse hiérarchique · Seuil critique : 3 · Déclenchée : oui / non