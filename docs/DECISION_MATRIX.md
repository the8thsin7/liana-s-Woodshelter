# Matrice de décision

## Finalité
La matrice aide à hiérarchiser des dossiers et des actions sans masquer les choix derrière un texte long. Elle ne prétend pas supprimer le jugement humain : elle le rend explicite, comparable et révisable.

## Échelle commune
Chaque critère reçoit une note de 0 à 5.
- 0 : nul, absent ou défavorable
- 1 : faible
- 2 : limité
- 3 : moyen
- 4 : fort
- 5 : déterminant

## Critères par défaut
| Critère | Question mesurable | Poids par défaut |
|---|---|---:|
| Urgence / échéance | Y a-t-il un délai proche ou une perte si rien n’est fait ? | 5 |
| Impact | Quel gain, protection ou dommage évité est en jeu ? | 5 |
| Réversibilité / risque | Une inaction ou mauvaise décision est-elle difficile à corriger ? | 4 |
| Preuve disponible | Les éléments sont-ils suffisamment documentés ? | 3 |
| Faisabilité immédiate | Peut-on obtenir un résultat avec les ressources actuelles ? | 3 |
| Effort / charge | Quel est le coût de temps, d’énergie ou d’argent ? Note inversée : 5 = faible effort. | 2 |
| Valeur stratégique | L’action débloque-t-elle plusieurs sujets ou protège-t-elle une trajectoire ? | 3 |
| Incertitude | Ce qui manque empêche-t-il de décider ? Note inversée : 5 = incertitude faible. | 2 |

## Calcul
Pour chaque option :
\[ Score = \sum(note_i \times poids_i) \]

Score maximal par défaut : 135. On compare surtout les options entre elles ; le score n’est pas une vérité autonome.

## Seuils d’action
| Situation | Règle |
|---|---|
| P0 | Échéance critique ou risque irréversible : traiter immédiatement, même si le score est incomplet. |
| P1 | Score élevé et action faisable : planifier une action dans les 7 jours. |
| P2 | Score intermédiaire : conserver, compléter les preuves ou programmer. |
| P3 | Score faible, effort excessif ou faible preuve : parking, sans rumination. |

## Matrice de travail
| Option / dossier | Urgence ×5 | Impact ×5 | Risque ×4 | Preuve ×3 | Faisabilité ×3 | Effort ×2 | Stratégie ×3 | Certitude ×2 | Total /135 | Priorité | Prochaine action |
|---|---:|---:|---:|---:|---:|---:|---:|---:|---:|---:|---|---|
|  |  |  |  |  |  |  |  |  |  |  |  |

## Contrôle anti-biais
Avant de retenir le résultat :
- Vérifier si une note reflète un fait ou seulement une préférence.
- Écrire la source qui justifie toute note de 4 ou 5.
- Créer au moins une option « ne rien faire maintenant » lorsque c’est pertinent.
- Distinguer l’importance émotionnelle du risque objectif ; les deux peuvent exister, mais ne doivent pas être confondus.
- Recalculer lorsque survient un document, une réponse ou une nouvelle échéance.

## Format décision rapide
```text
Dossier :
Décision à prendre :
Options :
Faits sourcés :
Incertitudes :
Score / priorité :
Décision provisoire :
Action suivante :
Responsable :
Échéance / relance :
```
