## TP 1 - Data Visualization - Bullet Plot

### Définition 

Utilisés typiquement pour afficher les données de performance, les Bullet Graphs fonctionnent comme un Bar Chart, mais sont accompagnés d'éléments visuels supplémentaires à mettre en contexte. A l'origine, les Bullet Graphs ont été développés par Stephen Few comme une alternative aux jauges et aux compteurs. Cela s'explique par le fait qu'ils n'affichaient souvent pas assez d'informations, et qu'ils étaient moins efficaces en termes d'espace.

<p align="center">
  <img src=images/bullet_plot_def.png>
</p>

Le graph est constitué des éléments suivant : 
<ul>
	<li> <strong>Text label</strong>: Indique le type de données représentées.</li>
	<li><strong>Quantitative scale</strong>: représente l'échelle de mesure.</li>
	<li><strong>The Featured measure</strong>: La donnée principale</li>
	<li><strong>The Comparative measure</strong>: utilisé comme marqueur cible pour être comparé avec la barre principale</li>
	<li><strong>Qualitative ranges</strong>: espaces colorées segmentées derrière la mesure principale sont utilisés pour afficher les notes qualitatives. Chaque nuance de couleur (les trois nuances de gris dans l'exemple ci-dessus) est utilisée pour attribuer une note de performance. Ainsi par exemple, faible, moyen et fort. En utilisant les Bullet Graphs, il est idéal de maintenir le nombre maximum de plages à cinq</li>
</ul>

### Exemples d'utilisation:

il n'existe pas d'exemples historiques ou très populaires qui montrent l'utilisation des Bullet Graph, mais on peut citer l'exemple qui figure dans la description originale de ses graphs par Stephen Phew:  

<p align="center">
  <img src=images/bullet_plot_example.png />
</p>

### Commentaires

Le bullet Plot est certainement meilleur que les jauges ou simple bar chart, mais on peut y ajouter: 
<ul>
  <li>Normaliser les valeurs cibles pour faciliter l'évaluation visuelle</li>
  <li>Mettre en évidence les écarts afin de comprendre le graphique plus rapidement</li>
</ul>

### 3) Conclusion

Les bullets Graphs sont un bon outil pour indiquer la valeur d'une caractéristique, et de la comparer avec une valeur critique. En plus de la possibilité d'annoter et montrer d'autre traits (de performance) sur le même graphique.

### 4) Sources

https://www.perceptualedge.com/articles/misc/Bullet_Graph_Design_Spec.pdf

https://www.fusioncharts.com/chart-primers/bullet-graph/