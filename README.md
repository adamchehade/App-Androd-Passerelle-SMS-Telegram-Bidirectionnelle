# App-Androd-Passerelle-SMS-Telegram-Bidirectionnelle
# 📱 Passerelle SMS ↔ Telegram Bidirectionnelle

**Solution de continuité pour l'expatriation.** Ne manquez plus jamais un OTP ou un message important lorsque votre carte SIM reste au pays. Cette application Android transforme votre smartphone secondaire en une passerelle intelligente qui redirige vos SMS vers Telegram et vous permet d'y répondre à distance.

---

## 🌟 Le Concept

Lorsque vous vivez à l'étranger, garder une carte SIM active dans votre pays d'origine est souvent nécessaire pour les banques (OTP), les administrations ou les services double authentification. 

**Le problème :** Le roaming coûte cher ou le signal est inexistant.
**La solution :** 1. Laissez votre téléphone secondaire (SIM locale) branché chez un proche ou au bureau.
2. Installez cette application.
3. Recevez tous vos SMS instantanément sur votre compte Telegram principal.
4. Répondez aux SMS directement depuis Telegram : le bot transmettra votre texte via la carte SIM du téléphone.

---

## 📸 Aperçu de l'Interface

| Écran Principal | Configuration Bot | Historique |
| :---: | :---: | :---: |
| ![dashboard-sms](https://github.com/user-attachments/assets/88332b67-1100-4128-9e55-09b17622f820)
) | ![Config](![tutor-sms](https://github.com/user-attachments/assets/b2a2ab84-6d0b-458f-bb65-1d56770e2c38)
| *Statut de la connexion* | *Paramètres Telegram* | *Flux des messages* |

---

## ✨ Fonctionnalités

* **Redirection Instantanée** : Les SMS reçus sont envoyés vers votre chat Telegram en temps réel.
* **Réponse Bidirectionnelle** : Répondez au message sur Telegram, le téléphone envoie le SMS au destinataire d'origine.
* **Sécurité renforcée** : Seul votre compte Telegram autorisé peut interagir avec le bot.
* **Gestion OTP** : Optimisé pour la réception de codes de vérification bancaires.
* **Auto-Start** : L'application se relance automatiquement au démarrage du téléphone.

---

## 🛠️ Configuration Rapide

1.  **Créer un Bot Telegram** :
    * Contactez [@BotFather](https://t.me/botfather) sur Telegram.
    * Créez un nouveau bot et récupérez le **Token API**.
2.  **Récupérer votre Chat ID** :
    * Utilisez un bot comme [@userinfobot](https://t.me/userinfobot) pour obtenir votre ID numérique unique.
3.  **Configurer l'App Android** :
    * Entrez le Token et votre Chat ID dans les réglages de l'application.
    * Accordez les permissions nécessaires (**SMS** et **Internet**).
4.  **Tester** :
    * Envoyez un message test pour vérifier la liaison.

---

## 📥 Installation

1.  Téléchargez le dernier fichier APK dans la section [Releases](https://github.com/votre-compte/votre-repo/releases).
2.  Autorisez l'installation de sources inconnues sur votre appareil Android.
3.  Lancez l'application et suivez l'assistant de configuration.

---

## 🔒 Confidentialité & Sécurité

* **Données locales** : Aucune donnée n'est stockée sur un serveur tiers. La communication se fait directement entre l'API Telegram et votre téléphone.
* **Chiffrement** : Les échanges bénéficient du protocole sécurisé HTTPS de Telegram.

---

## 🤝 Contribution

Les contributions sont les bienvenues ! Si vous souhaitez améliorer l'interface ou ajouter des fonctionnalités (comme le support Multi-SIM), n'hésitez pas à ouvrir une *Issue* ou une *Pull Request*.

---

### 👨‍💻 Développeur
* **Adam Chehade** - [GitHub](https://github.com/adamchehade)
