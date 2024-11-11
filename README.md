<p align="center">
  <a href="https://spring.io/projects/spring-boot" target="blank"><img src="https://upload.wikimedia.org/wikipedia/commons/thumb/4/44/Spring_Framework_Logo_2018.svg/2560px-Spring_Framework_Logo_2018.svg.png" width="320" alt="Spring Boot Logo" /></a>
</p>

# **MS Parent Spring Webflux**

## **Descripción**
Este repositorio contiene un proyecto parent para microservicios basados en Spring Webflux. Este parent hereda de `unique-parent-spring` y proporciona una configuración estándar para microservicios, incluyendo dependencias y plugins comunes para desarrollo, pruebas y despliegue.

## **Pre-requisitos**
Para clonar y utilizar este proyecto parent, necesitará [Git](https://git-scm.com), [Java 17.0.11](https://www.oracle.com/java/technologies/javase/jdk17-archive-downloads.html), y [Maven](https://maven.apache.org/download.cgi) instalados en su computadora.

Desde su línea de comando:

```bash
# Clonar repositorio
$ git clone https://github.com/dgcorredorr/ms-parent-spring-webflux

# Entrar al repositorio local
$ cd ms-parent-spring-webflux

# Instalar localmente la aplicación
$ mvn clean install
```

## **Uso**
Este proyecto está diseñado para ser utilizado como un parent en otros proyectos Maven que desarrollan microservicios. Para ello, simplemente incluya la siguiente sección en el `pom.xml` de su proyecto:

```xml
<parent>
    <groupId>com.meli</groupId>
    <artifactId>ms-parent-spring-webflux</artifactId>
    <version>1.0.0-SNAPSHOT</version>
</parent>
```

## **Configuración**
Este parent incluye configuraciones predefinidas para:

- **Dependencias comunes** como `spring-boot-starter-web`, `spring-boot-starter-actuator`, `spring-boot-starter-validation`, `spring-boot-starter-test`, y `springdoc-openapi`.
- **Configuración de logging** con Logback y Logstash para un manejo avanzado de logs.
- **Plugins de construcción** como `spring-boot-maven-plugin` para empaquetado y despliegue.

## **Autores**
Para cualquier duda o contribución, puede contactar a:

| Operación             | Autor                  | Correo                    |
| --------------------- |------------------------|---------------------------|
| General               | David Corredor Ramírez | dgcorredorr@gmail.com |