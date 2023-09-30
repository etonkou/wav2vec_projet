## **README Devoir Wav2Vec** :

***Devoir_Deepl2_wav2vec.ipynb*** :
c'est notre notebook qui charge notre ASR et fait l'entrainement du modele wav2vec et push le modele sur huggingface

***le lien huggingface de notre modele wav2vec est :***
[https://huggingface.co/etonkou/swahili](https://huggingface.co/etonkou/swahili)

***main.py*** :
Ce fichier contient le code permet de deployer notre modele sur fastapi
il contient la fonction qui appele le FastAPI et la fonction d'inference qui se trouve dans utils.py

***Dockerfile*** :
Dockerfile contient les commandes pour construire l'image et de deployer notre modele accessible via fastapi sur Docker

*** /screenshots*** :
le dossier screenshots contient quelques captures d'ecrans relatifs a ce projet 