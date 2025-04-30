# AgentAi_n8n

# AgentAI - Assistant Devis WhatsApp

Automatisez la gestion de vos demandes de devis sur WhatsApp grâce à AgentAI, un agent intelligent basé sur n8n.
Inspiré du travail de [jimleuk](https://n8n.io/creators/jimleuk/), ce projet facilite la réception, le traitement et la génération de devis, le tout via WhatsApp.

---

## 📑 Sommaire

- [Fonctionnalités](#fonctionnalités)
- [Stack technique](#stack-technique)
- [Installation](#installation)
- [Exemple d’utilisation](#exemple-dutilisation)
- [Personnalisation](#personnalisation)
- [Crédits](#crédits)

---

## 🚀 Fonctionnalités

- **Réception de demandes de devis** via WhatsApp (texte, audio, photo)
- **Collecte automatique** des informations client (nom, besoin, budget, etc.)
- **Génération de devis** (PDF ou texte)
- **Envoi du devis** directement sur WhatsApp
- **Agent IA** pour la compréhension et l’automatisation des réponses
- **Escalade vers un humain** si besoin
- **Historique et suivi** des échanges

---

## 🛠️ Stack technique

| Composant                 | Rôle                                               |
|---------------------------|----------------------------------------------------|
| n8n                       | Orchestration des workflows                        |
| WhatsApp Business API     | Réception/envoi de messages                        |
| Agent IA (ex : OpenAI)    | Analyse et génération de contenu                   |
| Stockage (optionnel)      | Archivage des demandes (Google Sheets, BDD...)    |
| PDF Generator (optionnel) | Création automatique des devis au format PDF       |

---

## ⚙️ Installation

1.  **Import du workflow n8n :**
    -   Téléchargez le workflow JSON ou créez le vôtre.
    -   Dans n8n : *Workflows → Import from File*.
2.  **Configuration des identifiants :**
    -   Renseignez les clés API WhatsApp, OpenAI, etc.
    -   Sécurisez les variables sensibles.
3.  **Personnalisation des prompts IA :**
    -   Adaptez les instructions de l'agent IA à votre activité.
4.  **Activation et test :**
    -   Démarrez le workflow et testez le parcours utilisateur.

---

## 💬 Exemple d’utilisation

1.  Client envoie : "Bonjour, devis pour une salle de bain."
2.  L’Agent IA analyse et demande des détails (surface, budget...).
3.  Génération et envoi du devis (PDF ou texte).
4.  Escalade humaine si besoin.

---

## ✨ Personnalisation

-   Ajout d'autres canaux (Telegram, Email)
-   Intégration CRM
-   Génération de factures
-   Paiements en ligne

---

## 🙏 Crédits

Basé sur le travail de [jimleuk](https://n8n.io/creators/jimleuk/) et la communauté n8n.

---

**Tags :** WhatsApp, Devis, Automatisation, n8n, Agent IA, Workflow, Jimleuk
