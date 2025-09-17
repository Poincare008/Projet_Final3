


# Projet_Final3

### _Author_: Steve Calixte

## Overview
Konpayi finansye an bezwen otomatize pwosesis pre li yo sou baz enfomasyon li rekeyi nn men kliyan. Pou nou arive a objektif sa, nou gen a dispozisyon nou yon dataset ki gen 13 kolon ak 615 liy done pase sou de pre ke yo te arive akode. Pou nou arive otomatize pwosesis lan nou bral teste diferan model ML epi kenbe pou deplwaman model ki bay pi bon rezilta a.


## Business Problem
The company seeks to automate (in real time) the loan qualifying procedure based on information given by customers while filling out an online application form. It is expected that the development of ML models that can help the company predict loan approval in accelerating decision-making process for determining whether an applicant is eligible for a loan or not.





## The Data
This dataset profiles individuals who have received a loan and those who have not. It provides information across 13 columns and 615 rows on their education levels, genders, credit histories, and more. As part of this project, we will use this data to try to solve a classification problem.





## Modeling

### Preparasyon done
Avan nou rive nan faz modelizasyon, nou fe kek tretman nan done yo. Pou komanse nou tansfome varyab kategoryel yo an varyab bine gras ak "get_dummies".Apre nou itilize MinMaxscaler pou nou ramene a yon menm echel done nimerik yo. Epi pou fini nou separe done nou yo an done dantrenman epi done tes.

### Chwa epi konstriksyon model
Pou nou rive a chwa model optimal lan, nou itilize yon apwoch iteratif ki konsiste a chwazi plize algoritm epi evalye yo sou baz "Accuracy". Pou nou rive fe chwa meye paramet nan chak model, nou itilize Gridsearch.
Premye model nou fe apel se Lojistik Regresyon,apre antrenman model lan gen yon nivo 'accuracy' 82.29 %


Dezyem model nou itilize se Decision Tree, apre antrenman model lan gen yon nivo 'accuracy' 82.29 % tou.




Pou fini nou fe apel ak KNN, ki gen yon nivo 'accuracy' de 79%.



## Konparezon model yo

















## Konklizyon