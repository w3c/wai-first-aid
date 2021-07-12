---
# translation notes are after "#" in this section

title: "Questions urgentes en matière d'accessibilité Web : des solutions provisoires"
title_html: "Questions urgentes en matière d'accessibilité Web :<br> des solutions provisoires"
nav_title: des solutions provisoires
layout: default
ref: /planning/interim-repairs/   # Translators, do not change this

github:
  repository: w3c/wai-first-aid
  path: content/index.fr.md    # Add the language shortcode to the middle of the filename, for example: index.fr.md
permalink: /planning/interim-repairs/fr   # Add the language shortcode to the end, with no slash at end, for example: /planning/interim-repairs/fr

lang: fr   # Change "en" to the translated language shortcode
last_updated: 2020-12-22   # Put the date of this translation YYYY-MM-DD (with month in the middle)
translators:   # remove from the beginning of the line: "# " and add your name(s)
- name: "Sofia Ahmed"
contributors:
- name: "Sandra Velarde Velazquez (ETNIC)"

feedbackmail: wai@w3.org
footer: >
  <p><strong>Date :</strong> Mise à jour : 9 janvier 2019. Première publication en mars 2006.<br>Historique : précédemment intitulé "Amélioration à court terme de l'accessibilité de votre site Web" et "Amélioration de l'accessibilité de votre site Web".</p>
  <p><strong>Rédacteur : </strong><a href="https://www.w3.org/People/shadi/">Shadi Abou-Zahra</a>. Rédacteurs précédents : <a href="https://www.w3.org/People/kevin">Kevin White</a> et <a href="https://www.w3.org/People/Shawn/">Shawn Lawton Henry</a>.  Contributeurs précédents : Sharron Rush, Anna Belle Leiserson, Judy Brewer, et les participants au <a href="https://www.w3.org/WAI/EO/participants">EOWG</a>.</p>
  <p>Développé par le Groupe de travail Éducation et Promotion (<a href="http://www.w3.org/WAI/EO/">EOWG</a>). Initialement développé avec le soutien du projet de l'<a href="https://www.w3.org/WAI/TIES/"><acronym title="Initiative pour l'accessibilité Web : formation, implémentation, éducation, aide">WAI-TIES</acronym></a>, mis à jour par la suite avec le soutien du projet de l'<a href="https://www.w3.org/WAI/ACT/"><acronym title="Initiative pour l'accessibilité Web - Cooperation Framework for Guidance on Advanced Technologies, Evaluation Methodologies, and Research Agenda Setting to Support Accessibility">WAI-ACT</acronym> </a>, et enfin avec le soutien du projet <a href="https://www.w3.org/WAI/DEV/"><acronym>WAI-DEV</acronym></a>.</p>
---


{::nomarkdown}
{% include box.html type="start" h="2" title="Résumé" class="full" %}
{:/}

Vous avez besoin de répondre à une question urgente en matière d'accessibilité pour un projet Web déjà en cours ?
Cette page fournit un bref aperçu et des conseils pour vous aider à répondre aux problèmes les plus critiques.
Retrouvez une approche plus détaillée des questions en matière d'accessibilité pour tout le processus de conception et de développement sur [Organisation et gestion de l'accessibilité Web]({{ "/planning-and-managing/" | relative_url }}).

{::nomarkdown}
{% include box.html type="end" %}
{:/}

{::options toc_levels="2" /}
{::nomarkdown}
{% include_cached toc.html type="start" title="Table des matières" class="full" %}
{:/}
-   TOC is created automatically.
{:toc}
{::nomarkdown}
{% include_cached toc.html type="end" %}
{:/}


Ressources essentielles pour les designers et les développeurs {#resources}
------------------------------------------

-   [Conseils pour démarrer]({{ "/tips/" | relative_url }}) — Des considérations d'ordre pratique illustrées par des exemples pour la conception, la rédaction et le développement de contenus Web accessibles.
-   [Tutoriels pour l'accessibilité Web](https://www.w3.org/WAI/tutorials/) —
    Des informations détaillées sur des sujets bien précis et de l'aide pour répondre aux besoins en accessibilité.
-   [Comment satisfaire aux exigences des WCAG (Référence rapide)](https://www.w3.org/WAI/WCAG20/quickref/) — Une référence rapide personnalisable aux Règles pour l'accessibilité des contenus Web (WCAG) 2.

Qu'est-ce que l'accessibilité Web ? {#understand}
----------------------

Si êtes novice en matière d'accessibilité, il est souvent utile de commencer par comprendre les bases de l'accessibilité :

-   [Introduction à l'accessibilité Web](https://www.w3.org/WAI/fundamentals/accessibility-intro/) — Introduit les concepts essentiels, les arguments et les ressources.
-   [L'accessibilité Web illustrée]({{ "/perspective-videos/" | relative_url }}) — Vidéos non techniques de courte durée introduisant les caractéristiques de l'accessibilité et les avantages pour tous.

### Plus de contexte {#background}

Pour une approche plus approfondie :

-   [Comment les personnes handicapées utilisent le Web]({{ "/people-use-web/" | relative_url }}) — Introduit les expériences et la terminologie en matière d'accessibilité et de handicap.
-   [Les principes d'accessibilité]({{ "/fundamentals/accessibility-principles/" | relative_url }})
    — Introduit les exigences en termes d'accessibilité définies par les Règles du W3C.

Identifier les problèmes {#explore}
-------------------

Si vous avez déjà détecté les problèmes d'accessibilité, vous pouvez passer cette section. Si vous avez besoin d'identifier les problèmes potentiels, ces ressources peuvent vous aider :

-   [Vérifications simples — Une première analyse de l'accessibilité Web]({{ "/test-evaluate/preliminary/" | relative_url }}) —
    Des vérifications simples qui peuvent être menées par tous, quelles que soient les compétences ou les connaissances en matière d'accessibilité.
-   [Liste des outils d'évaluation de l'accessibilité Web](https://www.w3.org/WAI/ER/tools/) — Une liste personnalisable qui vous permet de rechercher différents types d'outils.

### Analyse détaillée {#comprehensive}

Pour une évaluation approfondie :

-   [Méthodologie pour l'évaluation de la conformité à l'accessibilité d'un site Web (WCAG-EM)](https://www.w3.org/WAI/eval/conformance.html) — Fournit une approche structurée pour vous aider à évaluer l'accessibilité de vos sites Web.
-   [L'outil de reporting WCAG-EM](https://www.w3.org/WAI/eval/report-tool/) —
    Il existe des outils en ligne gratuits qui vous aident à créer des rapports d'évaluation selon la procédure WCAG-EM.

Une vue d'ensemble {#scope}
------------------

Il est probable que vous ne puissiez pas aborder tous les problèmes de chaque partie de votre site Web en même temps. Pour déterminer quelles parties vous souhaitez améliorer tout de suite, et lesquelles vous traiterez plus tard, pensez à prioriser :

-   Les **tâches essentielles**, telles que les inscriptions, les recherches, les soumissions ou les processus de vérification. Incluez toutes les étapes nécessaires à la réalisation complète de chaque tâche.
-   Le **contenu essentiel**, tel que le contenu fréquemment consulté, et le contenu s'adressant aux personnes handicapées.
-   Le **contenu signalé**, qui contient des obstacles rencontrés ; par exemple, par le biais de commentaires d'utilisateurs soumis via le formulaire de contact du site Web.
-   Le **contenu en cours de développement**, tel que les parties du site Web en cours de modification, pour éviter la création de nouveaux obstacles.

Au moment de vous faire une idée globale des solutions à apporter, pensez à prioriser les solutions en fonction :

-   Des **solutions à forte incidence**
    -   Elles concernent plusieurs pages Web, par exemple dans les barres de navigation
    -   Elles concernent des pages Web fréquemment consultées, telles que la page d'accueil
    -   Elles sont essentielles à la réalisation de processus, tels que les formulaires de commande
    -   Les problèmes en lien avec les Règles pour l'accessibilité des contenus Web (WCAG) de niveau A
-   Des **solutions qui demandent peu d'efforts**
    -   Elles demandent moins de temps, moins de compétences et sont moins coûteuses
    -   Elles nécessitent moins de temps d'évaluation et de validation

Fixer un niveau d'accessibilité à atteindre {#target}
-----------------------------------

L'objectif généralement accepté en matière d'accessibilité est la dernière version des [Règles pour l'accessibilité des contenus Web (WCAG)]({{ "/standards-guidelines/wcag/" | relative_url }})
de niveau AA. Il peut s'agir du standard déjà spécifié dans votre politique d'entreprise ou d'une obligation légale pour votre site Web.   

Vous pourriez devoir définir une approche par étapes avec différentes dates pour différents niveaux. Par exemple, satisfaire à certains critères de succès particulier des WCAG pour la prochaine publication, et satisfaire à tous [niveau A et niveau AA](https://www.w3.org/WAI/WCAG20/quickref/?currentsidebar=%23col_overview&levels=aaa) les critères de succès pour la publication suivante.

Notez que dans certains cas, il est relativement facile de satisfaire à certains critères de succès de niveau AAA. Par exemple, il est possible de réaliser facilement l'amélioriation d'un texte de lien approprié (2.4.4, niveau A) et la structure des en-têtes de section (2.4.10, niveau AAA) lors de la révision du contenu.

Conseils pour des solutions efficaces {#repair}
-------------------------

-   **Exploitez les différentes compétences au sein de votre équipe** — Bien que de nombreuses tâches seront confiées aux développeurs, d'autres intervenants peuvent contribuer de diverses manières. Par exemple, les designers peuvent sélectionner les meilleures couleurs et les auteurs du contenu peuvent améliorer la formulation des liens, des en-têtes de section et des équivalents textuels. La ressource [Utilisation d'une expertise combinée pour évaluer l'accessibilité Web](https://www.w3.org/WAI/eval/reviewteams.html) pourrait vous être utile.
-   **Communiquez les besoins à votre équipe** — Veillez à ce que toutes les personnes contribuant aux solutions apportées comprennent les fondements de l'accessibilité Web et les besoins spécifiques auxquels ils doivent satisfaire. Distribuez les [ressources importantes](#resources) aux membres concernés au sein de votre équipe.
-   **Validez les solutions le plus tôt possible** — Veillez à ce que chaque solution réponde de manière adéquate aux problèmes soulevés pour éviter d'implémenter des changements qui ne fonctionneront pas dans la pratique. Dans la mesure du possible, il est important d'inclure des personnes handicapées lors de la phase de validation. Les ressources concernant l'[Inclusion des utilisateurs dans les projets Web]({{ "/planning/involving-users/" | relative_url }}) et l'[Inclusion des utilisateurs lors de l'évaluation]({{ "/test-evaluate/involving-users/" | relative_url }}) fournissent des informations supplémentaires.
-   **Optimisez vos outils** — Explorez et configurez les paramètres d'accessibilité des outils d'édition que vous utilisez pour créer du contenu Web, tel que votre système de gestion de contenu (CMS). Les ressources relatives à la
    [sélection des outils d'évaluation]({{ "/test-evaluate/tools/selecting/" | relative_url }}) et la [sélection des outils d'édition](https://www.w3.org/WAI/impl/software) pourrait vous être utile.

À plus long terme : organisation et gestion {#plan}
----------------------------------

Une fois que vous avez réglé les problèmes d'accessibilité les plus critiques au sein de votre projet Web, il est essentiel que vous prévoyiez l'intégration de l'accessibilité tout au long de vos processus de conception et de développement futurs. Le guide pour l'[Organisation et la gestion de l'accessibilité Web]({{ "/planning-and-managing/" | relative_url }}) peut vous aider à aller dans ce sens.
