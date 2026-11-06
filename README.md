# KABAMAN — Gestion commerciale

Application web légère en français, basée sur les flux des classeurs fournis.

## Ouvrir l’application

Ouvre le fichier index.html dans un navigateur récent. Aucun serveur ni compte n’est requis.

## Fonctions incluses

- Calcul du coût d’un produit ou répartition des frais d’une importation multi-produits au prorata de la valeur d’achat.
- Conversion des achats en EUR vers DA avec un taux modifiable.
- Calcul des prix de gros et de détail à partir du coût réel et des majorations configurées.
- Catalogue de produits, prix négociés, quantités achetées, ventes et stock restant.
- Création de factures avec choix Gros / Détail / Négocié, remise, paiement et impression bilingue français-arabe.
- Saisie de ventes, historique, suivi des paiements et analyse du chiffre d’affaires et du bénéfice brut.
- Import et export CSV du catalogue, export CSV des ventes, sauvegarde et restauration JSON de toutes les données.

## Données et confidentialité

Les données sont enregistrées dans le stockage local du navigateur sur cet appareil. Elles ne sont pas envoyées à un serveur. Télécharge une sauvegarde JSON régulièrement. Pour déplacer l’application ou changer d’appareil, restaure cette sauvegarde dans le navigateur de destination.

## Premiers pas

1. Ouvre **Paramètres** et vérifie les marges, taux, charges et coordonnées de KABAMAN.
2. Dans **Calcul des coûts**, saisis les frais et les produits de l’import. Ajoute le résultat au catalogue.
3. Vérifie le stock et les prix dans **Produits & stock**.
4. Prépare une facture dans **Factures** ou saisis une vente dans **Ventes**.
5. Consulte les résultats dans **Rentabilité**.

Les coordonnées professionnelles ne sont pas préremplies dans la version destinée au dépôt public. Renseigne-les dans **Paramètres** avant d’imprimer tes factures.

Les valeurs initiales (CASNOS, impôt, douane, banque et taux EUR/DA) proviennent des fichiers source et doivent être vérifiées pour chaque opération. Le bénéfice affiché est un bénéfice brut produit; il ne déduit pas toutes les charges fixes de l’entreprise.

