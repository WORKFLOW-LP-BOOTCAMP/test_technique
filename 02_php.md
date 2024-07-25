# Tests techniques

## 1. Quel sera le résultat du script suivant ?

```php
<?php
$namespace = 'MyApp';
function test() {
    $namespace = 'TestApp';
    echo $namespace;
}
test();
echo $namespace;
?>
```

☐ A. TestAppMyApp  
☐ B. MyAppTestApp  
☐ C. MyAppMyApp  
☐ D. TestAppTestApp




## 2. Que va afficher ce script ?

```php
<?php
include 'file.php'; // Suppose que file.php n'existe pas
echo 'Hello, World!';
?>
```

☐ A. Hello, World!  
☐ B. Warning et Hello, World!  
☐ C. Fatal error  
☐ D. Rien du tout




## 3. Que va afficher ce script ?

```php
<?php
try {
    throw new Exception('Erreur !');
} catch (Exception $e) {
    echo 'Exception capturée : ' . $e->getMessage();
} finally {
    echo ' Bloc finally exécuté.';
}
?>
```

☐ A. Exception capturée : Erreur ! Bloc finally exécuté.  
☐ B. Exception capturée : Erreur !  
☐ C. Bloc finally exécuté.  
☐ D. Erreur ! Bloc finally exécuté.




## 4. Que va afficher ce script ?

```php
<?php
if ($_SERVER['REQUEST_METHOD'] == 'POST') {
    echo $_POST['name'];
} else {
    echo $_GET['name'];
}
?>
```

Assume that the script is accessed via URL: `http://example.com/script.php?name=John`

☐ A. Affiche toujours le contenu de $_GET['name']  
☐ B. Affiche le contenu de $_GET['name'] si la requête est GET, sinon affiche le contenu de $_POST['name']  
☐ C. Affiche uniquement le contenu de $_POST['name']  
☐ D. Affiche uniquement le contenu de $_GET['name']



## 5. Que va afficher ce script ?

```php
<?php
trait HelloWorld {
    public function sayHello() {
        echo 'Hello, World!';
    }
}

class MyClass {
    use HelloWorld;
}

$obj = new MyClass();
$obj->sayHello();
?>
```

☐ A. Hello, World!  
☐ B. Erreur fatale  
☐ C. Hello  
☐ D. Rien du tout


## 6. Que va afficher ce script ?

```php
<?php
declare(strict_types=1);

function add(int $a, int $b): int {
    return $a + $b;
}

echo add(5, '10');
?>
```

☐ A. 15  
☐ B. 510  
☐ C. TypeError  
☐ D. 10


## 7. Que va afficher ce script ?

```php
<?php
function square($n) {
    return $n * $n;
}

$array = [1, 2, 3, 4];
$result = array_map('square', $array);
print_r($result);
?>
```

☐ A. Array ( [0] => 1 [1] => 4 [2] => 9 [3] => 16 )  
☐ B. Array ( [0] => 1 [1] => 2 [2] => 3 [3] => 4 )  
☐ C. Array ( [0] => 2 [1] => 4 [2] => 6 [3] => 8 )  
☐ D. Rien du tout


## 8. Que va afficher ce script ?

```php
<?php
interface MyInterface {
    public function doSomething();
}

abstract class MyAbstractClass {
    abstract public function doSomethingElse();
}

class MyClass extends MyAbstractClass implements MyInterface {
    public function doSomething() {
        echo 'Doing something';
    }

    public function doSomethingElse() {
        echo 'Doing something else';
    }
}

$obj = new MyClass();
$obj->doSomething();
$obj->doSomethingElse();
?>
```

☐ A. Doing somethingDoing something else  
☐ B. Doing something  
☐ C. Doing something else  
☐ D. Erreur fatale


## 9. Que va afficher ce script ?

```php
<?php
try {
    $pdo = new PDO('mysql:host=invalid_host;dbname=database', 'username', 'password');
    $pdo->setAttribute(PDO::ATTR_ERRMODE, PDO::ERRMODE_EXCEPTION);
    echo 'Connection établie';
} catch (PDOException $e) {
    echo 'Connexion échouée : ' . $e->getMessage();
}
?>
```

☐ A. Connection établie  
☐ B. Connexion échouée : SQLSTATE[HY000] [2002] No such file or directory  
☐ C. Erreur fatale  
☐ D. Rien du tout


## 10. Que va afficher ce script ?

```php
<?php
$a = '5';
$b = 5;

if ($a == $b) {
    echo 'Egalité';
}

if ($a === $b) {
    echo 'Identité';
}
?>
```

☐ A. Egalité  
☐ B. EgalitéIdentité  
☐ C. Identité  
☐ D. Rien du tout

