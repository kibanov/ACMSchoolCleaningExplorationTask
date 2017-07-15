# Homework for course of Prof. Ferreira
The repository consists of two files:
* ```parking-violations-small.csv``` Cleaned data of New York City parking violations
* ```trees.ipynb``` iPython Notebook for analysis of dependnece of New York trees on shadows

## Findings about trees and sun (shadows) amount in New York City
Those findings were made using that notebook.

### Can you find a correlation between the amount of sun and tree health?
* There is no correlation between tree health and sun (shadow) amount on the item level
* However, if using aggregated view, there is a negative correlation between tree health and sun amount (e.g. Pearson Correlation for sun amount in winter = -0.47, alpha = 0.01)

### Is tree height associated with health? Do taller trees get more sun?
* Tree height is associated with health in terms of Pearson Correlation (0.64, alpha = 0.01).

### How prevalent are species that tolerate shade? Are trees of these species healthier? Have they been planted in suitable places, where they get plenty of shade?
* Only 64% of trees of American linden (Tilla americana) have good health. 80% of american elms have good health. 70.6% of silver linden have good health. Those three arts of trees tolerate shade well. However, many other arts have better values in terms of numbers of healthy trees (e.g., honeylocust with over 83% of healthy trees, crab apple with almost 85% of healthy species, and golden golden raintree	with 88% of healthy trees). So, it is not possible to say that the trees of those three arts have a specially high amount of healthy species.