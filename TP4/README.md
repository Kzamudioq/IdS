# Trabajo Práctico 4: Git, Make y Doxygen

## Descripción del trabajo práctico
¡Hola, amiguito! Este trabajo práctico es tan emocionante como un banana split. Vamos a hacer cosas geniales con Git, Make y Doxygen. Los minions están listos para la acción, ¡así que presta atención!

---


<p align="center" width="100%">
    <img width="60%" src="https://github.com/Kzamudioq/SOPG/assets/138271936/de274c78-c5b1-4ec7-9dfb-88a55dcb7fcb"> 
</p>


## Tareas a Realizar
### 1. Resolución de un Conflicto en la Rama Master
¡Oh, no! Hubo un conflicto en la rama master del repositorio de la cátedra. Para arreglarlo, vamos a hacer un commit con la resolución del conflicto. Aquí tienes un ejemplo de código:

```bash
git pull origin master  # Obtén los últimos cambios
# Resuelve los conflictos en tus archivos
git add .              # Añade los cambios
git commit -m "Resuelto el conflicto en la rama master"
git push origin master  # ¡Envía tus cambios de vuelta!
```

### 2. Repositorio Privado Derivado y Documentación con Doxygen
- Realizar un fork del repositorio de la cátedra para crear un repositorio privado derivado.
- Documentar el código fuente utilizando Doxygen.

### 3. Modificación del Archivo Makefile
Agregar una nueva regla en el archivo makefile del repositorio privado. Esta regla deberá generar toda la documentación del proyecto utilizando Doxygen.

### Entregables Requeridos
1. Commit en la rama master con la resolución del conflicto en el repositorio compartido por la cátedra.
2. Repositorio privado derivado mediante un fork del repositorio de la cátedra con:
   - Código fuente documentado usando Doxygen.
   - Una nueva regla en el archivo makefile para generar toda la documentación del proyecto.
3. Pull request para volcar los cambios de la rama develop del repositorio privado en la rama develop del repositorio de la cátedra.

## Instrucciones para la Ejecución
1. Clonar el repositorio de la cátedra: `git clone URL_DEL_REPOSITORIO_CATEDRA.git`
2. Realizar cambios necesarios según las tareas indicadas.
3. Hacer commits y push a las ramas correspondientes.
4. Crear pull request para integrar los cambios en la rama develop del repositorio de la cátedra.

## Recursos Adicionales
- [Enlace a la documentación de Doxygen](https://github.com/Kzamudioq/IdS/blob/master/doxyfile)

## Notas Importantes
- Asegurarse de seguir las buenas prácticas de desarrollo y documentación.
- Comunicarse con el profesor o los colaboradores del proyecto en caso de dudas.

¡Banana-tastic, amigo! 🍌

Este README incluye algunas explicaciones "minion-style" y ejemplos de código implícito para hacerlo más divertido y accesible. ¡Espero que te diviertas trabajando en tu proyecto! 🚀
