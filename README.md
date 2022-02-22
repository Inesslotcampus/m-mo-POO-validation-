# m-mo-POO-validation-

Mémo de poo

# POO (programmation objet orienté)

__L'objet se trouve dans une variable, peut stocker des valeurs, peut demander de faire des actions.__

    
__La classe permet de donner le nom de l'élément que l'ont veut manipuler.
La classe est est une définition qui contient le nom des propriétés et les méthodes.__

- keyword (class) = classe

- keyword (public) = définit l'accessibilité de la propriété.

## Propriétés

__Ce sont les variables internes où on stocke des valeurs.__

## Attributs

__Caractéristiques d'une classe. Définie par var,  ou rien__
- var $nom_var
- $nom_var
## Méthode
 __ensemble de fonctions essentielles et internes à la classe que chaques objet va contenir.__

 - function namefunction(){} = créer des méthodes 

__ Constructor méthod est appellé automatiquement quand un objet est instancier.  __
 - __construct() = constructor method



## Instancier/instanciating

__Le fait de créer un objet à partir d'une classe.__
- $nom_dune_variable = new  nom_de_la_classe () => __instancier la classe__ 

### Instance
__Créer une classe à partir d'une classe grace à (new).__

- $this => Permet de désigner une instance. variable qui correspond à l'objet.
- $this-> = invoquer attribut de la classe

## Getter et setter 
__Objet methods qui permet de controler l'accès à certaines variables et propriétés dans les classes .__
## Getter


__Obtient la valeur d'un attribut en dehors de la classe lorsqu'il est private ou protected. Utilise un return et peut afficher un attribut privé avec echo;__
- Ex:class Pet {

  private $name;

  function setName($name) {
    $this->name = $name;

  }


## Setter
__Permet de modifier une valeur d'un attribut privé ou protected.__



## Héritage(inheritance)

__L'inhérence permet de réutiliser une classe dans ton code sans le duppliquer. Il y a une classe parente avec des propriétés et des méthodes et une classe enfant qui peut utiliser le code de la classe parent.__

- class nom_de_la_classe_enfant extends nom_de_la_classe_parent{

}



## Surcharger(overriding)

__Utilisation d'une méthode d'une classe mère dans une classe fille.
Il faut redéclarer la classe mère avec le même nombre de caractères.__

__Impossible de récuperer les éléments privés (private).__

__Possible après les élément protected et public.__

