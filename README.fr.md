# Brief d’images vendeur Free

[简体中文](README.zh-CN.md) | [English](README.en.md) | [日本語](README.ja.md) | [한국어](README.ko.md) | [Deutsch](README.de.md) | [Français](README.fr.md) | [Español](README.es.md) | [Português](README.pt.md)

Utiliser la langue explicitement demandée, sinon celle de la demande. Conserver les commandes, identifiants de Skill, clés JSON, valeurs d’énumération, unités et citations originales. Distinguer traduction et original. Ne déduire ni pays, ni devise, ni juridiction de la langue. Lire les références détaillées utiles et maintenir tous les contrôles et autorisations existants.

## Installation et utilisation

Télécharger ou cloner le dépôt, puis copier le répertoire du Skill indiqué, avec ses references, scripts, assets et autres dépendances existantes, dans le répertoire de Skills de l’hôte. Conserver son nom et SKILL.md. Changer la langue de documentation ne demande pas de nouvelle installation. Les commandes proposées ne prouvent ni installation ni activation.

```sh
git clone https://github.com/PDBen-Auto/seller-image-brief-free.git
```

## Brief d’images vendeur Free

`seller-image-brief-free`

Préparer au plus trois images e-commerce distinctes selon FABE à partir des faits et avis fournis ; livrer un brief exécutable, pas des images générées.

Répertoire du Skill: `skills/seller-image-brief-free`

**Fondements et dépendances**

Agent/modèle lisant texte/CSV/tableaux et faits produit. Aucun compte/API/réseau externe pour le cœur ; coûts du modèle selon l’environnement. Allégations publiques : preuves et règles actuelles.

**Entrées**

Produit/catégorie/version/marché obligatoires. Avis autorisés, photos/mesures/tests, langue/format facultatifs ; maximum trois images. Avis d’offre désactivable par l’utilisateur ou SELLER_IMAGE_NO_UPSELL=1 si disponible.

**Sorties**

Conversation/Markdown : portée des preuves, questions acheteurs, trois fiches maximum avec F/A/B/E, composition, angle, texte court, statut, critères et inconnues.

[Déroulement · Limites et conditions d’arrêt · Exemple de demande](skills/seller-image-brief-free/references/i18n/fr.md)

> Utilise `$seller-image-brief-free` — Montrer l’usage des cloisons d’un rangement d’après les faits ; sans essai, ne pas affirmer l’étanchéité ; réponds en français en conservant les preuves, les inconnues et les limites d’autorisation.

## Couverture linguistique et validation

Ce guide localisé couvre objectif, prérequis, entrées, sorties, étapes, exemples et limites. Il ne traduit pas chaque référence ligne par ligne. Les références techniques détaillées, cas historiques, erreurs de scripts, interfaces d’exemple et images restent dans leur langue originale et peuvent être expliqués à la demande. Structure, liens et contraintes essentielles sont vérifiés ; aucune relecture par un locuteur natif de chaque langue n’est revendiquée.

Avant livraison, rapprocher entrées, preuves, valeurs manquantes, fichiers et critères d’achèvement d’origine. Marquer les étapes non exécutées comme non vérifiées ; la réussite d’un script ne valide pas une conclusion métier.
