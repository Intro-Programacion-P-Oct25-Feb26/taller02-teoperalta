# Taller 2 (Laboratorio): Configuración de uso de Git y GitHub

## Actividades

En el presente repositorio realizar la siguientes tareas:

1. Clonar (git clone) el repositorio en sus máquinas personales; usar git-bash
2. Crear un proyecto con el **IDE de programación Netbeans**, llamado **proyecto01**, el proyecto debe **ser ubicado en la carpeta** creada mediante el proceso de clonación.
3. En la clase Java (.java) creada mediante el proyecto de Netbeans, agregar el siguiente texto, **dentro del método main**, para que se presente dicha información al ejecutar el programa:

```
Ejemplo básico de Java
Versionado a través de Git
Manejado desde GitHub
```
  Recuerde usar la sentencia

```java
System.out.println("Ejemplo básico de Java Versionado a través de Git Manejado desde GitHub");
```

4. Regresar al git-bash (verificar que estemos dentro de la carpeta clonada, pwd)
5. Ejecutar el comando

```
git status
```
Analizar la salida en consola

6. Ejecutar el comando

```
git add .
```

7. Ejecutar el comando

```
git commit -a -m "primer commit"
```

8. Ejecutar el comando

```
git push
```
Es posible que deba usar el proceso de autenticación con el token (creado previamente)

9. Verificar que el repositorio en su cuenta de GitHub esté actualizado; en caso de no estar actualizado, **debe revisar los casos previos**.

10. Regresar al IDE Netbeans, en su máquina persona y modificar la clase de Java creada en el proyecto de Netbeans, con el siguiente texto, para que se muestre cuando se ejecute el programa:

```
Ejemplo de Java
Manejado desde GitHub
Versionado a través de Git
Creado por <ubicar su usuario de github>
```

11. Ejecutar el comando

```
git add .
```
En esta **circunstacia el comando git add sería opcional**; pues, no hay archivos nuevos que gestionar, solo archivos modificados.

12. Ejecutar el comando

```
git commit -a -m "segundo commit"
```

13. Ejecutar el comando

```
git push
```

14. Verificar que el repositorio en su cuenta de github esté actualizado.

15. Crear un proyecto con el **IDE de programación Netbeans**, llamado proyecto02, el proyecto debe ser ubicado en la carpeta creada mediante el proceso de clonación.
16. En la clase de Java creada mediante el proyecto de Netbeans, agregar el siguiente texto, para que se presente al ejecutar el programa:

```
Ejemplo dos básico de Java
Versionado a través de Git
Manejado desde GitHub
Además se usar GitHubClassroom
```
# Cambio en GitHub
* Este cambio fue hecho directamente en GitHub
17. Regresar al git-bash (verificar que estemos dentro de la carpeta clonada)
18. Ejecutar el comando

```
git status
```
Analizar la salida en consola

19. Ejecutar el comando

```
git add .
```

20. Ejecutar el comando

```
git commit -a -m "tercer commit, trabajando con Git y GitHubClassroom"
```

21. Ejecutar el comando

```
git push
```
22. Verificar que el repositorio en su cuenta de **GitHub** esté actualizado.

23. Simular un cambio remoto, para ello se generará un cambio directo en la plataforma GitHub

* Localiza el archivo README.md
* Haz clic en el ícono de edición (lápiz) para modificar el archivo directamente en GitHub.
* Agrega una línea de texto simple, como:

```md
# Cambio en GitHub
* Este cambio fue hecho directamente en GitHub
```
* Haz Commit del cambio directamente en la interfaz web de GitHub (usando el botón "Commit changes")
* **Atención**: El repositorio en GitHub tiene un commit que tu máquina local aún no tiene.

24. Sincronizar cambios a la Máquina Local (Usando git pull)
* Regresar a Git-Bash en tu máquina local (dentro de la carpeta clonada)
* Analizar la salida en consola: Git mostrará que ha descargado un commit y ha fusionado (merged) los cambios en tu rama local.

25. Verificar la integración del Cambio

* Abrir el archivo README.md y verificar que la línea que agregaste en GitHub
