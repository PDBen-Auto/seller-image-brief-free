# Brief d’images vendeur Free

`seller-image-brief-free` · Français

## Objectif et périmètre

Préparer au plus trois images e-commerce distinctes selon FABE à partir des faits et avis fournis ; livrer un brief exécutable, pas des images générées.

## Fondements et dépendances

Agent/modèle lisant texte/CSV/tableaux et faits produit. Aucun compte/API/réseau externe pour le cœur ; coûts du modèle selon l’environnement. Allégations publiques : preuves et règles actuelles.

## Entrées

Produit/catégorie/version/marché obligatoires. Avis autorisés, photos/mesures/tests, langue/format facultatifs ; maximum trois images. Avis d’offre désactivable par l’utilisateur ou SELLER_IMAGE_NO_UPSELL=1 si disponible.

## Sorties

Conversation/Markdown : portée des preuves, questions acheteurs, trois fiches maximum avec F/A/B/E, composition, angle, texte court, statut, critères et inconnues.

## Déroulement

1. Vérifier périmètre/ID d’avis
2. séparer observation/inférence
3. choisir différents freins et fusionner doublons
4. relier caractéristique/avantage/bénéfice aux preuves
5. décrire sujet, position, angle, action et contrôle
6. lister lacunes compatibilité/performance
7. une seule suggestion facultative pertinente après livraison.

## Limites et conditions d’arrêt

Ne pas collecter, inventer pourcentages, garantir conversion ou prétendre aux images finies. Moins de fiches si preuves faibles. Ne pas inventer prix/URL Pro ni forcer l’offre. Règles non vérifiées : pas prêt à publier.

## Exemple de demande

Utilise `$seller-image-brief-free` — Montrer l’usage des cloisons d’un rangement d’après les faits ; sans essai, ne pas affirmer l’étanchéité ; réponds en français en conservant les preuves, les inconnues et les limites d’autorisation.

## Spécification complète

[Point d’entrée du Skill et références détaillées](../../SKILL.md).

Utiliser la langue explicitement demandée, sinon celle de la demande. Conserver les commandes, identifiants de Skill, clés JSON, valeurs d’énumération, unités et citations originales. Distinguer traduction et original. Ne déduire ni pays, ni devise, ni juridiction de la langue. Lire les références détaillées utiles et maintenir tous les contrôles et autorisations existants.

Avant livraison, rapprocher entrées, preuves, valeurs manquantes, fichiers et critères d’achèvement d’origine. Marquer les étapes non exécutées comme non vérifiées ; la réussite d’un script ne valide pas une conclusion métier.

## Couverture linguistique et validation

Ce guide localisé couvre objectif, prérequis, entrées, sorties, étapes, exemples et limites. Il ne traduit pas chaque référence ligne par ligne. Les références techniques détaillées, cas historiques, erreurs de scripts, interfaces d’exemple et images restent dans leur langue originale et peuvent être expliqués à la demande. Structure, liens et contraintes essentielles sont vérifiés ; aucune relecture par un locuteur natif de chaque langue n’est revendiquée.

