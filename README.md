# ISW2-ModuloSWTesting

## Compilazione ed esecuzione dei test per il progetto Bookkeeper

Esecuzione dei test e generazione dei report di JaCoCo:
```bash
mvn clean verify
```

Esecuzione del mutation test da lanciare su https://github.com/simesi/bookkeeper/tree/master/bookkeeper-server/ oppure su https://github.com/simesi/bookkeeper/tree/master/bookkeeper-common/:
```bash
mvn clean verify -P pit-test
```
Il report di pit viene generato nella directory ```./bookkeeper-server/target/pit-reports/```

## Compilazione ed esecuzione dei test per il progetto OpenJPA

Esecuzione dei test e generazione dei report di JaCoCo:
```bash
mvn clean verify
```

Esecuzione del mutation test da lanciare su  https://github.com/simesi/openjpa/tree/master/bookkeeper-kernel/:
```bash
mvn clean verify -P pit-test
```
Il report di pit viene generato nella directory ```./openjpa-kernel/target/pit-reports/```
