<!-- ELUCENIA technical documentation · criterios-acr-eular-artrite-reumatoide · fr · no clinical/professional/rights approval -->

# Critères ACR/EULAR 2010 de polyarthrite rhumatoïde

[conditions, sources et autorisations](https://elucenia.org/fr/outils/criterios-acr-eular-artrite-reumatoide)

## Mode d’emploi

Utilisez l’outil sur le portail ou ouvrez index.html via un serveur HTTP local. Sélectionnez la langue, remplissez les champs et lancez le calcul.

## Données d’entrée et unités

### Atteinte articulaire (gonflement ou douleur)

`artic`

- `0` — 1 grosse articulation
- `1` — 2 à 10 grosses articulations
- `2` — 1 à 3 petites articulations (avec ou sans grosses articulations)
- `3` — 4 à 10 petites articulations (avec ou sans grosses articulations)
- `5` — \> 10 articulations (dont au moins 1 petite)

### Sérologie (facteur rhumatoïde et anti-CCP)

`soro`

- `0` — Tous deux négatifs
- `2` — Au moins un titre faiblement positif (jusqu’à 3× la limite supérieure)
- `3` — Au moins un titre fortement positif (\> 3× la limite supérieure)

### Marqueurs de phase aiguë (CRP et VS)

`fase`

- `0` — Les deux normales
- `1` — CRP ou VS anormale

### Durée des symptômes

`duracao`

- `0` — \< 6 semaines
- `1` — ≥ 6 semaines

## Édition de la méthode

ACR/EULAR 2010 : 4 domaines, total 0–10, seuil≥6 ; contexte et exclusions requis

## Formule documentée

Somme de quatre domaines (maximum 10) : articulations (0–5), sérologie (0–3), phase aiguë (0–1), durée des symptômes (0–1). ≥ 6 = polyarthrite rhumatoïde définie.

Grandes articulations : épaules, coudes, hanches, genoux, chevilles. Petites : MCP, IPP, MTP 2e–5e, IP du pouce et poignets.

## Limites et population

La classification ACR/EULAR 2010 exige une synovite confirmée dans au moins une articulation et l’absence d’un diagnostic alternatif l’expliquant mieux, avant d’appliquer le seuil ≥6/10. Elle a été développée pour une synovite inflammatoire indifférenciée de présentation récente. Le score seul, sans ces conditions, ne reproduit pas les critères de classification.

## Références

- [Aletaha D et al. 2010 Rheumatoid arthritis classification criteria: an American College of Rheumatology/European League Against Rheumatism collaborative initiative. Arthritis Rheum, 2010.](https://doi.org/10.1002/art.27584)

## Reproduire les tests techniques

Exécutez node test.cjs dans le répertoire racine de ce dépôt pour reproduire les cas synthétiques enregistrés. Les données d’entrée, les résultats attendus et les tolérances d’origine sont conservés. Les tests techniques ne constituent pas une validation clinique.

```sh
node test.cjs
```

tool.json contient les sources, l’édition et le périmètre de la revue. examples.json conserve les données d’entrée et les résultats attendus des cas synthétiques ; results.json consigne les résultats obtenus.

[Fiche et références](../tool.json) · [Code JavaScript](../calculator.js) · [Cas de référence](../examples.json) · [results.json](../results.json)

## Revue et conditions d’utilisation

Aucune révision clinique indépendante n’a été effectuée.

Cette interface est une traduction réalisée par nos soins, et non une édition officielle ou certifiée. La revue clinique indépendante, la révision linguistique professionnelle et l’autorisation des droits sur les instruments n’ont pas été réalisées.

Résultat de la formule ou de la classification. L’interprétation, la conduite et l’applicabilité dépendent de l’évaluation professionnelle et de la source sélectionnée.

## Licence et attribution

Apache-2.0 s’applique uniquement au code d’ELUCENIA. Les droits sur les instruments, publications, traductions et données restent ceux de leurs titulaires respectifs. Conservez LICENSE et NOTICE.

ELUCENIA · Felipe Guedes · Copyright © 2026

## Résultats documentés

Les informations ci-dessous conservent les sorties de la méthode pour des exemples synthétiques. Elles ne constituent pas une validation clinique indépendante.

### 1

Classe comme polyarthrite rhumatoïde définie (≥ 6 points)


### 2

Classe comme polyarthrite rhumatoïde définie (≥ 6 points)


### 3

Ne remplit pas les critères de classification (< 6 points)

N’exclut pas la polyarthrite rhumatoïde : réévaluer au fil du temps.

