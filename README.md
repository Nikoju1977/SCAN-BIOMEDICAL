# SCAN Biomédical — expérience de caméra et biométrie

**Catégorie :** prototype d'interface biométrique assistée par IA · Studio Niko Design.

## Ce que fait réellement ce dépôt

La page `index.html` porte le titre **« QUANTUM AI by Niko | Agent Biométrique Clinique »**. Elle présente un parcours pour **activer la caméra**, **démarrer une analyse IA**, afficher des **métriques biométriques** et visualiser une **évolution de la fatigue**.

Il s'agit de l'interface biométrique actuellement présente dans le dépôt, **pas d'un logiciel d'analyse histopathologique de biopsies ou de lames microscopiques**. Les anciens textes suggérant un tel périmètre ne reflétaient pas l'interface examinée.

## Démarrage

Depuis la racine du dépôt :

```sh
python3 -m http.server 8000
```

Ouvrir http://localhost:8000/ ; l'accès caméra exige généralement HTTPS ou localhost et l'accord de l'utilisateur. Les bibliothèques externes et les fonctions d'IA peuvent nécessiter une connexion.

## Confidentialité et limites

**Prototype de démonstration non validé cliniquement.** Les métriques présentées par une caméra ne constituent pas des mesures physiologiques calibrées ni un diagnostic de fatigue ou de maladie. Les données vidéo ou images personnelles nécessitent une revue des flux réseau avant utilisation. Ne pas utiliser pour une décision de santé ou de sécurité.

Ce README décrit la structure observable du projet ; il ne certifie **ni les résultats de l'IA, ni la sécurité, ni le fonctionnement sur appareils réels**.

[Voir le catalogue détaillé des projets](https://github.com/Nikoju1977/Nikoju1977/blob/main/PROJECTS.md)
