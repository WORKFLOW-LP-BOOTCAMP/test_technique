# Tests techniques

## 1. Qu'est-ce que le namespace en PHP et pourquoi est-il utilisé ?

☐ A. Un namespace est une méthode pour définir des variables globales  
☐ B. Un namespace est utilisé pour inclure des fichiers externes  
☐ C. Un namespace est une manière d'encapsuler des classes, fonctions et constantes afin d'éviter les collisions de noms  
☐ D. Un namespace est une fonctionnalité pour gérer les sessions


## 2. Quelle est la différence entre `include`, `require`, `include_once` et `require_once` ?

☐ A. `include` et `require` incluent des fichiers une seule fois, `include_once` et `require_once` incluent des fichiers plusieurs fois  
☐ B. `include` et `include_once` incluent des fichiers, `require` et `require_once` exécutent des fichiers  
☐ C. `include` continue l'exécution du script en cas d'erreur, `require` arrête le script, `include_once` et `require_once` incluent des fichiers une seule fois  
☐ D. `include` et `require` exécutent des scripts PHP, `include_once` et `require_once` sont utilisés pour les scripts HTML


## 3. Comment gérer les exceptions en PHP ?

☐ A. Utiliser des déclarations if-else  
☐ B. Utiliser des boucles while  
☐ C. Utiliser les blocs `try`, `catch` et éventuellement `finally`  
☐ D. Utiliser la fonction `handle_exception()`


## 4. Quelle est la différence entre les variables superglobales `$_GET` et `$_POST` ?

☐ A. `$_GET` est utilisée pour récupérer les données envoyées via la méthode HTTP POST, `$_POST` via la méthode HTTP GET  
☐ B. `$_GET` récupère les données envoyées via la méthode HTTP GET, `$_POST` via la méthode HTTP POST  
☐ C. `$_GET` et `$_POST` sont interchangeables  
☐ D. `$_GET` est utilisée pour les requêtes asynchrones, `$_POST` pour les requêtes synchrones


## 5. Expliquez le concept de traits en PHP.

☐ A. Les traits sont une manière d'étendre une classe avec des méthodes statiques  
☐ B. Les traits sont un mécanisme de réutilisation de code permettant d'encapsuler des méthodes réutilisables sans utiliser l'héritage multiple  
☐ C. Les traits sont une fonctionnalité pour gérer les interfaces utilisateur  
☐ D. Les traits sont une méthode pour définir des constantes globales


## 6. Qu'est-ce que le typage strict en PHP et comment l'activer ?

☐ A. Le typage strict force les fonctions à n'accepter que les types de données définis dans leurs déclarations de type, et peut être activé avec `declare(strict_types=1);`  
☐ B. Le typage strict permet d'utiliser des types dynamiques pour les variables, et peut être activé avec `use(strict_types=1);`  
☐ C. Le typage strict permet d'utiliser des types de données flexibles, et peut être activé avec `declare(flexible_types=1);`  
☐ D. Le typage strict est une fonctionnalité pour les variables globales, activée avec `global(strict_types=1);`


## 7. Comment fonctionne la fonction `array_map` ?

☐ A. `array_map` combine deux tableaux en un seul  
☐ B. `array_map` applique une fonction à chaque élément d'un ou plusieurs tableaux et retourne un tableau contenant les nouveaux éléments  
☐ C. `array_map` filtre les éléments d'un tableau selon une condition  
☐ D. `array_map` trie les éléments d'un tableau


## 8. Quelle est la différence entre une interface et une classe abstraite en PHP ?

☐ A. Une interface peut contenir des méthodes avec implémentation, une classe abstraite ne peut contenir que des méthodes sans implémentation  
☐ B. Une interface ne contient que des déclarations de méthodes publiques sans implémentation, tandis qu'une classe abstraite peut contenir des méthodes avec ou sans implémentation  
☐ C. Une classe abstraite est utilisée pour définir des constantes, une interface pour définir des variables  
☐ D. Il n'y a pas de différence, les deux sont interchangeables


## 9. Comment établir une connexion à une base de données MySQL en utilisant PDO ?

☐ A. `new PDO('mysql:host=hostname;dbname=database', 'username', 'password');`  
☐ B. `mysql_connect('hostname', 'username', 'password', 'database');`  
☐ C. `mysqli_connect('hostname', 'username', 'password', 'database');`  
☐ D. `connect_pdo('mysql', 'hostname', 'database', 'username', 'password');`


## 10. Expliquez la différence entre les opérateurs `==` et `===` en PHP.

☐ A. `==` compare les valeurs sans conversion de type, `===` compare les valeurs après conversion de type  
☐ B. `==` compare les valeurs après conversion de type, `===` compare les valeurs et les types sans conversion  
☐ C. `==` est utilisé pour les nombres, `===` pour les chaînes de caractères  
☐ D. `==` compare les chaînes de caractères, `===` compare les objets
