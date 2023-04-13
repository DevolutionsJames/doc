---
title: Survol
---
Utiliser ***Fichier - Exporter*** pour exporter des entrées à partir de {{ fr.RDM }} . Voici une liste d&apos;options d&apos;exportation:  

* Exporter tout (.rdm) 
* Exporter la sélection (.rdm) 
* Exporter l&apos;entrée en fichier Remote Desktop (.rdp) 
* Exportation spéciale (Toutes les entrées .csv, .html, .xml et toutes les sélections .csv, .html, .xml) 

{% snippet icon.badgeInfo %}
La fonction d&apos;exportation n&apos;est active que si la [Permission](/fr/rdm/mac/commands/administration/user-management/permissions/) d&apos;importation a été activée dans le compte d&apos;utilisateur 
{% endsnippet %}
 
{% snippet icon.badgeInfo %}
Le seul format approprié pour réimporter les entrées dans {{ fr.RDM }} est le format .rdm. 
{% endsnippet %}
 
## Paramètres 

![Fichier - Exporter](/img/fr/rdm/mac/clip4028.png) 

{% snippet icon.badgeInfo %}
Lorsque vous utilisez une [Source de données avancée](/fr/rdm/mac/data-sources/data-sources-types/advanced-data-sources/) , les capacités d&apos;exportation peuvent être désactivées via des politiques de sécurité au niveau de la source de données (personne ne peut exporter) ou au niveau de l&apos;utilisateur (certains utilisateurs ne peuvent pas exporter). Voir gestion des [Groupes de sécurité (Ancien)](/fr/rdm/mac/commands/administration/security-group-management/) pour plus d&apos;informations. 
{% endsnippet %}
 
### Exporter tout (.rdm) 

Exporter toutes les entrées dans un fichier .rdm qui peut être importé dans n&apos;importe quelle source de données {{ fr.RDM }} . Vous pouvez également inclure les identifiants dans ce format d&apos;exportation et sécuriser votre fichier avec une clé maîtresse. 

{% snippet icon.badgeWarning %} 
Par défaut, les identifiants ne sont PAS inclus. Il est essentiel de cocher l&apos;option Inclure identifiants afin que les données exportées les incluent. 
{% endsnippet %}
 
![Fichier - Exporter](/img/fr/rdm/mac/clip4028.png) 

### Exporter la Sélection (.rdm) 

Exporter la session sélectionnée dans un fichier .rdm qui peut être importé dans n&apos;importe quelle source de données {{ fr.RDM }} . Vous pouvez également inclure les identifiants dans ce format d&apos;exportation et sécuriser votre fichier avec une clé maîtresse. 

### Exporter l&apos;entrée en fichier Remote Desktop (.rdp) 

Exporter l&apos;entrée sélectionnée dans un fichier .rdp pour l&apos;utiliser facilement en dehors de {{ fr.RDM }} . 

### Exportation spéciale (.csv) 

Exporter les entrées à l&apos;aide du fichier au format .csv. Pour des raisons de sécurité, le fichier .csv sera contenu dans un fichier zip chiffré par mot de passe. Ce type de sécurité peut être piraté à l&apos;aide d&apos;attaques par force brute, il ne doit être utilisé que lorsque le fichier zip est sous votre contrôle exclusif. 

{% snippet icon.badgeInfo %}
Veuillez noter que les colonnes csv varient en fonction des types d&apos;entrées exportés. Cela en fait le mauvais format si jamais vous souhaitez réimporter les données dans {{ fr.RDM }} . Utilisez-le uniquement pour migrer vers un autre système. 
{% endsnippet %}
 
### Exportation spéciale (.html) 

Exporter toutes les entrées d&apos;un AES-256 pour crypter le fichier HTML autonome. 

### Exportation spéciale (.xml) 

Parce qu&apos;il a semé la confusion dans notre base d&apos;utilisateurs, ce format d&apos;exportation a été converti pour effectuer exactement la même exportation que &quot;Exporter toutes les entrées&quot; mais définit l&apos;extension de fichier sur .xml à la place. 
