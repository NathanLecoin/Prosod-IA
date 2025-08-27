
<a name="top"></a>
# 🏆 Prosod’IA – ESIEE Paris Innovation Award 2024  

<p align="center">
    <img src="./docs/logo.png" alt="ProsodIA Logo" width="500"/>
</p>


<p align="center">
    <img alt="Python" src="https://img.shields.io/badge/Python-3776AB?style=for-the-badge&logo=python&logoColor=white" />
    <img alt="Keras" src="https://img.shields.io/badge/Keras-FF0000?style=for-the-badge&logo=keras&logoColor=white" />
    <img alt="MATLAB" src="https://img.shields.io/badge/MATLAB-0076A8?style=for-the-badge&logo=mathworks&logoColor=white" />
</p>

<br>

<p align="center"><i>Projet académique de 3ᵉ année (Durée : 4 mois) – Lauréat du <b>Prix de l’Innovation 2024</b>, remis par Éric Larchevêque (Co-fondateur de Ledger).</i></p>

## 📑 Table des matières
- [Objectif](#-objectif)
- [Technologies utilisées](#-technologies-utilisées)
- [Méthodologie](#-méthodologie)
- [Résultats](#-résultats)
- [Aperçu de l’application](#-aperçu-de-lapplication)
- [Équipe](#-équipe)
- [Accès au code](#-accès-au-code)
- [Références](#-références)

## 🎯 Objectif  
Développer une application d’aide au **diagnostic précoce des Troubles du Spectre Autistique (TSA)**, basée sur l’analyse de la **prosodie** (caractéristiques vocales avant l’apparition du langage).  

➡️ Résultat principal : taux de fiabilité de **93%**.  
➡️ Nouvelle approche pour soutenir les professionnels de santé dans le dépistage des TSA, complémentaire aux méthodes actuelles.  


## 🔧 Technologies utilisées  
- **Traitement du signal** : Matlab, Python (Librosa, SciPy)  
- **IA & Deep Learning** : TensorFlow / Keras, Transfer Learning (VGG16, MobileNet, ResNet)  
- **Application** : Python (Tkinter) → exécutables Windows (.exe) et Mac (.app)  
- **Gestion de projet** : GitLab, Trello, diagrammes de Gantt  


## 🛠️ Méthodologie  
1. **Extraction des caractéristiques vocales** : MFCC, spectrogrammes, mel-spectrogrammes  
2. **Filtrage & prétraitement audio** : élimination des bruits parasites (Butterworth filter, segmentation)  
3. **Modélisation IA** : réseaux pré-entraînés et fine-tuning sur nos données  
4. **Développement logiciel** : application ergonomique pour médecins (diagnostic à partir d’un simple enregistrement)  


## 🚀 Résultats  
- Fiabilité : **93%** (contre ~86% sur travaux précédents à l’ESIEE)  
- Démonstration que des **marqueurs précoces** sont détectables dans la voix des enfants atteints de TSA  
- Déploiement sous forme d’application fonctionnelle (Windows et)  

## 📸 Aperçu de l’application

L’application **Prosod’IA** a été déployée en exécutables autonomes (.exe Windows, .app Mac) grâce à *py2app* et *auto-py-to-exe* (PyInstaller).  
➡️ Aucun besoin d’installation Python, une distribution simplifiée pour les médecins et chercheurs, et un code source protégé.  

L’interface se compose de trois écrans principaux :  
1. **Menu principal** – accueil clair et ergonomique  
2. **Import audio** – chargement d’un fichier .wav à analyser  
3. **Résultats** – affichage du spectrogramme et d’un pourcentage de suspicion de TSA  

<p align="center">
  <img src="./docs/app.png" alt="ProsodIA App Main" width="400"/>
</p>

<p align="center">
  <img src="./docs/app2.png" alt="ProsodIA Import Audio" width="350" style="margin: 10px;"/>
  <img src="./docs/app3.png" alt="ProsodIA Results" width="350" style="margin: 10px;"/>
</p>

## 👨‍💻 Équipe  

Anaelle Mariette, Louka Morandi, Livio Daninthe, Nathan Lecoin, Tom Lalieu, Lila Razani

**Encadrement** : *Nadia Madaoui* – Enseignante-chercheuse, ESIEE Paris  

## 📂 Accès au code  
👉 Le code source complet est disponible sur le **[GitLab de l’ESIEE Paris](https://git.esiee.fr/lalieut/prosod-ia)**.  
Ce repo GitHub sert de vitrine publique au projet.  

## 📜 Références  
- [Affiche de présentation (PDF)](./docs/Affiche.pdf) 
- [Vidéo de présentation (YouTube)](https://www.youtube.com/watch?v=wFQNDkl7yT4)

---

<p align="center">
👤 Auteur : <a href="https://www.linkedin.com/in/nathan-lecoin-855940231/" target="_blank">Nathan Lecoin</a>
</p>

<br>

<p align="center">
    <a href="#top">⬆️ Back to top</a>
</p>
