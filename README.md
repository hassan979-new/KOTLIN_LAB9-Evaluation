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
Sortie console : 
- <img width="960" height="1008" alt="image" src="https://github.com/user-attachments/assets/514827a6-ca68-44d5-866c-2666412f059e" />
```
Welcome to your banking system.
What type of account would you like to create?
1. Debit account
2. Credit account
3. Checking account
Choose an option (1, 2 or 3)
You selected : 2
You have created a credit account.
Credit account detected: balance is a debt => -962 Dirhams.
The amount you transferred is 623 Dirhams.
You successfully withdrew 623 Dirhams. The current balance is -1585 Dirhams.
The amount you withdrew is 623 Dirhams.

Not enough money on this account! The current balance is -1585 Dirhams.
The amount you withdrew is 0 Dirhams.

You successfully deposited 623 Dirhams. The current balance is -962 Dirhams.
The amount you deposited is 623 Dirhams.

You successfully deposited 623 Dirhams. The current balance is -339 Dirhams.
The amount you deposited is 623 Dirhams.

What would you like to do?
1. Check bank account balance
2. Withdraw money
3. Deposit money
4. Close the app
Which option do you choose? (1, 2, 3 or 4)
The selected option is 10.
What would you like to do?
1. Check bank account balance
2. Withdraw money
3. Deposit money
4. Close the app
Which option do you choose? (1, 2, 3 or 4)
The selected option is 1.
The current balance is -339 Dirhams.
What would you like to do?
1. Check bank account balance
2. Withdraw money
3. Deposit money
4. Close the app
Which option do you choose? (1, 2, 3 or 4)
The selected option is 4.
The system is closed
```

---

## 💡 Concepts pratiqués
- Utilisation de **boucles `while`** pour maintenir un système actif.
- Gestion des **conditions** avec `if` et `when`.
- Définition de **fonctions imbriquées** pour modulariser les opérations.
- Simulation d’un menu interactif avec choix aléatoires.
- Gestion des comptes bancaires avec règles spécifiques.

---

## 🧑‍💻 Auteur
👤 **Agouram Hassan**  
📱 Développement Kotlin  
🎓 Instructor : **Mr. LACHGAR**  
📅 8 Mars 2026

