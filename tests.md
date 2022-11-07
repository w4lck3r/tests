# Plan des tests 
### Module méthodologie des tests 

#### Groupe :
* SALMI Badr-eddine : badreddine.salmi@epsi.fr
* KOURIAT Mohammed : 
----

## Game plan :
* User : 
    *  Un user peut avoir juste un seul compte
    * compte : avec un e-mail , ou connexion (facebook , google) .

    * Un user possède des pokémons et des objets



* Game : 
    * Un user peut voir le profile (les objets , les pokémons) d'un autre user.
    
    * Un user peut [se battre] avec un autre , le gangant prend (un objet).

    * Chaque jours l'user reçoit 5 randoms pokémons 
        * Il doit remplacer 1 de son equipe : mais pas le plus recent.

    * Classement : 
        * victoire :
            * (+) 10 pts + nb(pokémons invaincu) . 
        * defaite : 
            * (-) 10 pts - nb(pokémons invaincu) .

    * Un user reçoit chaque jour 1 objet

    * Un user peut ganger jusqu'a 3 objet max par jour
------
##  DATA :

* user : 
    * pseudo
    * email (email of facebook or gmail connected)
    * nb points
    * pokémons gotten
    * rank
    * nb objects

* rank : 
    * pseudo
    * rank

* pokémon : 
    * pseudo
    * power
    * camp

* object :
    * name
    * price ?

------
## Ressources impliquées :

##### Les besoins pour effectuer les divers activités de tests :
* users existance :
    * On est besoin de deux users au moins connectés : cas des fights .
    * Ou juste un user pour collecté ses recompenses : 
        * user pick a new poké :
            * user pick un nouveau pokémon pour son équipe .
            * user  pick le pokémon qui va quitter le clan .
        * user collect an object.
* 

* user fight each other :
    * 2 user obliger .
    * les pokémons de chaque user . (power of each one)
    * objects de chaque user .  
    * rank ???

* user win : 
    * (+) 10 pts + nb(pokémons invaincu) .
    * objectGotten =  random(object) 
<!-- * other user (looser) :
    * (-) 10 pts - nb(pokémons invaincu) .
    * User.objects.del(objectGotten) . -->

* est ce que l'user peut ganger un objet ?
    * ssl l'user a ganger le jour < 3 objet .

----  
##### 3 KPIs permettant de suivre l'avancée des tests :
* Covered Requirements :
This KPI is used to measure the mapping of test cases to requirements. A test manager is required to make sure that all the requirements have corresponding test cases and the action should be taken on any requirements that could not be mapped to any test case and vice versa. The goal is to keep the mapping of requirements to test cases to 100%.

* Code Coverage :
This KPI is used by testers to ascertain the percentage of code they are covering with their automated tests.

* Quality Ratio: 
Based on the passed or failed rates of all the tests executed by the software testers, the quality ratio, is used as both a software testing metrics as well as a KPI. The formula used for this is: Quality Ratio: (Successful Tests Cases / Total Number of Test Cases) x 100

##### Budget :
* Resources humaines :
    * Une équipe qui contibuer dans le projet : 
        * devs : 
        * designers :
        * 
        * 


* Charges techniques : 
    * Des appereils :
        * ordinateurs 
        * connexion 
        * 
        *
        *
        *

* Cas des tests : 
