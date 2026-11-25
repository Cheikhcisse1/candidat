# Proposition AXEM IA × Bellanger Construction

Proposition commerciale réalisée dans le cadre de l'épreuve pratique de l'alternance **Chef de projet IA** chez AXEM IA.

**Code candidat : AXM-20261125-16F7**

> Le client, Bellanger Construction, est fictif. Il est construit à partir d'un vrai appel, rendu méconnaissable.

---

## L'idée en une phrase

**L'IA n'est pas une fusée, c'est un outil de plus dans la caisse.** La proposition rassure une direction méfiante et attentive à ses frais généraux. Elle commence petit, prouve les gains par la mesure, et laisse décider sur des chiffres.

## Ce que contient la page

| Section | Contenu |
|---|---|
| **L'essentiel** | Cinq points à lire en une minute pour le comité de direction |
| **La caisse à outils** | Un outil réel pour chacun des 8 besoins, avec son coût et son calendrier |
| **Démonstration** | Deux exemples cliquables : un compte rendu de chantier dicté et l'imputation d'une facture |
| **Essayez-le dès demain** | Une consigne prête à copier dans Copilot Chat, pour tester gratuitement avant de signer |
| **Sécurité** | Copilot Chat inclus dans Microsoft 365, et une charte en trois couleurs |
| **Le plan** | Chantier zéro, preuve, décision : trois étapes, avec un arrêt possible après chacune |
| **Rentabilité** | Un simulateur où le client règle ses propres chiffres |
| **Budget** | 9 500 € HT payables par étape, avec un financement possible par Constructys |
| **Les questions du comité** | Six réponses aux objections attendues |

## Structure du dépôt

```
.
├── index.html   # La proposition : une seule page autonome (HTML, CSS et JavaScript)
└── README.md    # Ce fichier
```

La page ne dépend d'aucun outil de build : il n'y a rien à installer ni à compiler. Les polices viennent de Google Fonts.

## Héberger la page

> ⚠️ **Anonymat.** L'épreuve interdit le nom du candidat dans la proposition. Si le nom d'utilisateur GitHub contient un nom, **ne pas utiliser GitHub Pages** : l'adresse `pseudo.github.io` le révélerait. Garder ce dépôt **privé** et publier la page avec Netlify.

### Option recommandée : Netlify relié à ce dépôt

1. Créer ce dépôt en **privé** et y déposer `index.html` et `README.md`.
2. Sur [app.netlify.com](https://app.netlify.com), cliquer sur **Add new project → Import an existing project → GitHub**, puis choisir ce dépôt.
3. Réglages de build :
   - **Build command** : laisser vide
   - **Publish directory** : `.` (la racine)
4. Cliquer sur **Deploy**.
5. Renommer le projet **`axm-20261125-16f7`** (*Project configuration → General → Change project name*).
6. Si un login est demandé à l'ouverture du site, aller dans *Project configuration → Access & security → Visitor access* et désactiver la protection pour la production.

Adresse finale : **`https://axm-20261125-16f7.netlify.app`**

Chaque modification poussée sur la branche `main` met le site à jour automatiquement.

### Autre option : Netlify Drop, sans GitHub

Glisser un dossier contenant uniquement `index.html` sur [app.netlify.com/drop](https://app.netlify.com/drop), **en étant connecté** (sans compte, le site est supprimé au bout d'une heure).

## Vérifications avant l'envoi

- [ ] Le lien s'ouvre en **navigation privée**, sans créer de compte.
- [ ] Aucun nom ni aucun visage dans la page ni dans l'adresse : seulement le code candidat.
- [ ] Les deux démonstrations, le bouton « Copier » et le simulateur fonctionnent.
- [ ] La page s'affiche correctement sur téléphone.
- [ ] Le mail de réponse garde **l'objet d'origine**, contient le lien et cinq lignes au plus sur la méthode.

## Sources des chiffres

Prix publics consultés en novembre 2026, susceptibles d'évoluer :
- Microsoft 365 Copilot Chat (inclus) et Copilot Business : [microsoft.com](https://www.microsoft.com/fr-fr/microsoft-365/business/copilot-for-microsoft-365)
- Facturation électronique, réception obligatoire depuis le 1er septembre 2026 : [economie.gouv.fr](https://www.economie.gouv.fr/node/3241932)
- Règlement européen sur l'IA, article 4 : [ai-act-service-desk.ec.europa.eu](https://ai-act-service-desk.ec.europa.eu/fr/ai-act/article-4)
- Financements Constructys : [constructys.fr](https://constructys.fr)
- Mistral AI, offre Team : [mistral.ai/pricing](https://mistral.ai/fr/pricing/)

Les gains affichés dans le simulateur sont des hypothèses, que le pilote doit vérifier.
