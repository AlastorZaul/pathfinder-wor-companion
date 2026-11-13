# WOTR Companions

Guides de build pour les compagnons de **Pathfinder: Wrath of the Righteous**, en français.

Site en ligne : https://alastorzaul.github.io/pathfinder-wor-companion/

## Contenu

### Compagnons
- **Vue d'ensemble** : les compagnons de la campagne principale, des chemins mythiques et des DLC, d'après la page Companions du wiki Fextralife.
- **Ember**, **Delamere**, **Arueshalae**, **Woljif Jefto**, **Sosiel** : build détaillé, avec ordre de montée de niveau, dons, sorts, équipement, points forts et points faibles.
- **Daeran**, **Regill**, **Greybor** : build résumé. Les niveaux ne sont pas précisés dans la source.

### Builds
- **Builds par classe** : pages de build du wiki (Eldritch Knight, Inquisitor, Magus, Monk, Rogue, Warpriest, Bloodrager, Arcanist), builds d'archers et guides mis en avant.
- **Builds maison** : builds inventés à partir des guides du wiki, non testés en jeu. Première version : un Cavalier tank pour une première partie en Normal, avec les dons encore à choisir.

## Structure du dépôt

```
index.html          Accueil
companions.html     Vue d'ensemble des compagnons
builds.html         Builds par classe
<compagnon>.html    Une page par compagnon détaillé
style.css           Style commun à toutes les pages
theme.js            Bouton clair / sombre et menu mobile
```

Chaque page reprend la même barre de navigation. Quand tu ajoutes une page, pense à l'ajouter dans la barre de navigation de toutes les autres, et dans l'accueil.

## Compagnons à compléter

- Camellia, Seelah et Nenio n'ont qu'une description de classe, sans build détaillé.
- Finnean (arme parlante), les compagnons du chemin Lich (sauf Delamere), Aivu, Trever et les compagnons des DLC n'ont pas encore de page.
- Lann et Wenduag sont exclusifs : une partie n'en prend qu'un des deux.

## Déploiement

Le site est publié par GitHub Pages directement depuis la branche `main` (racine du dépôt). Chaque push sur `main` relance le déploiement natif, sans workflow maison.

## Sources et limites

Les données viennent de :
- **Wiki Fextralife** : pages Companions, Companion Builds et Builds, ainsi que les guides de build par compagnon.
- **Wiki Kingmaker** (tableaux des compagnons, pour les classes et les races).
- **Game-Rack** : classement des compagnons du 19 juin 2026 (patch 2.7.0x), niveaux S et A.

Limites à garder en tête :
- Plusieurs guides Fextralife datent de septembre 2021 et ne correspondent peut-être plus à la version actuelle du jeu. Le classement Game-Rack est plus récent, mais ses niveaux reposent sur des évaluations communautaires.
- Pour Ember, les deux sources ne s'accordent pas sur le multiclassage. Le point reste à trancher en jeu.
- Les niveaux et les ordres de dons ne sont pas tous vérifiés en jeu.
- Les pages de classe du wiki ne donnent pas de build précis, seulement une entrée par classe.
- Le guide de Woljif Jefto cite trois attributs dans son en-tête pour un texte qui en utilise deux ; le point est à vérifier.

Chaque page indique ses sources en bas.

## Avertissement

Guide communautaire non officiel. Aucun lien avec Owlcat Games ni avec Paizo. Pathfinder: Wrath of the Righteous est une marque de ses détenteurs respectifs.
