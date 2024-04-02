## Instrucciones

Autor del reto: Sanjay C/Danny Tunitis


**Descripción:**

¿Sabes cómo moverte entre directorios y leer archivos en la terminal? Inicia el contenedor, conecta a él a través de `ssh`, y luego ejecuta `ls` una vez conectado para comenzar. Inicia sesión vía `ssh` como `ctf-player` con la contraseña `a13b7f9d`.

Detalles adicionales estarán disponibles después de lanzar tu instancia del desafío.


***

## Walkthrough

1. 

```BASH
cat /tmp/tmp.TO8G0TPrnv | tr -d \\n | xargs
```