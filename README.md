# CV Generator with RAG and LLM (Cohere)

## Description

Ce projet utilise une approche RAG (Retrieval-Augmented Generation) combinée à un Large Language Model (LLM) de Cohere pour générer automatiquement un CV personnalisé à partir de vos anciens documents personnels (anciens CV, lettres de motivation, certificats, etc.).

Grâce à LangChain et à un moteur de recherche intelligent, les documents sont récupérés, analysés, et utilisés pour construire un nouveau CV adapté à vos besoins actuels.

## Technologies utilisées

Python 3.10+ \
LangChain \
Cohere API \
FAISS (ou autre outil de vectorisation pour retrieval) \
Streamlit (optionnel pour une interface simple) 

## Objectifs du projet

Utiliser RAG pour enrichir un modèle de langage Cohere avec vos données personnelles. \
Automatiser la création d'un CV intelligent et structuré. \
Tester différentes options : \
Température du modèle (plus ou moins créatif). \
Différents prompts pour varier le style et la précision du CV. 

## Fonctionnement

Indexation des anciens documents sous forme vectorisée. \
Recherche intelligente de contenus pertinents. \
Génération d'un nouveau CV à partir des données récupérées grâce à Cohere. \
Optimisation des résultats en ajustant les paramètres (temperature, prompts). 
