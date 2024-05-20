# 1. Remerciements (h-s)

# 2. Fonctionnement de ce projet (h-s)
Avant de dévoiler les différents chapitres de notre projet, il nous a semblé nécessaire de l'introduire par l'approche que nous avons choisie pour son organisation. Ce projet de troisième année de bachelor a pour but de mettre en évidence notre capacité d'analyse, notre niveau de technicité, ainsi que notre maîtrise des aspects relatifs à la gestion de projet. Nous sommes conscients du caractère scolaire de cet exercice. Toutefois, dans un contexte réel de gestion de projet, l'architecture proposée ne serait pas applicable et pourrait engendrer des anachronismes, nuisant à l'alignement et à la précision des détails.

Pour aborder ce projet sous un angle le plus réaliste possible, nous avons identifié trois types de chapitres : les parties « simulations », les parties « hors-simulation », et les parties « futur de la simulation ». Chaque type est clairement indiqué dans les titres des chapitres par les mentions « s », « hs », et « fs » respectivement. Les parties simulations sont conçues comme si nous étions au sein de notre entreprise, CloudConsulting, et non plus en tant qu'étudiants d'Isitech. Les parties hors simulation permettent de prendre du recul par rapport à la situation fictive pour discuter et expliquer certains sujets en notre qualité d'étudiants. Enfin, le futur de la simulation nous permettra, par exemple, d'imaginer le délai de réalisation d'un projet jusqu'à sa réception définitive ou encore, un retour sur l'offre discuté avec le client tout en restant dans le cadre de la simulation. Le projet se révèle ainsi être une simulation réaliste et multi-temporelle d'un autre projet technique.

# 3. Méthodologie projet (h-s)

## 3.1. Choix méthode de gestion de projet (h-s)
Méthode agile, pourquoi? Pourquoi est-ce une mauvaise idée de faire ce projet avec une méthode traditionnelle (retour d'experience du projet de l'année précedente)

## 3.2. Outils de travail (h-s)
Pour chaque outils, il faut spécifier pourquoi et comment.
Pour entreprendre ce projet, nous nous sommes servis d'une liste d'outils qui nous ont facilité la construction de sa colonne vertébrale. Ils nous ont permit de travailler éficacement, de nous organiser correctement en équipe et de déployer notre infrastructure sans nous soucier du temps ou du coût. Dans cette section noys vous présentons ces outils.

### Notion
Pour méner un projet à terme, l'organisation et la repartition de taches priment, et notre formation en Bachelor RPI nous a incités à prendre cette partie sérieusement. Nous avons adopté Notion(1) pour ses capacités en gestion de tâches et collaboration en temps réel. Grâce à cette application, nous avons pu automatiser la création de tâches en sections que nous avons appelées "Épics", divisés aussi en sous tâches. Chaque collaborateur était ainsi assigné à une sous tâche lié à un état d'avancement. Une fois les tâches terminées et leur état d'avancement mis à jour, un nouvel Épic était lancé. Ainsi jusqu'à la finalisation du projet.

### GitHub / Git
Github(2) était fondamental pour achevement de ce projet. Offrant un environement de développement collaboratif et de stockage de code, cette plateforme nous a aidé à constituer ce rapport écrit, aussi que le projet technique que vous verrez dans les prochains paragraphes. Sa fonctionnalité de travail en simultané, revue(3) et validation du code par des collegues, nous a permit d'avoir un échange sur la qualité et objectivité de notre travail. Nous avons pu ainsi gravir des échelons en équipe pour aboutir ce projet de fin d'année.
D'un autre côté, GitHub nous a offert une visualisation de notre travail dans le temps, structurant un historique des versions du projet, idéal pour notre approche IaC(4) (Infrastructure-as-Code) en cas de complications dans le développement.

### AWS
AWS est la plateforme de services Cloud sur laquelle nous avons basé notre modernisation de SI. Elle offre tous 

OVH (ou autre ? c'est l'infra de base)
Terraform
Ansible
Docker

# 4. Cadre du projet
## 4.1. Genèse du projet (h-s)
Ici nous préciserons pourquoi nous avons choisi ce projet, les technologies que l'on à décider d'utiliser pour le bâtir. L'interet que nous lui avons porté et pourquoi? 

## 4.2. Equipe de projet (s)
Ici nous expliquerons nos trois rôles respectif comme si nous devions nous présenter au client.
 
## 4.3. Présentation de notre entreprise (s)
Bienvenue chez CloudConsulting, une entreprise en plein essor, composée de sept collaborateurs passionnés spécialisés dans la gestion de projets et la réalisation de chantiers cloud.

Fondée en 2017 par des visionnaires du cloud computing, CloudConsulting s'est rapidement développée pour devenir une équipe aguerrie, engagée, prête à relever les défis les plus complexes avec créativité et compétence.

Notre mission est claire : fournir des solutions personnalisées qui répondent précisément aux exigences spécifiques de nos clients en matière de cloud computing. L'engagement envers l'excellence technique, associé à une approche centrée sur le client, sont les piliers de notre développement.

Nous avons démarré modestement à Lyon avec seulement trois personnes. Aujourd'hui, notre croissance nous a permis d'élargir notre offre et notre portée géographique. CloudConsulting propose désormais une gamme complète de services, y compris la gestion de projets et la mise en œuvre de solutions cloud.

En 2023, nous avons atteint un chiffre d'affaires de 2 millions d'euros, une preuve tangible de la confiance et de la satisfaction de nos clients. Cette réussite résulte de notre dévouement constant à la qualité, à l'innovation, ainsi qu'à l'excellence opérationnelle.

Chez CloudConsulting, nous sommes fiers de notre parcours et prêts à répondre aux besoins émergents de nos clients. Nous sommes impatients de partager notre expertise avec vous et de faciliter votre transition vers le cloud.

## 4.4. Présentation entreprise cliente (s)
(Un bref résumé de leur entreprise, leur domaine d'activité, un petit historique et quelques chiffre lié à leur activité.)

Fondée en 2023 par une petite équipe de jeunes developpeurs passionnés de cinéma, l'entreprise **EduLearn** fait une entrée remarquée sur le marché de l'éducation en ligne avec une approche créative. Ayant pour objectif premier de rendre l'apprentissage des differentes langues interessante pour tous, leur site web a intègré avec succès des contenus cinématographiques sous forme d'exercices, fusionnant ainsi éducation et divertissement pour une approche pédagogique captivante. EduLearn a connu une ascension fulgurante. Aujourd'hui, le site enregistre plus de 300 connexions par semaine, générant un chiffre d'affaires de 25 000€ depuis sa création.

L'année 2024 a débuté avec beaucoup de promesses pour EduLearn. Leur participation au **Sommet d'Enterpreneurs & Croissance** en mars était fructueuse, ils ont raméné le trophée d'argent ainsi qu'une somme d'argent pour investir. Cette victoire leur a ouvert les portes d'un partenariat avec l'État français, qui leur a permit d'integrer ses services d'apprentissage en ligne aux programmes de plus de 2 160 élèves dans les 20 écoles pilote.

## 4.5 Interlocuteur client (s)
Ici nous ferons un rappel des partie prenants côté client, leur rôle et leurs coordonées. Existe réellement en entreprise et sert à se référer au bonnes personnes en cas de besoins.

## 4.6. Contexte du projet (s)
Nous détaillerons le résumé de ce pourquoi le client nous à contacter, les enjeux et le contexte de mnière global

# 5. Cahier de charges (s)
## 5.1 Présentation TQC
## 5.2 Identification des besoins
## 5.3 Objectifs
## 5.4 Contraintes
### 5.4.1 Humaines
### 5.4.2 Techniques
### 5.4.3 Budgétaire
### 5.4.4 Légales/règlementaires
### 5.4.5 De temps
### 5.4.6 Liées à la maintenance et à l’évolutivité
### 5.4.7 Géographiques

# 6. Etude de marché (s)
## 6.1 Analyse de la concurrence
## 6.2 Étude micro-économique
## 6.3 Étude macro-économique
## 6.4 Matrice SWOT
## 6.5 Pestel

# 7 Rédaction de l'offre (s)
## 7.1 Solution proposée 

## 7.2 Perspective d’évolution

## 7.3 Planning

## 7.4 Chiffrage & jalons de paiment

## 7.5 Légal
### 7.5.1 Périmètre du projet
### 7.5.2 Engagement client

# 8 Point commercial et validation (h-s)
Explication en mode hors simulation de comment s'est passé la présentation de notre offre, est ce que le client à accepter directement? Comment a t'il réagit? Est-il d'accord sur tout les aspects? 

# 9 Réalisation (futur de la simutation )
Description technique de tout ce que nous avons réalisé.

# 13 Clôture du projet (h-s)
Point hors simulation pour expliquer comment la fin du projet c'est terminé, si ils ont signé le PV de reception def. immédiatement ou il y eu une ou plusieurs réserve à lever pour finaliser? Ne pas hésiter à être imaginatif et creuser dans le détail de ce que le client aurait pu redire. (sans se mettre une balle dans le pied, en montrant que ce n'est pas de notre faute, en ajoutant un avenant par exemple).

# 14 Conclusion (h-s)

# 15 Annexe 

# 13. Clôture du projet

# 14. Conclusion

# 15. Annexe

# 16. Bibliographie

1. "Notion: c'est quoi et comment l'utiliser au quotidien ?".
   https://www.dixmilleheures.fr/outils/notion

2. "Qu’est-ce Que GitHub ? Présentation de GitHub pour un Débutant".
   https://kinsta.com/fr/base-de-connaissances/base-de-connaissances-github/

3. "À propos des demandes de tirage (pull requests)".
   https://docs.github.com/fr/pull-requests/collaborating-with-pull-requests/proposing-changes-to-your-work-with-pull-requests/about-pull-requests

4. "L'IaC (Infrastructure-as-Code), qu'est-ce que c'est ?".
   https://www.redhat.com/fr/topics/automation/what-is-infrastructure-as-code-iac