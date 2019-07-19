# API para Catálogos CONACYT

## Desarrollo

Para levantar el servicio:

    ./mvnw

## Para produccin

### Packaging as jar

Construir el jar obtimizado

    ./mvnw -Pprod clean verify

Probar que funciona:

    java -jar target/*.jar

### Empaquetar como war

    ./mvnw -Pprod,war clean verify

## Para pruebas
    ./mvnw verify
