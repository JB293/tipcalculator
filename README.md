# Tip Calculator

Une application Android moderne pour calculer les pourboires, développée avec **Jetpack Compose** et **Material Design 3**.

## ✨ Fonctionnalités
- Calcul dynamique du pourboire en temps réel.
- Entrée personnalisée du montant de la facture.
- Choix du pourcentage de pourboire.
- Option pour arrondir le montant final.
- Interface adaptative avec support du défilement.

## 🛠 Technologies utilisées
- **Kotlin** : Langage de programmation.
- **Jetpack Compose** : Framework UI déclaratif.
- **Material 3** : Design system d'Android.
- **State Management** : Utilisation de `mutableStateOf` et `remember`.

## 🚀 Installation
1. Clonez ce dépôt sur votre machine.
2. Ouvrez le projet dans **Android Studio**.
3. Cliquez sur **Run 'app'** pour l'installer sur votre émulateur ou appareil physique.

## 📖 Structure du projet
Le code principal se trouve dans `MainActivity.kt` et se compose de :
- `TipTimeLayout` : L'écran principal et sa logique.
- `EditNumberField` : Composant réutilisable pour la saisie.
- `calculateTip` : Fonction de calcul mathématique formatée.

---
*Projet réalisé pour apprendre les bases de la gestion d'état dans Android.*