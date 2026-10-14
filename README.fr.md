# Mole App

[English](README.md) · [简体中文](README.zh-CN.md) · [繁體中文](README.zh-TW.md) · [日本語](README.ja.md) · [한국어](README.ko.md) · [Deutsch](README.de.md) · Français · [Español](README.es.md) · [Italiano](README.it.md) · [Português (Brasil)](README.pt-BR.md)

Documentation officielle et assistance communautaire pour **Mole for Mac** et **Mole for Windows**.

Les apps Mac et Windows sont des applications de bureau natives et payantes, dont les licences financent le développement et les mises à jour. Ce dépôt sert à la documentation, aux questions et aux retours, et ne contient pas le code source des apps. Le [Mole CLI](https://github.com/tw93/Mole) reste gratuit et open source.

## Obtenir Mole

| App | Configuration requise | Téléchargement | Guide d’utilisation |
| --- | --- | --- | --- |
| Mole for Mac | macOS 14 ou ultérieur, Apple Silicon ou Intel | [Site Mac](https://mole.fit/fr/?utm_source=github.com&utm_medium=referral&utm_campaign=mole-app-readme) | [Aide Mac](https://mole.fit/fr/help?utm_source=github.com&utm_medium=referral&utm_campaign=mole-app-readme) |
| Mole for Windows | Windows 10 22H2 ou Windows 11, x64 ou ARM64 | [Site Windows](https://mole.fit/fr/windows?utm_source=github.com&utm_medium=referral&utm_campaign=mole-app-readme) | [Aide Windows](https://mole.fit/fr/windows/help?utm_source=github.com&utm_medium=referral&utm_campaign=mole-app-readme) |

Les deux apps réunissent dans une seule interface le nettoyage, la gestion des apps, la maintenance, l’analyse du disque et l’état du système en direct.

### Mole for Mac

Mole for Mac est une app SwiftUI native créée et maintenue par [Tw93](https://github.com/tw93), avec des outils rapides dans la barre des menus.

![Écran de nettoyage de Mole for Mac](https://mole.fit/img/fr/clean.jpg)

| Outil | Ce que vous pouvez faire | Guide |
| --- | --- | --- |
| Nettoyer | Passer en revue les caches des apps et des navigateurs, les journaux et les fichiers de compilation des outils de développement avant de choisir ce qu’il faut supprimer | [Nettoyage du Mac](https://mole.fit/fr/mac-cleaner?utm_source=github.com&utm_medium=referral&utm_campaign=mole-app-readme) |
| Apps | Désinstaller des apps, vérifier leurs résidus, rechercher les mises à jour et gérer les éléments de démarrage | [Gestion des apps](https://mole.fit/fr/mac-app-uninstaller?utm_source=github.com&utm_medium=referral&utm_campaign=mole-app-readme) |
| Optimiser | Lancer la maintenance de macOS, utiliser Nettoyer l’écran ou Écran allumé | [Maintenance du Mac](https://mole.fit/fr/mac-optimizer?utm_source=github.com&utm_medium=referral&utm_campaign=mole-app-readme) |
| Analyser | Repérer les gros fichiers et dossiers avec un treemap du disque, les afficher dans le Finder ou placer les éléments sélectionnés dans la Corbeille | [Analyse du disque](https://mole.fit/fr/mac-disk-analyzer?utm_source=github.com&utm_medium=referral&utm_campaign=mole-app-readme) |
| État | Consulter le CPU, la mémoire, le stockage, le réseau et la température, avec des mesures au choix dans la barre des menus | [Moniteur système](https://mole.fit/fr/mac-system-monitor?utm_source=github.com&utm_medium=referral&utm_campaign=mole-app-readme) |

#### Nettoyage IA · Bêta

La version bêta ajoute Nettoyage et entretien des outils d’IA dans Nettoyer. Elle passe en revue les caches, anciennes versions, anciennes sessions, worktrees nettoyables et outils en ligne de commande inactifs de Claude Code, Codex, Cursor et d’autres outils d’IA. Les caches sont cochés par défaut, tandis que les sessions et les outils demandent votre validation. Les mémoires, les plans et les skills sont exclus. Pour les modèles locaux, seuls les modèles Ollama inutilisés depuis un mois sont listés, pour que vous les sélectionniez et les supprimiez via Ollama. Consultez le [guide du nettoyage IA](https://mole.fit/fr/docs?utm_source=github.com&utm_medium=referral&utm_campaign=mole-app-readme#docs-ai) pour les détails.

### Démarrer sur votre Mac

1. Téléchargez le DMG depuis le site Mac ci-dessus, faites glisser Mole dans Applications et ouvrez-le. Si vous utilisez déjà Homebrew, `brew install --cask mole-app` installe l’app Mac.
2. Lancez une analyse et vérifiez les résultats avant de supprimer quoi que ce soit. Si Mole signale l’absence de l’accès complet au disque, suivez le guide des autorisations ci-dessous et relancez l’app.
3. Après l’achat, ouvrez le panneau Licence avec `Cmd + Shift + L`, collez la clé reçue dans l’email de Dodo Payments et cliquez sur Activer.

[Articles Mac](https://mole.fit/fr/blog?utm_source=github.com&utm_medium=referral&utm_campaign=mole-app-readme) · [Notes de version Mac](https://mole.fit/fr/releases?utm_source=github.com&utm_medium=referral&utm_campaign=mole-app-readme)

### Guides Mac à lire en priorité

- [Mole CLI ou app Mac](https://mole.fit/fr/blog/mole-cli-vs-mac-app?utm_source=github.com&utm_medium=referral&utm_campaign=mole-app-readme) : ce qui distingue l’outil gratuit en terminal de l’app native payante.
- [Mole est-il sûr sur Mac ?](https://mole.fit/fr/blog/is-mole-safe?utm_source=github.com&utm_medium=referral&utm_campaign=mole-app-readme) : ce qui va dans la Corbeille, ce qui est supprimé définitivement et ce qui reste protégé.
- [Que sont les données système sur Mac ?](https://mole.fit/fr/blog/what-is-system-data-on-mac?utm_source=github.com&utm_medium=referral&utm_campaign=mole-app-readme) : trouver ce qui occupe de la place avant de supprimer quoi que ce soit.
- [Vérifier les résidus de désinstallation sur Mac](https://mole.fit/fr/blog/mac-uninstall-leftovers-review-before-delete?utm_source=github.com&utm_medium=referral&utm_campaign=mole-app-readme) : contrôler la propriété des fichiers et les données partagées avant la suppression.
- [Supprimer les modèles Ollama et LM Studio](https://mole.fit/fr/blog/how-to-remove-ai-tool-leftovers-mac?utm_source=github.com&utm_medium=referral&utm_campaign=mole-app-readme) : distinguer modèles téléchargés, caches et données personnelles.
- [Tester les apps Mac pour Mole](https://mole.fit/fr/blog/testing-mac-apps-one-by-one?utm_source=github.com&utm_medium=referral&utm_campaign=mole-app-readme) : ce que révèlent les vraies installations et les tests de désinstallation.

### Mole for Windows

L’app Windows s’améliore à chaque version.

![Écran de nettoyage de Mole for Windows](https://mole.fit/img/windows-fr/clean.jpg)

[Articles Windows](https://mole.fit/windows/blog?utm_source=github.com&utm_medium=referral&utm_campaign=mole-app-readme) · [Notes de version Windows](https://mole.fit/windows/releases?utm_source=github.com&utm_medium=referral&utm_campaign=mole-app-readme)

## Retours

- [Signaler un bug de l’app Mac](https://github.com/tw93/Mole-App/issues/new?template=mac_bug.yml)
- [Signaler un bug de l’app Windows](https://github.com/tw93/Mole-App/issues/new?template=windows_bug.yml)
- [Suggérer une fonctionnalité](https://github.com/tw93/Mole-App/issues/new?template=feature_request.yml)
- [Poser une question ou rejoindre une discussion](https://github.com/tw93/Mole-App/discussions)

Les issues et les discussions sont publiques. Pour un achat, une activation ou un remboursement, écrivez à [hi@mole.fit](mailto:hi@mole.fit). Envoyez les signalements de sécurité par le [canal de signalement privé](.github/SECURITY.md).

Pour un diagnostic sur Mac, ouvrez le menu du logo Mole et choisissez Lancer le diagnostic. Envoyez le rapport en privé à [hi@mole.fit](mailto:hi@mole.fit), avec la version de l’app et ce qui s’est passé.

Pour les bugs et demandes de fonctionnalités du CLI, utilisez [tw93/Mole](https://github.com/tw93/Mole/issues).

## FAQ

### Un dépôt GitHub public signifie-t-il que les apps sont open source ?

Ce dépôt contient la documentation et les retours de la communauté. Le code source des apps Mac et Windows est privé. Le [Mole CLI](https://github.com/tw93/Mole) est gratuit et open source.

### Dois-je installer le CLI pour utiliser les apps ?

Non. Mole for Mac et Mole for Windows sont des apps de bureau autonomes. Installer le CLI n’installe aucune des deux.

### Les apps sont-elles gratuites ?

Les apps reposent sur des licences à paiement unique. Mole for Mac coûte **$19 USD pour deux Mac**, sans abonnement et avec des mises à jour gratuites, y compris pour les versions majeures. La [page officielle des tarifs](https://mole.fit/pricing.md?utm_source=github.com&utm_medium=referral&utm_campaign=mole-app-readme) donne les conditions actuelles. Le prix et la disponibilité de Windows figurent sur son site. Le CLI open source est gratuit.

### Puis-je essayer l’app Mac avant d’acheter ?

L’analyse est gratuite, et chaque outil payant offre deux essais. Vous pouvez consulter l’analyse du disque et l’état du système sans licence. Le [centre d’aide Mac](https://mole.fit/fr/help?utm_source=github.com&utm_medium=referral&utm_campaign=mole-app-readme) explique comment télécharger, essayer et activer l’app.

### Puis-je transférer ma licence Mac sur un nouvel ordinateur ?

Ouvrez le panneau Licence sur l’ancien Mac avec `Cmd + Shift + L`, désactivez-la, puis activez la même clé sur le nouveau Mac. Si l’ancien Mac n’est plus disponible, connectez-vous au [portail client Dodo Payments](https://customer.dodopayments.com/) avec l’email d’achat et désactivez-la depuis là. Le nombre d’appareils dépend de la licence achetée. L’édition actuelle couvre deux Mac.

### Où trouver ma clé de licence et ma facture ?

Cherchez Dodo Payments dans votre boîte de réception et vos spams, ou connectez-vous au [portail client Dodo Payments](https://customer.dodopayments.com/) avec l’email utilisé au paiement pour retrouver la clé, la commande et la facture. Si vous avez encore besoin d’aide, écrivez à [hi@mole.fit](mailto:hi@mole.fit) avec votre email d’achat ou votre Payment ID. Ne publiez pas ces informations dans les issues publiques.

### Et si l’app Mac ne me convient pas ?

Écrivez à [hi@mole.fit](mailto:hi@mole.fit) dans les 14 jours suivant l’achat, avec votre Payment ID ou votre email d’achat. La [politique de remboursement](https://mole.fit/fr/refund?utm_source=github.com&utm_medium=referral&utm_campaign=mole-app-readme) donne les conditions complètes.

### L’app Mac envoie-t-elle mes fichiers ou les résultats d’analyse ?

L’analyse et le nettoyage se font en local sur votre Mac. Mole n’envoie ni le contenu des fichiers, ni leurs noms, ni les résultats d’analyse, et son journal d’opérations local n’est pas envoyé automatiquement. La [politique de confidentialité](https://mole.fit/fr/privacy?utm_source=github.com&utm_medium=referral&utm_campaign=mole-app-readme) explique l’activation de la licence, les mises à jour et les autres fonctions qui contactent des services en ligne.

### Pourquoi Mole demande-t-il l’accès complet au disque ?

macOS restreint l’accès à certaines données des apps. L’accès complet au disque permet à Mole d’inspecter ces emplacements. Les chemins protégés et votre liste protégée continuent de s’appliquer, donc cet accès ne fait pas de chaque fichier un candidat au nettoyage. Consultez le [guide des autorisations](https://mole.fit/fr/help?utm_source=github.com&utm_medium=referral&utm_campaign=mole-app-readme#doctor-permission-fda).

### Puis-je restaurer des fichiers après un nettoyage sur Mac ?

Les apps désinstallées et leurs fichiers résiduels sélectionnés vont dans la Corbeille et peuvent être restaurés tant qu’ils y restent. Le nettoyage des caches est définitif par défaut, avec une option Corbeille dans les Réglages. Certaines actions de maintenance suppriment les données directement et ne peuvent pas être annulées. Le [guide de sécurité](https://mole.fit/fr/blog/is-mole-safe?utm_source=github.com&utm_medium=referral&utm_campaign=mole-app-readme) détaille chaque opération.

### Comment fonctionnent les mises à jour de l’app Mac et les fonctions bêta ?

Mole intègre un outil de mise à jour, et les [notes de version officielles](https://mole.fit/fr/releases?utm_source=github.com&utm_medium=referral&utm_campaign=mole-app-readme) décrivent chaque version. Les fonctions marquées Preview dans la documentation nécessitent la version bêta jusqu’à leur arrivée dans une version stable.

### Puis-je utiliser Mole avec le clavier ou VoiceOver ?

Mole prend en charge la navigation au clavier et VoiceOver. Le treemap est visuel, et vous pouvez parcourir les mêmes fichiers dans la liste Plus gros fichiers au clavier ou avec VoiceOver. Consultez le [guide d’accessibilité](https://mole.fit/fr/help?utm_source=github.com&utm_medium=referral&utm_campaign=mole-app-readme) pour les détails et les limites actuelles.

### Quel site est le site officiel ?

**mole.fit** est le site officiel des apps. Utilisez les liens de téléchargement ci-dessus pour obtenir les paquets à jour. Le CLI gratuit se trouve sur [tw93/Mole](https://github.com/tw93/Mole).

### Où trouver des instructions détaillées ?

La [documentation Mac](https://mole.fit/fr/docs?utm_source=github.com&utm_medium=referral&utm_campaign=mole-app-readme) explique les outils et leurs règles de sécurité. Le [catalogue des apps testées](https://mole.fit/fr/tested-apps?utm_source=github.com&utm_medium=referral&utm_campaign=mole-app-readme) contient des notes d’installation, de désinstallation et de résidus pour chaque app. Pour l’installation, l’activation ou le dépannage, consultez le [centre d’aide Mac](https://mole.fit/fr/help?utm_source=github.com&utm_medium=referral&utm_campaign=mole-app-readme) ou le [centre d’aide Windows](https://mole.fit/fr/windows/help?utm_source=github.com&utm_medium=referral&utm_campaign=mole-app-readme). Les conditions de licence figurent dans les [conditions d’utilisation](https://mole.fit/fr/terms?utm_source=github.com&utm_medium=referral&utm_campaign=mole-app-readme).
