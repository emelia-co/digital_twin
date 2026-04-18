# digital_twin
*Conception et développement d’un jumeau numérique du système respiratoire pour l’optimisation personnalisée des paramètres de ventilation mécanique en réanimation*En réanimation, la ventilation mécanique est essentielle pour les patients en détresse respiratoire (ex : SDRA).

Cependant :
	•	Les réglages (PEEP, volume courant, FiO₂) sont souvent ajustés empiriquement
	•	Les poumons réagissent différemment selon le patient
	•	Un mauvais réglage peut provoquer un VILI (Ventilator-Induced Lung Injury)

D’où l’intérêt d’un modèle numérique personnalisé du poumon capable de simuler la réponse du patient à différents réglages.
 *Objectif général*

Développer un modèle mathématique personnalisé du système respiratoire (jumeau numérique) permettant de :
	•	Simuler la mécanique pulmonaire du patient
	•	Prédire la réponse à différents paramètres ventilatoires
	•	Aider à choisir les réglages optimaux
*Objectifs spécifiques*
	1.	Modéliser la mécanique respiratoire (compliance + résistance)
	2.	Estimer les paramètres individuels à partir des données patient
	3.	Simuler différents scénarios ventilatoires
	4.	Proposer un algorithme d’optimisation des réglages
