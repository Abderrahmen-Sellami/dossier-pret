# Dossier Prêt · ملف جاهز

**Pré-contrôle automatique des dossiers administratifs, avant le passage au guichet.**

Dossier Prêt est un workflow automatisé qui vérifie le dossier administratif d'un citoyen avant qu'il ne se déplace. Il ne remplace aucun processus existant : il ajoute une couche de vérification par-dessus.

**Démo en ligne :** https://abderrahmen-sellami.github.io/dossier-pret/

## Le problème

Beaucoup de dossiers sont refusés au guichet pour des raisons évitables : une pièce manquante, un document expiré, ou un nom écrit différemment d'un document à l'autre (Trabelsi, Trablsi, الطرابلسي).

## Le workflow

1. Réception du dossier
2. Contrôle de complétude (pièces obligatoires)
3. Contrôle de validité (dates d'émission et d'expiration)
4. Cohérence croisée (nom arabe/latin, date de naissance, n° CIN)
5. Vérification auprès des institutions concernées
6. Décision « prêt » ou « à corriger », avec notification au citoyen
7. Rappels programmés (relance, expirations, date limite)

## Fonctionnalités du prototype

- Trois démarches : bourse universitaire, passeport, création de SUARL
- Comparaison des noms entre écriture arabe et latine par squelette consonantique
- Rapport avec indice de préparation, actions correctives et message de notification
- Vue guichet pour l'agent administratif
- Page explicative : du prototype à la production (webhook, OCR, API d'interopérabilité, tâches planifiées)

## Limites

Les règles, délais et montants sont fictifs et paramétrables. Les institutions sont simulées. Toutes les données sont fictives.

## Auteur

**Abderrahmen Sellami**, étudiant en 3ᵉ année de licence en informatique appliquée à la gestion, ESSECT Tunis.
[LinkedIn](https://linkedin.com/in/abderrahmen-sellami) · [Portfolio](https://abderrahmen-sellami.github.io)

## Droits

© 2026 Abderrahmen Sellami. Tous droits réservés. Ce dépôt est publié à titre de démonstration uniquement. Aucune licence n'est accordée : toute copie, modification, redistribution ou réutilisation, totale ou partielle, sans autorisation écrite de l'auteur est interdite. Voir [LICENSE](LICENSE) et [PATERNITE.md](PATERNITE.md).
