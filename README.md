# unit_testing_exercise

Projet Maven d'exemple pour l'exercice 2a de la formation Jenkins (Digital Learning Hub).

- Classe testée : `src/main/java/com/dlh/calcul/MultiplyClass.java`
- Classe de tests : `src/test/java/com/dlh/calcul/MathClass.java` (6 tests JUnit 5)

Prérequis : Java 17 ou plus, Maven 3.6 ou plus.

```
mvn clean test -Dtest=MathClass
```

Rapports JUnit : `target/surefire-reports/*.xml`
