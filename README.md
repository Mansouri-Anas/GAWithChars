# Utilisation de l'algorithme génétique avec un système multiagent 🌱

## Objectif

Notre objectif est de créer une population de chaînes de caractères, représentées par des chromosomes, qui évoluent au fil des générations. Nous espérons obtenir une population dans laquelle une des chaînes sera identique à la cible recherchée, "BONJOUR BDCC bonsoir bdcc".

## Configuration

La classe `GAUtils` contient les paramètres clés pour notre algorithme génétique :

```java
public class GAUtils {

    public static final String TARGET_PHRASE = "BONJOUR BDCC bonsoir bdcc";

    public static final int CHROMOSOME_SIZE = 25;

    public static final int POPULATION_SIZE = 20;

    public static final double MUTATION_PROBABILITY = 0.5;

    public static final int MAX_ITERATIONS = 3000;

    public static final String ALPHABET = "ABCDEFGHIJKLMNOPQRSTUVWXYZ abcdefghijklmnopqrstuvwxyz";
    
}
```
## Exécution
![image](https://github.com/Mansouri-Anas/MultiAgentSystemForGeneticAlgorithm/assets/106403012/79a50787-c6a7-4b4e-aad4-29c2ac0f6fb5)
![image](https://github.com/Mansouri-Anas/MultiAgentSystemForGeneticAlgorithm/assets/106403012/cc9e9b41-c5af-47ed-b060-593dd10588ac)
