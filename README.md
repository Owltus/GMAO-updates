# GMAO-updates - Releases publiques de GMAO

## À propos de ce repository

Ce repository contient uniquement les **releases publiques** de GMAO (Gestion de Maintenance Assistée par Ordinateur). Il s'agit d'un espace de distribution pour les versions compilées de l'application.

> **Note importante** : Le code source de GMAO est maintenu dans un repository privé. Ce repository public ne contient que les fichiers exécutables prêts à l'emploi.

## Qu'est-ce que GMAO ?

GMAO est une application de bureau moderne pour la **Gestion de Maintenance Assistée par Ordinateur**. Elle permet de gérer l'ensemble des opérations de maintenance préventive et corrective d'une organisation.

### Points clés

- 🖥️ **Application desktop** multiplateforme (Windows, macOS, Linux)
- 🔒 **100% locale** - Toutes vos données restent sur votre ordinateur
- 👤 **Mono-utilisateur** - Simple et sans gestion de comptes
- 🚀 **Prête à l'emploi** - Aucune configuration serveur requise
- 🛡️ **Sécurisée** - Fonctionne sans connexion internet

### Fonctionnalités principales

- 📋 Gestion des maintenances préventives et correctives
- 🏢 Gestion des prestataires et contrats
- 📝 Ordres de travail avec suivi complet
- 📊 Tableau de bord et statistiques
- 📁 Gestion documentaire intégrée
- 🌍 Organisation par sites et zones

## Téléchargement et installation

### 1. Télécharger la dernière version

Rendez-vous dans la section [**Releases**](https://github.com/Owltus/GMAO-updates/releases) de ce repository et téléchargez la version correspondant à votre système d'exploitation :

- **Windows** : `GMAO-Setup-[version].exe`
- **macOS** : `GMAO-[version].dmg`
- **Linux** : `GMAO-[version].AppImage` ou `.deb`

### 2. Installation

#### Windows
1. Double-cliquez sur le fichier `.exe` téléchargé
2. Suivez l'assistant d'installation
3. L'application sera disponible dans le menu Démarrer

#### macOS
1. Double-cliquez sur le fichier `.dmg`
2. Glissez l'application GMAO dans le dossier Applications
3. Lors du premier lancement, faites clic droit → Ouvrir

#### Linux
- **AppImage** : Rendez le fichier exécutable (`chmod +x`) puis double-cliquez
- **Deb** : Double-cliquez ou utilisez `sudo dpkg -i GMAO-[version].deb`

## Première utilisation

Au premier démarrage, GMAO créera automatiquement :
- Une base de données locale dans votre dossier utilisateur
- Un dossier pour stocker les documents attachés

Aucune configuration supplémentaire n'est nécessaire. L'application est immédiatement opérationnelle.

## Mises à jour

Les nouvelles versions sont publiées régulièrement dans ce repository. Pour mettre à jour :

1. Vérifiez la [dernière release](https://github.com/Owltus/GMAO-updates/releases/latest)
2. Téléchargez la nouvelle version
3. Installez par-dessus l'ancienne (vos données seront conservées)

> 💡 **Astuce** : Activez les notifications GitHub (bouton Watch) pour être informé des nouvelles versions.

## Support et documentation

### Besoin d'aide ?

- 📖 Consultez la [documentation complète](https://github.com/Owltus/GMAO-updates/wiki) (à venir)
- 🐛 Signalez un bug dans les [Issues](https://github.com/Owltus/GMAO-updates/issues)
- 💡 Proposez des améliorations dans les [Discussions](https://github.com/Owltus/GMAO-updates/discussions)
- 📧 Contact direct : pl.bessonneau@gmail.com

### Configuration système requise

- **Système d'exploitation** : Windows 10+, macOS 10.13+, ou Linux moderne
- **Mémoire RAM** : 4 GB minimum (8 GB recommandé)
- **Espace disque** : 200 MB pour l'application + espace pour vos données
- **Résolution** : 1280x720 minimum

## À propos du développement

Cette application a été développée par un technicien de maintenance sans compétences particulières en programmation, grâce à l'assistance de l'IA Claude Sonnet 4. Elle démontre qu'il est possible de créer des outils professionnels en se concentrant sur les besoins métier.

### Technologies utilisées

- Electron + Vue.js 3 + TypeScript
- Base de données SQLite locale
- Interface moderne avec Tailwind CSS

## Licence

### 🆓 Gratuit pour usage personnel
- ✅ Particuliers et usage personnel
- ✅ Étudiants et enseignants
- ✅ Associations à but non lucratif
- ✅ Auto-entrepreneurs (CA < 30k€/an)

### 💼 Licence commerciale requise
- 🏢 Entreprises et sociétés
- 💰 Usage commercial ou professionnel
- 🏭 Collectivités et services publics
- 📧 Tarifs sur devis uniquement

**[Voir les détails de la licence](LICENSE.md)** | **[Demander un devis](mailto:pl.bessonneau@gmail.com?subject=Demande%20de%20licence%20commerciale%20GMAO)**

## Changelog

Consultez le [CHANGELOG](https://github.com/Owltus/GMAO-updates/releases) pour l'historique détaillé des versions.

---

**Version actuelle** : Voir la [dernière release](https://github.com/Owltus/GMAO-updates/releases/latest)

_GMAO - Une solution simple et efficace pour votre gestion de maintenance_

Développé avec passion par un technicien pour des techniciens.
