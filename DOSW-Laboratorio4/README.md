# Bankify

comando de maven: 

```
mvn org.apache.maven.plugins:maven-archetype-plugin:3.2.1:generate -DgroupId="edu.dosw.lab" -DartifactId="DOSW-Laboratorio4" -DarchetypeGroupId="org.apache.maven.archetypes" -DarchetypeArtifactId="maven-archetype-quickstart" -DarchetypeVersion="1.5" -DinteractiveMode=false
```
---

### Integrantes

- Daniel Alexander Ahumada León
- Juan Camilo Torres
- Juan Manuel Neira Zuluaga

---

## Preguntas teoricas

a. ¿Qué es un arquetipo (Archetype) en Maven?

Un arquetipo es un molde para generar proyectos 

b. ¿Para qué sirve el arquetipo maven-archetype-quickstart?

Es la plantilla más básica y utilizada de Maven. Sirve para generar la estructura inicial de una aplicación Java estándar (JAR)

c. ¿Cuál es el comando con el cual se puede crear un proyecto basado en
un arquetipo maven?

El comando base es:

```
mvn archetype:generate
```
Para que sea automático, se le añaden parámetros como

```
-DgroupId, -DartifactId y -DarchetypeArtifactId Apache Maven Docs.
```
d. ¿Qué es un pull request en GitHub?

Es una propuesta de cambios que un desarrollador hace a un repositorio. Permite que otros miembros del equipo revisen el código, lo comenten y discutan las mejoras antes de fusionarlo (merge) con la rama principal GitHub Docs.

e. ¿Cómo se crea un pull request en GitHub?

1. Sube tus cambios a una rama en GitHub (git push).
2. Entra al repositorio en la web de GitHub.
3. Verás un botón amarillo que dice "Compare & pull request".
4. Describe tus cambios y haz clic en "Create pull request" Atlassian Git

f. ¿Cómo se aprueba un pull request en GitHub?

Dentro del Pull Request, ve a la pestaña "Files changed".
Haz clic en el botón verde "Review changes".
Selecciona la opción "Approve", escribe un comentario opcional y envía la revisión GitHub Docs.

g. Bibliografía en norma APA de donde consultaron las preguntas
anteriores

GitHub. (s.f.). *About pull requests*. GitHub Docs. Recuperado el 14 de febrero de 2026, de https://docs.github.com

Apache Software Foundation. (s.f.). *Introduction to Archetypes*. Apache Maven Project.