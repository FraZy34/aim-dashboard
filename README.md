# Aim Dashboard — Valorant & Kovaak's

Application Windows (un seul `AimDashboard.exe`) pour suivre ses progrès en aim, avec la **régularité** comme métrique centrale : points forts et faibles, échauffement et plan d'entraînement adaptés à tes résultats (playlists Kovaak's envoyées directement dans le jeu), suivi des sessions et impact de la forme et du mental.

Ce dépôt ne contient que les versions publiées de l'application.

## ⬇️ Télécharger et lancer

**[➡️ Télécharger la dernière version (AimDashboard.exe)](https://github.com/FraZy34/aim-dashboard/releases/latest/download/AimDashboard.exe)**

1. **Télécharge** `AimDashboard.exe`, range-le où tu veux (Bureau, dossier Jeux…) et **double-clique dessus**. Rien à installer : tout est inclus dans le fichier.
2. **Si Windows affiche « Windows a protégé votre ordinateur »** : *Informations complémentaires* → *Exécuter quand même* (programme sans signature payante, une seule fois).
3. **Active ta licence** (voir ci-dessous), puis laisse-toi guider par le **Guide de démarrage**.

**Mises à jour :** automatiques. Quand une nouvelle version sort, une fenêtre te propose « Mettre à jour maintenant » ; l'application se met à jour et redémarre toute seule. Tes données sont conservées.

> Configuration requise : Windows 10 ou 11, 64 bits.

## 🔑 Licence

Aim Dashboard s'utilise avec une **licence personnelle**.

1. Au premier lancement, la fenêtre *Activer Aim Dashboard* affiche le **code de ton PC** (ex. `7U4W-NA2R-4YS6-ZCC7`) : clique sur *Copier*.
2. Envoie ce code à **FraZy34** pour obtenir ta licence.
3. Colle la **clé de licence** reçue (elle commence par `AIMD-`) et clique sur *Activer*.

La licence est vérifiée sur ton PC, sans compte et sans connexion obligatoire. Elle est liée à ton PC : pour un autre PC, demande une licence pour ce PC. Le code du PC est une empreinte : il ne contient aucune information personnelle.

![Vue d'ensemble](docs/vue-ensemble.png)
## Fonctionnalités

| Page | Contenu |
|---|---|
| **Vue d'ensemble** | K/D, ACS, ADR, HS%, KAST, win rate, FB/partie et régularité, avec la tendance par rapport à la période précédente (7 j, 30 j, ou par acte). Graphique de l'ACS par partie et tableau par acte. Alerte « pause conseillée ». |
| **Progression** | Rapport de chaque semaine (ranked, RR, Kovaak's, sessions, objectifs, pistes pour la semaine suivante), exportable en HTML imprimable en PDF ; courbe de rang et de RR ; records personnels (notification à chaque record battu) ; meilleures conditions de jeu (créneau, jour, nombre de parties avant de décrocher) ; progression Kovaak's par famille sur le long terme. |
| **Régularité** | Écart-type et coefficient de variation de l'ACS, du K/D et du HS% ; score de régularité sur 100 ; moyenne glissante avec bande min/max ; évolution du score ; 5 meilleures et 5 pires parties, et **ce qui les différencie** (HS%, entry, KAST, fatigue, tilt, échauffement, rang de la partie dans la journée, map, agent). |
| **Analyse Valorant** | Ta place dans chaque partie face aux autres joueurs (classement, top frag, ACS et HS% vs le lobby), solo ou en groupe, kills par arme (Vandal / Operator…), économie (pistolet, eco, force, full), trades, clutchs (1vX), moment de tes morts, stats par agent et par map, attaque/défense, entry et corrélation first death / issue du round. |
| **Analyse Kovaak's** | Progression par scénario (score, précision, kills/s, TTK moyen), filtre par type (clicking, tracking, flicking, switching), meilleur score et moyenne des 7 derniers jours, régularité et tendance par scénario. |
| **Points forts / faibles** | Moteur de règles lisible ; chaque point faible est expliqué en une phrase et relié à un axe de travail. |
| **Échauffement du jour** | Routine de 15 à 20 min avant la ranked (range, tracking, clicking, counter-strafe, duels) adaptée aux points faibles, avec sa **playlist Kovaak's** envoyée dans le jeu ; une case par bloc ; la séance validée compte comme « échauffement fait » dans le journal. |
| **Plan de la semaine** | 3 à 7 vraies séances (30 à 90 min) réparties sur la semaine selon tes points faibles. Chaque séance = une **playlist Kovaak's écrite directement dans le jeu** (tes scénarios en stagnation d'abord, puis des scénarios connus) + un bloc Valorant + un objectif chiffré. Séance « bilan » en fin de semaine. |
| **Adaptation automatique** | Chaque scénario reçoit un mode selon tes résultats : **Précision** (trop de tirs ratés : ralentis), **Pousser** (précision bonne mais score bloqué : accélère), **Consolider** ou **Découverte**, avec un objectif chiffré **atteignable**, calculé sur tes propres résultats (entre ta moyenne récente et ton record, précision +3 points max) et le niveau de difficulté adapté. **Boucle de retour** : l'application mesure si tes séances Kovaak's améliorent vraiment tes parties du même jour, et donne plus de place à ce qui marche. Le plan se **réajuste chaque jour** (séances manquées reportées), cible ta **pire map**, et l'échauffement s'adapte à ta **forme du jour** (version courte si fatigué ou alerte pause). Seuils de HS% adaptés à ton **rang** (lu automatiquement via HenrikDev). Suivi des **benchmarks Voltaic**. |
| **Sessions suivies** | Bouton **Démarrer une session** (forme, humeur et durée prévue) : un **échauffement adapté est généré à chaque démarrage** (points faibles, dernier bilan, alerte pause, forme, humeur, durée), envoyé dans Kovaak's et ouvert directement. Puis, puis **Terminer** (forme et humeur à la fin) : l'application prend toutes les parties classées jouées entre les deux et rédige un **bilan** : résultats vs ta moyenne, évolution pendant la session, forme et tilt, l'échauffement Kovaak's fait juste avant était-il adapté, et ce que le prochain échauffement va changer (l'axe à corriger passe en priorité). Une partie arrivée après la fin met le bilan à jour automatiquement. |
| **Mental et forme** | ACS selon la fatigue, le tilt et l'échauffement, corrélations et conclusions en phrases. |
| **Objectifs** | Objectifs chiffrés (HS%, K/D, ACS, ADR, KAST, win rate, régularité, score Kovaak's) avec barre de progression. |
| **Saisie** | Formulaire rapide pour une partie, import CSV/JSON avec modèles fournis, journal de session, paramètres. |

![Guide de démarrage](docs/guide.png)

## Tes données

Tout reste sur ton PC (`%APPDATA%\AimDashboard`) : base de données, réglages et clé API. Les seules connexions sont l'API HenrikDev (si tu l'actives, avec ta propre clé gratuite) et GitHub pour les mises à jour. L'application ne fait aucun scraping de sites qui l'interdisent (pas de tracker.gg).

Aim Dashboard n'est ni développé ni soutenu par Riot Games ou Kovaak's.

---
© 2026 FraZy34 — tous droits réservés. Voir [LICENSE](LICENSE).