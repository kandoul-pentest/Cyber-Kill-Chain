# Cyber-Kill-Chain soc level 1 
The Cyber Kill Chain framework is designed for identification and prevention of the network intrusions. You will learn what the adversaries need to do in order to achieve their goals.
<!-- SCREENSHOT 1 - HEADER -->
![Schéma de la Cyber Kill Chain](images/cyberkillchain.png)  
*Fig.1 - Les 7 étapes de la Cyber Kill Chain (Lockheed Martin)*

## 📌 Introduction
La **Cyber Kill Chain** est un modèle de sécurité qui décrit les étapes d'une cyberattaque. Voici sa décomposition complète :

## 🔍 Les 7 Étapes Clés

### 1. Reconnaissance (Espionnage)
- **Objectif** : Collecter des informations sur la cible
- **Outils** : 
  ```bash
  theHarvester -d entreprise.com -b google # 🔗 Cyber Kill Chain - SOC Level 1 Path

## 2. Weaponization (Armement)
**Définition** :  
Création de l'arme numérique combinant malware et exploit.

**Méthodes** :
- 💾 Documents avec macros malveillantes
- 📦 Exploits zero-day
- 🧩 Kits d'exploitation (Metasploit)

## 3. Delivery (Livraison)
**Définition** :  
Transmission du payload malveillant à la cible.

**Méthodes courantes** :
```mermaid
pie title Méthodes de Livraison (2023)
    "Phishing" : 65
    "Sites compromis" : 20
    "USB malveillants" : 10
    "Autres" : 5
## 💥 Exploitation

### 🎯 Définition
Phase où l'attaquant active son code malveillant après avoir infiltré le système.

### 🔧 Techniques courantes
1. **Exploitation de vulnérabilités logicielles**  
   Exemple : `CVE-2023-1234` (dépassement de tampon)

2. **Documents malveillants**  
   ```python
   # Macro Word malveillante simplifiée
   Sub AutoOpen()
       Shell("cmd /c powershell -nop -w hidden -e JABzAD0A...")
   End Sub
