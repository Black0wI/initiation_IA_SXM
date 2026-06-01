# Fiche pratique - Audit SEO / GRO d’un site public avec Codex

## Prompt optimisé

```text
Travaille comme un consultant SEO senior spécialisé en SEO technique, contenu, UX, performance et GRO/GEO, c’est-à-dire l’optimisation de la visibilité dans les moteurs de recherche classiques et les moteurs de réponse IA.

Objectif : réaliser un audit SEO / GRO poussé du site public suivant :
[URL_DU_SITE]

Contraintes :
- Analyse uniquement les pages publiques accessibles sans connexion.
- Ne remplis aucun formulaire.
- Ne contourne aucune restriction.
- Respecte robots.txt et limite le crawl à un volume raisonnable.
- Ne fais aucune action destructive.
- Si une information ne peut pas être vérifiée, indique-le clairement.

Étape 1 - Cadrage
Identifie :
- domaine analysé ;
- pages explorées ;
- sitemap.xml disponible ou non ;
- robots.txt disponible ou non ;
- type de site : vitrine, e-commerce, SaaS, média, institutionnel, blog, etc. ;
- public cible probable ;
- objectifs SEO probables.

Étape 2 - Audit technique SEO
Analyse :
- indexabilité ;
- balises title ;
- meta descriptions ;
- balises H1/H2/H3 ;
- canonical ;
- hreflang si applicable ;
- structure des URL ;
- maillage interne ;
- profondeur des pages ;
- pages orphelines visibles ;
- erreurs 404 ou redirections ;
- sitemap ;
- robots.txt ;
- données structurées Schema.org ;
- compatibilité mobile ;
- performance perçue ;
- Core Web Vitals si mesurables ;
- poids des pages ;
- images trop lourdes ;
- attributs alt ;
- sécurité HTTPS ;
- duplication technique.

Étape 3 - Audit contenu
Évalue :
- clarté de la proposition de valeur ;
- intention de recherche ciblée ;
- couverture sémantique ;
- qualité des titres ;
- profondeur du contenu ;
- lisibilité ;
- expertise, expérience, autorité et fiabilité ;
- contenu dupliqué ou faible ;
- pages à fort potentiel ;
- pages à fusionner, enrichir ou supprimer ;
- opportunités de nouveaux contenus.

Étape 4 - Audit GRO / GEO
Analyse la capacité du site à être compris, cité ou repris par les IA génératives :
- clarté des réponses aux questions fréquentes ;
- présence de définitions explicites ;
- structure en paragraphes courts ;
- données factuelles facilement extractibles ;
- FAQ ;
- tableaux comparatifs ;
- listes d’étapes ;
- pages piliers ;
- preuves, sources, chiffres, dates ;
- mentions d’expertise ;
- pages auteur ou entreprise ;
- cohérence des entités : marque, services, lieux, personnes, offres ;
- facilité pour une IA de résumer le site correctement.

Identifie les contenus à créer ou modifier pour améliorer la visibilité dans ChatGPT, Perplexity, Gemini, Copilot et moteurs de réponse similaires.

Étape 5 - Analyse concurrentielle légère
Si possible, identifie 3 à 5 concurrents ou sites comparables.
Compare :
- positionnement ;
- structure de contenu ;
- profondeur éditoriale ;
- clarté de l’offre ;
- signaux de confiance ;
- opportunités différenciantes.

Étape 6 - Priorisation
Classe les recommandations avec :
- priorité : haute, moyenne, basse ;
- impact SEO estimé ;
- impact GRO/GEO estimé ;
- effort de mise en œuvre ;
- risque si non traité ;
- page concernée ;
- action concrète.

Étape 7 - Livrables attendus
Produis un rapport structuré avec :

1. Résumé exécutif.
2. Score global SEO / GRO sur 100.
3. Points forts.
4. Problèmes critiques.
5. Audit technique.
6. Audit contenu.
7. Audit GRO / GEO.
8. Analyse des opportunités.
9. Tableau des recommandations priorisées.
10. Plan d’action sur 30 jours.
11. Plan d’action sur 90 jours.
12. Quick wins.
13. Annexes avec pages analysées.

Format du tableau principal :
- problème ;
- page concernée ;
- preuve ou observation ;
- impact ;
- priorité ;
- recommandation ;
- effort estimé ;
- responsable suggéré.

Important :
- Sois concret.
- Ne donne pas de conseils génériques.
- Appuie chaque recommandation sur une observation.
- Si tu fais une hypothèse, indique qu’il s’agit d’une hypothèse.
- Termine par les 10 actions les plus rentables à lancer en premier.

Génère le rapport final en Markdown puis en PDF dans un dossier output/.
Inclue un tableau de priorisation lisible et une synthèse exécutive en première page.
Ajoute si possible des captures ou schémas simples pour illustrer les problèmes critiques.
Vérifie que le PDF existe et produis un court rapport de contrôle final.
```
