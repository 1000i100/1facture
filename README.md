1facture
========

Application web minimaliste pour gérer ses devis et factures en auto-entrepreneur



Entièrement développé en TDD, les bug devrait être rare et corrigé efficacement.
L'applicaiton peut fonctionner hors ligne dans le navigateur (y compris la génération de pdfgrace à http://jspdf.com/ )
Elle se syncronise avec le serveur de votre choix (la partie serveur est limité au stricte minimum pour permettre d'utiliser aussi bien du php/mysql que du node.js/mangodb ou tout autre format de stockage.

L'application permet de :
- Créer/modifier des services (pas de gestion des stocks pour l'instant)
- Créer/modifier des contacts (prospect, client...)
- Créer/modifier des devis
- Créer des factures pdf (de zero ou depuis un devis)
- Envoyer des document par email aux clients
- Gérer des abonnement (génération et envoi de facture periodiquement)
- Créer des avoirs
- Gérer des paiements et générer des relances

- des statistique, bilan et autres données analytiques sont prévu.

Ne gère pas la TVA, le multi langue, le multi devise, le multi utilisateur (enfin, ils ne sont pas différencié et il peut y avoir des souci de syncro), le multi structure la trésorerie plus complexe que celle des auto-entrepreneur prestataire de service, le personnel, les stocks, ni surement bien d'autre choses.
