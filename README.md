# ROBOGUIDETOOL 2026

[Français](#français) · [English](#english)

![ROBOGUIDETOOL 2026](docs/image.png)

## Français

Outil Windows pour les robots FANUC : il lit une sauvegarde (MD) ou le robot lui-même et en sort un audit complet en HTML.

### Ce que fait l'outil

- Fiche robot, registres, outils et repères, programmes et arbre des appels
- Zones Space et DCS en 3D, cohérence Space / DCS, équations Safe I/O affichées en schéma
- Fiche de communication (EtherNet/IP, PROFINET), signaux UOP, logique de fond
- Contrôles des programmes : labels, sauts, WAIT sans TIMEOUT, références croisées des registres et des E/S
- Charges utiles, compteurs horaires, alarmes récurrentes, batteries
- Connexion au robot ou à ROBOGUIDE par HTTP, KCL, FTP (SNPX et RMI en option)

**L'audit est entièrement en lecture seule.** Quelques fonctions d'écriture existent en dehors de l'audit (registres, acquittement d'alarmes, affectations SNPX) : elles ne se déclenchent que sur action de l'utilisateur, avec une confirmation qui rappelle l'impact sur le robot. Aucune action sur la sécurité DCS.

### État du projet

Projet en cours de développement. Ce dépôt sert pour l'instant de présentation : le but est de recueillir des avis avant d'aller plus loin.

### Retours

Vos remarques et idées sont les bienvenues :

- par les [Issues](../../issues) de ce dépôt
- par e-mail : rrobotique@proton.me

## English

A Windows tool for FANUC robots: it reads a backup (MD) or the robot itself and produces a complete audit as HTML reports.

### What the tool does

- Robot data sheet, registers, tools and user frames, programs and call tree
- Space zones and DCS zones in 3D, Space / DCS consistency check, Safe I/O equations shown as a ladder-style diagram
- Communication sheet (EtherNet/IP, PROFINET), UOP signals, background logic
- Program checks: labels, jumps, WAIT without TIMEOUT, cross-references of registers and I/O
- Payloads, operating hours, recurring alarms, batteries
- Connection to the robot or to ROBOGUIDE over HTTP, KCL, FTP (SNPX and RMI optional)

**The audit is entirely read-only.** A few write functions exist outside the audit (registers, alarm reset, SNPX assignments): they only run on an explicit user action, after a confirmation that recalls the impact on the robot. No action is taken on DCS safety.

### Project status

Work in progress. For now this repository is a presentation only: the goal is to collect opinions before going further. The user interface and the reports are currently in French.

### Feedback

Comments and ideas are welcome:

- through the [Issues](../../issues) of this repository
- by e-mail: rrobotique@proton.me

---

FANUC and ROBOGUIDE are trademarks of FANUC Corporation. This tool is an independent project, not affiliated with FANUC.
FANUC et ROBOGUIDE sont des marques de FANUC Corporation. Cet outil est un projet indépendant, sans lien avec FANUC.
