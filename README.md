<!-- README.md - CipherMaster -->

<body style="background: linear-gradient(135deg, #f5f7fa 0%, #c3cfe2 100%); margin: 0; padding: 20px;">

<div style="
    background-color: #0f172a;
    border-left: 4px solid #00d4aa;
    padding: 1.5rem;
    margin: 2rem 0;
    border-radius: 0 8px 8px 0;
    color: #f8fafc;
">

<p style="font-size: 1.2rem; opacity: 0.9;">Application Desktop Professionnelle de Cryptographie — Algorithmes Classiques, Symétriques et Asymétriques</p>

</div>

<br>

<div align="center" style="
    background: linear-gradient(90deg, #0a192f 0%, #00d4aa 100%);
    color: white;
    padding: 2rem;
    border-radius: 10px;
    position: relative;
    overflow: hidden;
">
    
<br>

<div style="position: absolute; top: 0; right: 0; padding: 1rem;">
    <img alt="Java" src="https://img.shields.io/badge/Java-ED8B00?style=for-the-badge&logo=java&logoColor=white">
    <img alt="Swing" src="https://img.shields.io/badge/Java_Swing-007396?style=for-the-badge&logo=java&logoColor=white">
    <img alt="MIT License" src="https://img.shields.io/badge/License-MIT-blue?style=for-the-badge">
    <img alt="Status" src="https://img.shields.io/badge/Status-Production%20Ready-brightgreen?style=for-the-badge" />
    <img alt="Cryptography" src="https://img.shields.io/badge/Cryptography-Expert-important?style=for-the-badge" />
</div>

<br>

<h1 style="margin-top: 2rem;">🔐 CipherMaster</h1>
<p style="font-size: 1.2rem; opacity: 0.9;"> CipherMaster est une application desktop Java (Swing) professionnelle regroupant des algorithmes de chiffrement classiques, symétriques et asymétriques au sein d'une interface graphique intuitive, pensée pour l'apprentissage, la démonstration et la sécurité de l'information.
</p>

</div>

</body>

---


# 🔐 CipherMaster — Application de Cryptographie Desktop

> **CipherMaster** est une application desktop professionnelle de cryptographie développée en **Java (Swing)**.  
Elle regroupe des algorithmes de chiffrement classiques, modernes et asymétriques au sein d’une interface graphique intuitive, pensée pour l’apprentissage, la démonstration et la sécurité de l’information.

[![GitHub stars](https://img.shields.io/github/stars/krikounoureddine/CipherMaster?style=flat-square)](https://github.com/krikounoureddine/CipherMaster---Application-de-Cryptographie-Desktop)
[![Java Version](https://img.shields.io/badge/Java-8%2B-orange?style=flat-square)](https://www.java.com)
[![License: MIT](https://img.shields.io/badge/License-MIT-blue.svg?style=flat-square)](LICENSE)
[![GitHub issues](https://img.shields.io/github/issues/krikounoureddine/CipherMaster?style=flat-square)](https://docs.github.com/fr/issues/tracking-your-work-with-issues/learning-about-issues/about-issues)

---

## 📖 Table des Matières

### 🔍 **Découverte & Démonstration**
- [🎯 Présentation du Projet](#-présentation-du-projet)
- [🎨 Démonstration Interactive](#-démonstration-interactive)
- [✨ Fonctionnalités Clés](#-fonctionnalités-clés)

### ⚙️ **Développement & Architecture**
- [🏗️ Architecture du projet](#architecture-du-projet)
- [🛠️ Technologies & Outils](#-technologies--outils)
- [📦 Installation](#-installation)
- [▶️ Utilisation](#-utilisation)

### 🤝 **Communauté & Contribution**
- [💡 Contribution](#-contribution)
- [📜 Licence](#-licence)
- [📞 Contact](#-contact)

---

## 🚀 Présentation du projet

CipherMaster a pour objectif de fournir une **boîte à outils cryptographique complète** permettant de :

- Comprendre les mécanismes fondamentaux du chiffrement  
- Manipuler des algorithmes reconnus dans l’industrie  
- Gérer des clés cryptographiques de manière sécurisée  
- Chiffrer et déchiffrer des données via une interface graphique moderne  

L’application repose sur les standards **JCA / JCE** et s’appuie sur des bibliothèques reconnues telles que **Bouncy Castle** et **Apache Commons Codec**.

---

## 🚀 **Démonstration Interactive**

<div align="center">
  <table>
    <tr>
      <td align="center"><strong>Interface Moderne</strong></td>
      <td align="center"><strong>Gestion des Clés</strong></td>
    </tr>
    <tr>
      <td><img src="https://raw.githubusercontent.com/krikounoureddine/CipherMaster---Application-de-Cryptographie-Desktop/main/screenshots/ui-main.png" width="400" alt="Interface principale CipherMaster"></td>
      <td><img src="https://raw.githubusercontent.com/krikounoureddine/CipherMaster---Application-de-Cryptographie-Desktop/main/screenshots/rsa-keygen.png" width="400" alt="Génération de clés RSA"></td>
    </tr>
    <tr>
      <td align="center"><strong>Navigation Intelligente</strong></td>
      <td align="center"><strong>Chiffrement en Temps Réel</strong></td>
    </tr>
    <tr>
      <td><img src="https://raw.githubusercontent.com/krikounoureddine/CipherMaster---Application-de-Cryptographie-Desktop/main/screenshots/ui-tabs.png" width="400" alt="Navigation par onglets"></td>
      <td><img src="https://raw.githubusercontent.com/krikounoureddine/CipherMaster---Application-de-Cryptographie-Desktop/main/screenshots/encrypt.png" width="400" alt="Processus de chiffrement"></td>
    </tr>
  </table>
</div>

---

## ✨ Fonctionnalités clés

### 🔑 Algorithmes classiques
- Chiffrement **César**
- Chiffrement **Affine**
- Chiffrement **Vigenère**

### 🔒 Cryptographie symétrique
- **AES** (Advanced Encryption Standard)
- **DES** (Data Encryption Standard)
- Modes opératoires :
  - ECB
  - CBC
- Padding : **PKCS7**

### 🔐 Cryptographie asymétrique
- **RSA – 2048 bits**
- **ElGamal**

### 🧠 Sécurité & gestion des clés
- Génération sécurisée de clés
- Encodage **Base64**
- Stockage et manipulation sécurisée
- Respect des bonnes pratiques cryptographiques

### 🖥️ Interface graphique (GUI)
- Application desktop **Java Swing**
- Navigation par onglets
- Interface intuitive et interactive
- Architecture modulaire et maintenable

---

## Architecture du projet

- `ui/` : interfaces graphiques Swing  
- `crypto/` : implémentation des algorithmes  
- `utils/` : encodage et gestion des clés  
- `security/` : configuration JCA / providers

---

## Technologies & outils

### **Stack Technologique Principale**

| Catégorie | Technologies | Description |
|-----------|--------------|-------------|
| **Langage** | Java SE 8+ | Langage de programmation principal |
| **Interface** | Java Swing | Interface graphique desktop |
| **Cryptographie** | JCA / JCE | Architecture cryptographique Java |
| **Bibliothèques** | Bouncy Castle, Apache Commons Codec | Providers cryptographiques et utilitaires |
| **Développement** | Eclipse IDE | Environnement de développement intégré |
| **Gestion** | Git, GitHub | Versionnement et hébergement |

### **Détails techniques :**
- **JCA (Java Cryptography Architecture)** : Framework pour les opérations cryptographiques
- **JCE (Java Cryptography Extension)** : Implémentation des algorithmes cryptographiques
- **Bouncy Castle** : Provider cryptographique pour algorithmes additionnels
- **Apache Commons Codec** : Utilitaire pour l'encodage Base64

---

## 📦 Installation

### Prérequis
- Java JDK **8 ou supérieur**
- IDE Java (**Eclipse recommandé**)

### Étapes
```bash
# Cloner le dépôt
git clone https://github.com/krikounoureddine/CipherMaster---Application-de-Cryptographie-Desktop.git

# Ouvrir le projet dans Eclipse
# Vérifier les dépendances
# Lancer la classe principale

```

## Utilisation

1. Lancer l’application  
2. Choisir l’algorithme de chiffrement  
3. Sélectionner le mode opératoire (si applicable)  
4. Générer ou importer une clé  
5. Chiffrer / Déchiffrer le message  

> L’interface par onglets permet une navigation fluide entre les différents algorithmes.

---

## 🤝 Contribution

Les contributions sont les bienvenues :

1. Forker le projet  
2. Créer une branche (`feature/amelioration`)  
3. Committer les changements  
4. Ouvrir une Pull Request  

---

## 📜 Licence

Ce projet est sous licence **MIT**.  
Vous êtes libre de l’utiliser, le modifier et le distribuer.

---

## 📫 Contact

👤 **Noureddine Krikou**  
💼 Développeur Java / Full Stack  
🌐 GitHub : https://github.com/krikounoureddine  

---

## ⭐ Pourquoi CipherMaster ?

✔ Démonstration d’une **maîtrise avancée de Java**  
✔ Mise en pratique concrète de la **cryptographie moderne**  
✔ Code structuré, lisible et évolutif  
✔ Projet pertinent pour les recruteurs en **sécurité de l’information**

> ⭐ *N’hésitez pas à laisser une étoile si le projet vous plaît !*


