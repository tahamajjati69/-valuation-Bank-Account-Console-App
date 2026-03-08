# Kotlin – Évaluation

## 📖 Description
Cet exercice Kotlin illustre :
- La simulation d’un **système bancaire** avec différents types de comptes.
- L’utilisation de **fonctions imbriquées** pour gérer les opérations bancaires.
- La gestion des **balances positives et négatives** selon le type de compte.
- L’interaction avec l’utilisateur via un menu simulé.

---

## ⚙️ Fonctionnalités
- **Types de comptes disponibles** :
  - Compte **débit**.
  - Compte **crédit** (balance négative).
  - Compte **checking**.

- **Opérations bancaires** :
  - `withdraw(amount)` : retrait générique.
  - `debitWithdraw(amount)` : retrait spécifique pour compte débit.
  - `deposit(amount)` : dépôt générique.
  - `creditDeposit(amount)` : dépôt spécifique pour compte crédit.

- **Menu interactif** :
  - Vérifier le solde.
  - Retirer de l’argent.
  - Déposer de l’argent.
  - Fermer l’application.

- **Gestion des erreurs** :
  - Empêche les retraits si le solde est insuffisant.
  - Empêche les dépôts invalides sur un compte crédit déjà soldé.

---

## 🖥️ Exemple d’exécution

https://github.com/user-attachments/assets/5032489f-633b-4c7d-8ee7-963c45aa832f




## 💡 Concepts pratiqués
- Utilisation de **boucles `while`** pour maintenir un système actif.
- Gestion des **conditions** avec `if` et `when`.
- Définition de **fonctions imbriquées** pour modulariser les opérations.
- Simulation d’un menu interactif avec choix aléatoires.
- Gestion des comptes bancaires avec règles spécifiques.

---

## 🧑‍💻 Auteur
👤 **Majjati Mohamed Taha**  
📱 Développement Kotlin  
🎓 Instructor : **Mr. LACHGAR**  
📅 9 Mars 2026
