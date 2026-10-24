# Calculator : JUnit 5 et AssertJ

TP1 de tests unitaires en Java avec JUnit 5 et AssertJ.

## Objectifs

- Écrire des tests unitaires structurés avec le pattern Arrange / Act / Assert
- Maîtriser le cycle de vie des tests : `@BeforeEach`, `@AfterEach`, `@BeforeAll`, `@AfterAll`
- Utiliser des tests paramétrés : `@ParameterizedTest`, `@ValueSource`, `@CsvSource`
- Contrôler le temps d'exécution avec `@Timeout`
- Améliorer la lisibilité des assertions avec AssertJ
- Appliquer la démarche TDD (Rouge / Vert) sur la méthode `digitsSet`

## Technologies

- Java 17
- Maven
- JUnit 5 (5.10.2)
- AssertJ (3.24.2)

## Structure du projet

```
src
├── main/java/com/openclassrooms/testing
│   └── Calculator.java
└── test/java/com/openclassrooms/testing
    └── CalculatorTest.java
```

## Lancer les tests

```
mvn test
```

Ou dans IntelliJ : clic droit sur `CalculatorTest` > Run 'CalculatorTest'.

## Résultat

13 tests exécutés, 13 réussis.

## Auteure

Marwa Laamarti, élève ingénieure en Génie Informatique, ENSA Fès.
