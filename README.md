# ISW2-ModuloSWTesting

## Compilazione ed esecuzione dei test per il progetto Bookkeeper

https://github.com/simesi/bookkeeper

Esecuzione dei test e generazione dei report di JaCoCo:
```bash
mvn clean verify
```

Esecuzione del mutation test:
```bash
mvn clean verify -P pit-test
```
Il report di pit viene generato nella directory ```./bookkeeper-server/target/pit-reports/``` e in  ```./bookkeeper-common/target/pit-reports/```

## Compilazione ed esecuzione dei test per il progetto OpenJPA

https://github.com/simesi/openjpa

Esecuzione dei test e generazione dei report di JaCoCo:
```bash
mvn clean verify
```

Esecuzione del mutation test:
```bash
mvn clean verify -P pit-test
```
Il report di pit viene generato nella directory ```./openjpa-kernel/target/pit-reports/```
