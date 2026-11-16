# NEXORA-Projet1-SISR

Dépôt commun du binôme pour la conception, le déploiement et la documentation des sites de **Toulouse** (35 collaborateurs) et **Marseille** (30 collaborateurs).

## Répartition du binôme et convention de nommage
* **Toulouse (`PC-*`) – Étudiant A** : Pare-feu `PC-FW-TLS`, réseaux locaux (VLAN 10/20/30), domaine `tls.ad.nexora.test`, serveurs Windows (`PC-DC01-TLS`, `PC-DC02-TLS`, `PC-FS-TLS`), GPO et ERP **Dolibarr** (`PC-DOLIBARR-TLS`).
* **Marseille (`LG-*`) – Étudiant B (Ludivine)** : Pare-feu `LG-FW-MRS`, réseaux locaux (VLAN 10/20/30), domaine `mrs.ad.nexora.test`, serveurs Windows (`LG-DC01-MRS`, `LG-DC02-MRS`, `LG-FS-MRS`), GPO et outil ITSM **GLPI** (`LG-GLPI-MRS`).

## Structure du dépôt
* `00_contexte/` : Présentation de NEXORA, besoins, contraintes et hypothèses.
* `01_conception/` : Inventaire des VM, plan d'adressage IP, matrice des flux et convention de nommage.
* `02_maquette/` : Schémas logiques et techniques (Draw.io), captures de l'hyperviseur.
* `03_toulouse/` : Configurations, preuves et procédures du site de Toulouse.
* `04_marseille/` : Configurations, preuves et procédures du site de Marseille.
* `05_tests/` : Cahiers de recette et fiche de revue croisée.
* `06_documentation/` : Dossier d'architecture et dossier d'exploitation initial.
* `07_scripts/` : Scripts d'automatisation (PowerShell / CSV).
