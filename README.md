# 📩 Google Form to Discord partage par Spirit RP
Un serveur FiveM GTA5 Roleplay

Recevez les réponses de vos **formulaires Google** directement en **embed** sur un salon **Discord** grâce à un **webhook**. 🔗

---

## 🚀 Fonctionnalités
✅ **Récupération automatique** des réponses d'un **Google Form**  
✅ **Affichage propre en embed** sur Discord (titre, description, couleurs, avatar, footer)  
✅ **Personnalisation** du message, avec mentions et emojis  
✅ **Facile à configurer** et à utiliser avec un simple webhook  
✅ **Images acceptées** PNG, JPG, JPEG, GIF, et WEBP  

---

## 🎯 Prérequis
Avant de commencer, assurez-vous d’avoir :
- Un **formulaire Google** avec des questions-réponses.
- Un **webhook Discord** configuré sur votre serveur.

---

## ⚙️ Installation et Configuration

### 1️⃣ **Créer un webhook Discord**
1. Allez dans **Paramètres du serveur** > **Intégrations** > **Webhooks**.
2. Cliquez sur **Créer un webhook** et copiez l'URL.

### 2️⃣ **Ajouter le script à Google Apps Script**
1. Ouvrez votre **Google Form**.
2. Cliquez sur **Extensions** > **Apps Script**.
3. Supprimez le code par défaut et collez le **code.js** contenu dans ce repo.
4. **Remplacez l’URL du webhook** par le vôtre.
5. Enregistrez et fermez l’éditeur.

### 3️⃣ **Autoriser le script**
1. Dans **Apps Script**, cliquez sur **Exécuter** (▶️).
2. Autorisez l’accès à votre compte Google.

---

## 🖥️ Exemple d'Embed Discord
Une fois configuré, voici un exemple de réponse envoyée sur Discord :

> **📌 PPA Résultat - Spirit RP**
>
> 📝 **Entretien Psychotechnique pour le PPA**
>
> 🔹 **Question 1** : Réponse 1  
> 🔹 **Question 2** : Réponse 2  
> 🔹 **Question 3** : Réponse 3  
>
> 🔗 [Spirit RP](https://spirit-rp.fr)  
> *🕒 Aujourd’hui à 06:25*

---

# 🛠️ Personnalisation
Vous pouvez personnaliser :
- **Le titre** : `const title = "PPA Résultat - Spirit RP";`
- **L’avatar** : `const avatarImage = "https://cdn.data-system.org/upload/k8pn1oi086j.webp";`
- **La couleur de l'embed** : `const colour = "#e99200";`
- **La mention d’une personne** : `const mention = "<@!437714005394587648>";`
- **Le texte du footer** : Ajouté en bas de l'embed.

---

## 🐛 Dépannage et FAQ

### ❓ **Pourquoi mon embed ne s'affiche pas ?**
- Vérifiez que votre **webhook Discord** est bien configuré.
- Assurez-vous que le **script Apps Script** a été autorisé.
- Discord limite les **messages à 2000 caractères** → réduisez les réponses.

### ❓ **Comment tester mon script avant de l’envoyer ?**
- Ajoutez un `Logger.log(payload);` pour voir les résultats dans **Apps Script**.

---

## 🔗 Ressources utiles
- 📜 **Documentation Discord Webhooks** : [Lien officiel](https://discord.com/developers/docs/resources/webhook)
- 🛠️ **Google Apps Script** : [Documentation Google](https://developers.google.com/apps-script)
- 🌐 **Site officiel** : [Spirit RP](https://spirit-rp.fr)

---

## 👨‍💻 Auteur
Repris de Its et amélioré par **[Spirit RP](https://github.com/Ton-Nom-Utilisateur)**.  
Si vous aimez ce projet, **⭐ Mettez une étoile !** 😊

📧 **Contact** : [Discord](https://discord.gg/spiritfa)

---
