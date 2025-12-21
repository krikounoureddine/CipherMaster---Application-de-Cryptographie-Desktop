# 🔐 CipherMaster — Application de Cryptographie Desktop

> **CipherMaster** est une application desktop professionnelle de cryptographie développée en **Java (Swing)**.  
Elle regroupe des algorithmes de chiffrement classiques, modernes et asymétriques au sein d’une interface graphique intuitive, pensée pour l’apprentissage, la démonstration et la sécurité de l’information.

[![GitHub stars](https://img.shields.io/github/stars/krikounoureddine/CipherMaster?style=flat-square)](https://github.com/krikounoureddine/CipherMaster---Application-de-Cryptographie-Desktop)
[![Java Version](https://img.shields.io/badge/Java-8%2B-orange?style=flat-square)](https://www.java.com)
[![License: MIT](https://img.shields.io/badge/License-MIT-blue.svg?style=flat-square)](LICENSE)
[![GitHub issues](https://img.shields.io/github/issues/krikounoureddine/CipherMaster?style=flat-square)](https://docs.github.com/fr/issues/tracking-your-work-with-issues/learning-about-issues/about-issues)

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

## 🛠️ Technologies & outils

- **Java SE**
- **Java Swing (GUI Desktop)**
- **JCA / JCE (Java Cryptography Architecture / Extension)**
- **Bouncy Castle** (provider cryptographique)
- **Apache Commons Codec** (Base64)
- **Eclipse IDE**

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

## ▶️ Utilisation

1. Lancer l’application  
2. Choisir l’algorithme de chiffrement  
3. Sélectionner le mode opératoire (si applicable)  
4. Générer ou importer une clé  
5. Chiffrer / Déchiffrer le message  

> L’interface par onglets permet une navigation fluide entre les différents algorithmes.

---

## 🧩 Architecture du projet

- `ui/` : interfaces graphiques Swing  
- `crypto/` : implémentation des algorithmes  
- `utils/` : encodage et gestion des clés  
- `security/` : configuration JCA / providers  

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
