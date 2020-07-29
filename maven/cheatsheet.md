# MAVEN

## Creación de un nuevo proyecto JAVA basado en una plantilla (Arquetipo)
mvn archetype:generate -DarchetypeArtifactId=maven-archetype-quickstart
mvn archetype:generate -DarchetypeArtifactId=maven-archetype-webapp

## Identificar un proyecto MAVEN:
- groupID: 
    - Empresa/Organización al cargo del desarrollo (Dominio invertido)
        - Ejemplo: com.gfi
    - Qué estoy desarrollando a alto nivel?
        - Ejemplo: web-app-nominas
    - Las juntamos mediante un punto: com.gfi.web-app-nominas 
- artifactId: Qué es nuestro proyecto a bajo nivel?
    -  Ejemplo: web-services
El identificado de un proyecto es groupID + artifactId

# Goles
mvn GOLE_NAME
    - clean: 
    - compile: Compilación del proyecto
    - test-compile: compilar lso tests unitarios
    - test: Ejecutar todas las pruebas unitarias
    - package: empaquetar proyecto
    - install: Incluir nuestro artefacto en el repo local de maven