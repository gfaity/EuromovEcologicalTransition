# EuromovEcologicalTransition

Repertoire contenant les projets liés à la transition écologique du laboratoire Euromov DHM et en particulier ceux menés par le groupe des chercheurs verts.

## Phase2_survey
Le dossier Phase2_survey contient l'analyse des résultats de l'enquête réalisée pour connaître le degré d'adhésion des mesures de transition écologique qui ont été proposées par les membres du laboratoire pendant la phase 1 de l'enquête.

Les mesures proposées ont été nettoyées et triées par les membres du club des chercheurs verts, puis évaluées par les membres du laboratoire. Sur la base de cette évaluation, nous avons proposé un score d'adhésion à chaque mesure. Les scores d'adhésion de ces mesures ont ensuite été utilisés pour créer un panels progressif de scénarios de transition écologique allant d'un scénario peu ambitieux (aucun changement) à un scénario extrêmement ambitieux (toutes les mesures proposées sont mises en place). Pour faciliter l'étape 3 (vote du scénario à retenir), seul les scénarios 10%, 30%, 50% et 70% ont été retenus pour la suite.

### Organisation du répertoire
Les résultats bruts (anonymes) de l'enquête sont disponibles dans le dossier DAT.
Un exemplaire de l'enquête contenant les questions posées est disponible dans le dossier DOC.
Le traitement des résultats est disponible dans le dossier RES.
Le dossier RES contient le code d'analyse brut (.Rmd) et la présentation des résultats sous forme de markdown (.html).
**Pour voir la présentation des résultats, il faut télécharger le fichier Phase2_survey/RES/20230327_07h14_Phase2ResultsSurvey_apresCreationScenario.html, puis l'ouvrir dans un navigateur web pour afficher correctement le style de texte et les graphiques.**

### Score d'adhésion
Les scénarios ont été créés sur la base d'un score d'adhésion à chaque mesure, calculé grâce aux réponses des membres du laboratoire lors de l'enquête. Voici le détail du calcul du score d'adhésion :

Pour chaque question, un nombre d’adhésion est d’abord calculé comme le nombre de personnes ayant répondu “Oui” à la question multiplié par 2 + nombre de personnes ayant répondu “Oui, si nécessaire” multiplié par 1 + nombre de personnes ayant répondu “Non” multiplié par 0.
Le score d’adhésion est ensuite calculé comme le nombre d’adhésion divisé par le nombre de personnes ayant répondu “Oui”, “Oui, si nécessaire” et “Non” à cette question multiplié par 2. Ce résultat est multiplié par 100 pour obtenir le pourcentage.
Ainsi, le score d’adhésion est de :
- 0 si tout le monde réponds “Non”
- 50 si tout le monde réponds “Oui, si nécessaire”
- 50 si la moitié des personnes répondent “Oui” et l’autre moitié “Non”
- 50 si 1/3 des personnes répond “Oui”, 1/3 “Oui, si nécessaire”, 1/3 “Non”
- 62.5 si 1/2 des personnes répond “Oui”, 1/4 “Oui, si nécessaire”, 1/4 “Non”
- 100 si tout le monde répond “Oui”
Les personnes n’ayant pas répondu au sondage ou ayant répondu “Ne se prononce pas” sont donc exclus de ce calcul.

# Contact
Pour toute question, merci de contacter euromov.shift@gmail.com
