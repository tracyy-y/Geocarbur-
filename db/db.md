# Database
Conception et implémentation de la base de données.

## Conception 
Nous allons utiliser la méthode MERISE à savoir :
- Modèle conceptuel;
- Modèle logique ;
- Modèle physique.

### Modèle conceptuel
Entité 1 : Station
Entité 2 : Ville 
Relation : n Station -1 ville (n,1)

Propriétés station: nom, opérateur, shop ,adresse, géometrie .
Propriétés ville: nom, superficie , population, pays.
 
## ImplémentationINSERT INTO villes(id,nom,superficie,population,pays,created_at)
VALUES (1,'Abidjan',2119,6321017,'cote d"ivoire','2025-03-19')