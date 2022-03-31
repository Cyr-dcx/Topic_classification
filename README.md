# Topic_classification
Technical assessment

Problématique : pouvoir dire si un tweet parle effectivement d'une catastrophe naturelle ou non.  
Par exemple, les tweets suivants ne parlent pas de catastrophe naturelle :   
'By accident' they knew what was gon happen https://t.co/Ysxun5vCeh.  
Statistically I'm at more of risk of getting killed by a cop than I am of dying in an airplane accident.

Alors que les tweets suivants traitent effectivement du sujet :  
BigRigRadio Live Accident Awareness
Reported motor vehicle accident in Curry on Herman Rd near Stephenson involving an overturned vehicle. http://t.co/YbJezKuRW1. 

Le but du test est de construire un modèle de machine learning qui va prédire si un tweet parle effectivement d'une catastrophe naturelle ou non.
Voici les datas fournies :  
train.csv contient "keyword,location,text,target" => le keyword éventuel qui a permis de trouver le tweet, la location éventuelle, le texte, et s'il traite ou non d'une catastrophe naturelle.   
test.csv contient "keyword,location,text" => l'idée est d'ajouter une colonne "pred" avec les prédictions. 


L'important est d'expliquer comment le candidat procède et avec quelle démarche (quelles métriques ? quel preprocessing ?, quelles features ?, avec ou sans transfert learning ?
