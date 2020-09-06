# ISW2-ModuloSWTesting

## Compilazione ed esecuione dei test per il progetto Bookkeeper

Esecuzione dei test e generazione dei report di JaCoCo:
```bash
mvn clean verify
```

Esecuzione del mutation test da eseguire su...:
```bash
mvn clean verify -P pit-test
```
Il report di pit viene generato nella directory ```./bookkeeper-server/target/pit-reports/```

## Compilazione ed esecuione dei test per il progetto OpenJPA

Esecuzione dei test e generazione dei report di JaCoCo:
```bash
mvn clean verify
```

Esecuzione del mutation test:
```bash
mvn clean verify -P pit-test
```
Il report di pit viene generato nella directory ```./openjpa-kernel/target/pit-reports/```
