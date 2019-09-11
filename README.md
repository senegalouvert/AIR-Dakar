# AIR-Dakar
Données sur la qualité de l'air à Dakar, Sénégal

## Qu'est ce que l'IQA ?
L’indice de qualité de l’air (IQA) indique l’état journalier de la qualité de l’air. Il renseigne sur le niveau de pollution de l’air et les impacts sanitaires qui peuvent en découler après quelques minutes ou des jours après l’exposition à la pollution atmosphérique.

## Comment l'IQA est il calculé ?
L’indice pour un polluant donné correspond à sa concentration exprimée en pourcentage de sa valeur limite.
```
IQA = (Concentration du Polluant / valeur limite du Polluant)*100
```
Les valeurs limites d’immissions de polluants ont été établies par l’Association Sénégalaise de Normalisation.

Pour évaluer la qualité de l'air globale pour une station de surveillance particulière, un indice est calculé pour chaque polluant mesuré et le maximum est considéré comme l'indice de qualité de l'air pour cette station de surveillance, car il représente le plus mauvais des polluants mesurés.

## Que signifient les classes de l'IQA ?

<span style="color:#00ff00">**Bon**</span> : l’IQA est satisfaisant et la pollution de l’air pose très peu ou pas de risque sanitaire.
 
<span style="color:#ffff00">**Moyen**</span> : l’IQA est acceptable. Toutefois, pour certains polluants, il peut y avoir de légers risques sanitaires pour un nombre limité de personnes. Par exemple, les personnes qui ne sont pas d’habitude sensibles à l’ozone pourraient manifester quelques symptômes.
 
<span style="color:#ff9900">**Mauvais**</span> : Certains groupes de personnes sont particulièrement sensibles aux effets nocifs de certains polluants. Ceci signifie qu'ils sont susceptibles d'être affectés pour les plus basses valeurs que le grand public. C'est le cas pour les enfants et les adultes en activité à l’extérieur. Les personnes atteintes de maladies respiratoires sont soumises à un risque élevé en cas d’exposition à l’ozone, alors que les gens atteints de maladies cardiaques le sont en cas d’exposition au monoxyde de carbone. Avec des valeurs d'IQA entre 150 et 200, tout le monde peut commencer à sentir des effets sanitaires qui sont plus sérieux chez les gens des groupes sensibles.
 
<span style="color:#ff0000">**Très Mauvais**</span> : Des valeurs d’IQA supérieures à 200 déclenchent une alerte sanitaire, car chacun peut ressentir de sérieux effets sur la santé. Avec des valeurs d'IQA supérieures à 300, toute la population est affectée. L’alerte générale doit être déclenchée et des mesures d’urgence doivent être prises.

### Fichier CSV

| date | iqa | Bel Air | Cathédrale | HLM | Guédiawaye | Médina | Yoff |
| --------- |:-----:|:-----:|:-----:|:-----:|:-----:|:-----:|:-----:|
|   xxxxx   | xxxxx | xxxxx | xxxxx | xxxxx | xxxxx | xxxxx | xxxxx |
|   xxxxx   | xxxxx | xxxxx | xxxxx | xxxxx | xxxxx | xxxxx | xxxxx |

## Métadonnée
```
* date
* iqa - iqa région de Dakar
* Bel Air - iqa zone Bel Air
* Cathédrale - iqa zone Cathédrale 
* HLM - iqa zone HLM
* Guédiawaye - iqa zone Guédiawaye
* Médina - iqa zone Médina
* Yoff - iqa zone Yoff
```

## Télécharger

Cliquez [**ici**](https://github.com/senegalouvert/AIR-Dakar/archive/master.zip) pour télécharger ou sur **clone or download**

## Contribuer

Lisez s'il vous plait [CONTRIBUTING.md](CONTRIBUTING.md) pour plus de détails sur notre code de conduite et le processus de soumission des demandes de contribution.

## Auteurs

* **Mamadou Diagne**

## Licence

Ce projet est sous licence MIT - voir le fichier [LICENSE](LICENSE) pour plus de détails.

## Source

* **CGQA** - *[Centre de Gestion de la Qualité de l'Air](http://air-dakar.org/)*