# 🗑️ WasteTrackDakar

> **GET 409 · Atelier IA · Master · Swiss UMEF University — Campus de Dakar · 2025-2026**

---

## Le problème

Les quartiers de Dakar sont régulièrement victimes de **dépôts sauvages de déchets** faute d'un système de signalement efficace et de tournées de collecte optimisées. Les agents de la voirie opèrent sans données terrain, tandis que les citoyens n'ont aucun moyen de signaler un problème ou de connaître le passage du camion de collecte.

## Notre réponse

> **Comment pourrions-nous** permettre aux habitants de Dakar de signaler les dépôts sauvages de déchets en temps réel et aider les services de collecte à optimiser leurs tournées, afin de réduire l'insalubrité urbaine et améliorer la réactivité des services de propreté ?

---

## L'équipe

| Prénom | Nom | Rôle | GitHub |
|---|---|---|---|
| Mor | DIOUF | Chef de Produit (PM) | [@mordiouf](https://github.com/mordiouf) |
| Souleymane | DIALLO | Master Prompt Engineer | [@souleymane-diallo](https://github.com/souleymane-diallo) |
| Serigne Mor | DIAGNE | Dev UI (No-Code) | [@serignediagne](https://github.com/serignediagne) |
| Awa | DIOP | Responsable Impact | [@awadiop](https://github.com/awadiop) |

---

## Documentation

| Document | Description |
|---|---|
| [📋 Fiche équipe](docs/fiche-equipe.md) | Identité, membres, rôles, infrastructure S1 |
| [🗺️ Carte d'empathie](docs/carte-empathie.md) | Persona Aminata — pains, gains, insights |

---

## Prompts S1

<details>
<summary>Prompt 1 — Découverte du problème</summary>

```
Tu es un expert en gestion des déchets urbains et en services
municipaux à Dakar, Sénégal.

Identifie les 3 principaux problèmes que rencontrent les habitants
et les services de collecte face aux dépôts sauvages de déchets
dans le contexte dakarois (densité urbaine, informalité des quartiers,
ressources municipales limitées).

Pour chaque problème :
- La cause principale
- L'impact sur la vie quotidienne et la santé des habitants
- Une piste de solution technologique accessible (offline-first,
  compatible feature phones ou bas débit)
```

</details>

<details>
<summary>Prompt 2 — Guide d'interview</summary>

```
Tu es un UX Researcher spécialisé dans les services urbains
et l'innovation sociale en Afrique de l'Ouest.

Je dois interviewer [un habitant d'un quartier périphérique de Dakar
confronté quotidiennement aux dépôts sauvages de déchets —
smartphone basique ou entrée de gamme, connectivité 2G/3G intermittente]
face au problème :
[Il est impossible de signaler efficacement un dépôt sauvage
et les camions de collecte passent de façon imprévisible,
laissant les déchets s'accumuler pendant des jours.]

Génère un guide d'interview avec :
1. 3 questions d'ouverture (brise-glace)
2. 5 questions d'exploration en profondeur
   (avec 'Pourquoi ?' et 'Racontez-moi...')
3. 2 questions sur les aspirations attendues

Format : questions numérotées, courtes, sans jargon.
```

</details>

<details>
<summary>Prompt 3 — Générateur HMW</summary>

```
Tu es un facilitateur en Design Thinking.

Voici nos observations clés de l'interview :
Observation 1 : [Les habitants ne savent pas à qui signaler
                 un dépôt sauvage ni si leur signalement
                 sera pris en compte]
Observation 2 : [Les agents de collecte passent sans
                 information sur les points critiques du jour,
                 manquant les zones les plus urgentes]
Observation 3 : [Certains citoyens photographient les dépôts
                 et les publient sur WhatsApp pour alerter
                 la communauté, faute de canal officiel]

Frustration principale : [L'habitant de Dakar subit la dégradation
de son cadre de vie faute d'un canal simple pour signaler les dépôts
sauvages et d'une collecte réactive, ce qui génère un sentiment
d'impuissance et de désengagement civique.]

Génère 5 énoncés 'Comment pourrions-nous...' (HMW)
qui reformulent cette frustration en opportunité.

Critères : ni trop vague, ni trop précis,
ne propose pas encore de solution.
```

</details>

<details>
<summary>Prompt 4 — Carte d'empathie</summary>

```
# ROLE
Tu es un UX Researcher expert pour des projets
d'innovation sociale en Afrique.

## PERSONA
- Prénom, âge, profession : [Aminata, 35 ans, commerçante au marché de Thiaroye]
- Localisation : [Pikine, Dakar, Sénégal]
- Problème : [Elle vit à côté d'un dépôt sauvage récurrent,
               sans moyen d'alerter les services compétents
               ni de savoir quand le prochain camion passera]
- Équipement digital : [Smartphone Android entrée de gamme,
                        connexion 3G intermittente]

## OBSERVATIONS DE NOS INTERVIEWS
- Ce qu'il/elle a dit : ["J'ai appelé la mairie trois fois,
                          personne ne répond, les déchets sont
                          toujours là une semaine après"]
- Ce qu'il/elle a fait : [Poste des photos sur le groupe WhatsApp
                           du quartier pour mobiliser les voisins]
- Émotion principale : [Indignation mêlée de résignation]

## FORMAT STRICT
### 1. PENSE ET RESSENT  - [Insight 1]  - [Insight 2]
### 2. VOIT              - [Insight 1]  - [Insight 2]
### 3. ENTEND            - [Insight 1]  - [Insight 2]
### 4. DIT ET FAIT       - [Comportement]  - [Citation]
### 5. FRUSTRATIONS (Pains)  - [Douleur principale]
### 6. ASPIRATIONS (Gains)   - [Résultat désiré]
```

</details>

---

*Enseignant responsable : M. Malick Faye Diagne — GET 409 · Swiss UMEF University Dakar*
