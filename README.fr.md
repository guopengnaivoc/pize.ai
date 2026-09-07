<p align="center">
  <a href="https://pize.ai/fr">
    <img src="assets/pize-logo.svg" width="96" height="96" alt="Pize logo" />
  </a>
</p>

<h1 align="center">pize.ai</h1>

<p align="center"><strong>Un assistant de programmation IA pour le calcul scientifique et l'analyse statistique.</strong></p>
<p align="center">Comprendre les données. Construire l'analyse. Examiner les résultats.</p>

<p align="center">
  <a href="https://pize.ai/fr">Site officiel</a> &middot;
  <a href="https://pize.ai/docs">Documentation</a> &middot;
  <a href="https://pize.ai/download">Téléchargement</a>
</p>

<p align="center" dir="ltr">
  <a href="README.md">简体中文</a> &middot;
  <a href="README.en.md">English</a> &middot;
  <a href="README.de.md">Deutsch</a> &middot;
  <a href="README.ja.md">日本語</a> &middot;
  <a href="README.fr.md">Français</a><br />
  <a href="README.ar.md">العربية</a> &middot;
  <a href="README.es.md">Español</a> &middot;
  <a href="README.hi.md">हिन्दी</a> &middot;
  <a href="README.id.md">Bahasa Indonesia</a> &middot;
  <a href="README.ru.md">Русский</a>
</p>

---

## Écosystème du calcul scientifique

<p align="center">
  <a href="https://pize.ai/zh-Hans/share">
    <img src="assets/scientific-ecosystem.png" width="960" alt="24 langages et outils scientifiques présentés sur le site Pize" />
  </a>
</p>

Ce mur de logos présente les langages et outils de recherche répertoriés sur le site Pize, de l'analyse de données au calcul numérique, à l'apprentissage automatique et à la visualisation. Pize apporte une assistance de programmation IA à ces activités ; la [documentation officielle](https://pize.ai/docs) précise le périmètre de prise en charge, et les logos n'impliquent aucun partenariat ni aucune approbation officielle des marques.

## Pensé pour la recherche, pas seulement pour compléter du code

**Pize est un assistant de programmation IA destiné aux chercheurs qui travaillent avec du code scientifique et des données statistiques.** Il aide à comprendre un projet, préparer une analyse, écrire et exécuter du code, examiner les sorties et les graphiques, puis ajuster la suite. Il s'utilise dans Pize Code, Positron, en ligne de commande ou via le SDK.

Les erreurs apparaissent souvent avant l'ajustement d'un modèle : mauvais séparateur, valeur manquante interprétée comme un nombre ou observation prise pour un en-tête. Pize donne la priorité à la compréhension des données afin de travailler à partir de leur structure plutôt que d'hypothèses sur le contenu du fichier.

Ce dépôt est l'espace public de présentation et de communauté de Pize, maintenu par son fondateur, [@guopengnaivoc](https://github.com/guopengnaivoc).

## Ce que propose Pize

| Fonctionnalité | Apport au travail de recherche |
| --- | --- |
| **Lecture adaptée aux données** | Détecter séparateurs, en-têtes, valeurs manquantes et types de colonnes à partir du contenu ; prendre en compte commentaires, métadonnées et tableaux compressés. |
| **Contexte pour les grands jeux de données** | Fournir une fiche compacte lorsque le budget de contexte est dépassé, avec schéma, petit aperçu et nombre de lignes explicitement estimé. |
| **Session R / Python réelle** | Dans Positron, inspecter la session active et résumer les tableaux de données. Après autorisation, exécuter du code et récupérer des graphiques pour travailler sur des sorties réelles. |
| **Modifications vérifiables** | Coordonner les changements entre fichiers, examiner les différences, annuler des modifications et revenir à un point de contrôle antérieur. |
| **Planification et exécution** | Explorer le projet en mode planification, convenir d'une approche, puis écrire du code et lancer des commandes avec autorisation. |
| **Contexte du projet et du navigateur** | Référencer fichiers, dossiers, problèmes et URL ; utiliser le navigateur, les captures d'écran et les journaux pendant le débogage. |
| **Conventions réutilisables** | Appliquer règles de projet et compétences pour les définitions statistiques, les conventions graphiques et l'organisation des dossiers. |

Pour les formats de recherche comme Parquet, Arrow, RDS, HDF5, h5ad, NumPy, SPSS et Stata, Pize identifie le format et aide à produire le code de chargement approprié. Cela ne signifie pas décoder directement chaque format binaire dans la conversation. La [documentation sur la lecture des données et l'environnement d'exécution](https://pize.ai/docs) précise les comportements et les limites.

## Travailler dans votre environnement habituel

| Interface | Utilisation |
| --- | --- |
| **Pize Code** | Assistance dans l'éditeur, contexte du projet, examen des modifications et travail dans le terminal. |
| **Positron** | Le même agent, avec accès à la session R ou Python déjà active. |
| **CLI** | Utiliser Pize en ligne de commande. |
| **SDK** | Intégrer l'agent et ses capacités orientées données dans vos programmes et outils internes. |

La passerelle vers la session en cours est propre à Positron. Toutes les interfaces ne disposent pas du même accès à l'environnement d'exécution. Consultez la [documentation officielle](https://pize.ai/docs) pour l'installation et les détails.

## Modèles et outils connectés

Pize prend en charge des modèles cloud et locaux, notamment Anthropic, OpenAI, Google Gemini, DeepSeek, AWS Bedrock et OpenRouter, ainsi que des points d'accès compatibles avec OpenAI. Choisissez un fournisseur et une configuration adaptés à votre environnement de recherche.

**Le SDK intègre Pize ; MCP relie Pize aux outils externes.** En tant que client MCP, Pize peut se connecter à des serveurs compatibles pour accéder à des bases de données, systèmes internes et outils de laboratoire. Les opérations disponibles dépendent du serveur et des permissions accordées.

## Premiers pas

1. **Choisir une interface.** Commencez par la [page officielle de téléchargement](https://pize.ai/download) et suivez les instructions adaptées à votre environnement.
2. **Configurer un modèle.** Connectez un fournisseur pris en charge ou un point d'accès local conformément à la documentation.
3. **Fournir le contexte de recherche.** Ouvrez le projet et joignez les scripts ou données utiles. Dans Positron, activez la session contenant les données à analyser.
4. **Planifier, autoriser et itérer.** Convenez de l'approche, examinez les actions proposées, puis inspectez le code, les sorties et les graphiques avant de continuer.

<details>
<summary><strong>Exemples de demandes de recherche</strong></summary>

Ces formulations servent de points de départ ; elles ne constituent pas des résultats validés indépendamment.

- « Examine les colonnes, les types et les valeurs manquantes de ce jeu de données avant de proposer une analyse. »
- « Explique ce pipeline R ou Python et indique les hypothèses que je devrais vérifier. »
- « Aide-moi à modifier ce script d'analyse, exécute-le après autorisation et explique les graphiques de diagnostic. »

</details>

Pize accompagne le travail sans remplacer le jugement scientifique. Vérifiez les hypothèses méthodologiques et les sorties avant de vous fier aux résultats. Le traitement des données dépend des outils et services de modèles configurés ; consultez les [informations de confidentialité](https://pize.ai/privacy) et les politiques de votre fournisseur.

## Ce qui est public ici

Ce dépôt contient des informations produit, des indications pour la communauté et une [visualisation interactive de protéines](https://guopengnaivoc.github.io/pize.ai/) autonome. Cette visualisation est une démonstration visuelle, pas un service de prédiction de protéines ni une preuve de résultats scientifiques validés. Les sources sont indiquées dans les [crédits des protéines](assets/protein-CREDITS.md).

**Le code source de l'application principale Pize n'est pas publié dans ce dépôt.** La publication de la visualisation ne rend pas l'ensemble du produit open source. Certains outils, exemples et notes techniques pourront être publiés séparément, avec leur périmètre et leur licence. Consultez le site officiel pour les logiciels et leur disponibilité actuelle.

## Fondateur, retours et collaboration

Pize a été fondé par [@guopengnaivoc](https://github.com/guopengnaivoc), qui le maintient sous le nom **pize.ai**. Le site est le point d'entrée du produit ; ce dépôt rassemble les informations publiques du projet et les retours de la communauté.

- **Questions produit et demandes de fonctionnalités :** ouvrez une [issue GitHub](https://github.com/guopengnaivoc/pize.ai/issues).
- **Signalements utiles :** précisez l'environnement, la tâche, le comportement attendu, le comportement observé et un exemple minimal. Consultez le [guide de contribution](CONTRIBUTING.md).
- **Collaboration, utilisation en laboratoire ou demande privée :** choisissez l'adresse électronique appropriée ci-dessous.

Ne publiez pas de clés API, d'identifiants, de jeux de données privés ou de travaux de recherche confidentiels dans les issues publiques. Les fonctionnalités actuelles et les instructions figurent sur [pize.ai](https://pize.ai/fr) et dans sa [documentation](https://pize.ai/docs).

## Contacter Pize

Cliquez sur une adresse pour ouvrir votre application de messagerie avec un objet proposé. Ces adresses figurent sur la [page de contact officielle](https://pize.ai/contact).

| Contact | Objet de la demande | Adresse électronique |
| --- | --- | --- |
| **Renseignements généraux** | Questions produit, demandes de presse et informations sur les versions. | [hello@pize.ai](mailto:hello@pize.ai?subject=Pize%20general%20inquiry) |
| **Contact produit** | Démonstrations, questions de mise en place et collaborations. | [contact@pize.ai](mailto:contact@pize.ai?subject=Pize%20product%20inquiry) |
| **Assistance technique** | Compte, documentation, confidentialité et demandes de suppression de données. | [support@pize.ai](mailto:support@pize.ai?subject=Pize%20support%20request) |
| **Affaires et partenariats** | Achats, partenariats de recherche et demandes commerciales. | [business@pize.ai](mailto:business@pize.ai?subject=Pize%20business%20inquiry) |
