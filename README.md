# Paquet_Tracer

# Cisco Packet Tracer — Projets & TP Réseaux

Ce dépôt contient mes projets et TP réalisés sur **Cisco Packet Tracer** (fichiers `.pkt`) : topologies, ARP, switching, routage statique, etc.

## Objectifs

- Comprendre le fonctionnement des réseaux LAN/WAN
  
- Manipuler **switches / routeurs**
  
- Observer et analyser : **ARP, tables MAC, routage statique**
  
- Tester la connectivité (ping, traceroute, show commands)

## Prérequis

- **Cisco Packet Tracer** (version recommandée : 8.x ou plus récente)
  
- Un PC Windows/Linux/macOS

## Comment utiliser

1. Cloner le dépôt :
   
   ```bash
   
   git clone https://github.com/<TON-USER>/<TON-REPO>.git
   
Ouvrir un fichier .pkt avec Packet Tracer :

File → Open → sélectionner le .pkt

Lire les consignes / objectifs du TP (si un fichier TP.md existe) puis lancer les tests (ping, show, simulation).

2. Contenu du dépôt

TP / Projets disponibles

tp3.hub.pkt : Topologie avec hub

tp3.switch.pkt : Topologie avec switch

tp3.switch.hub.pkt : Comparaison switch vs hub

tp3.2switch.routeur.pkt : 2 switches + routeur

tp_table_arp_switch.pkt : Table ARP / table MAC sur switch

tp_arp_routeur_2switch.pkt : ARP avec routeur + 2 switches

tproutage_statique_simple.pkt : Routage statique (simple)

tp_routage_statique_des_commandes_en_plus.pkt : Routage statique + commandes supplémentaires

Chaque fichier contient la topologie + configurations nécessaires (ou à compléter selon le TP).

3. Commandes utiles (rappel)

### Tester :

ping <IP>

tracert <IP> (PC) / traceroute <IP> (routeur selon modèle)

### Switch :

show mac address-table

show running-config

### Routeur :

show ip interface brief

show ip route

show arp

show running-config

### Auteur

Abdallah Samy HAMDOUCHE
