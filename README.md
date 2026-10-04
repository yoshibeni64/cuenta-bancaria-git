# Cuenta bancaria — Git y pull requests

**Autor:** José Rodrigo Benítez Rivera

## Cómo correr

```
./correr.sh
```

## Mis pull requests

| # | Qué cambió                                                                      |
| - | ------------------------------------------------------------------------------- |
| 1 | El estado de cuenta muestra cuántos retiros se hicieron y cuántos fueron gratis |
| 2 | README y evidencia de la práctica                                               |

## Boleto de salida

1. ¿Qué diferencia hay entre `git add` y `git commit`?

   **Respuesta:** El comando git.add prepara los cambios realizados en archivos para el commit mientras que git.commit guarda esos cambios en el historial de Git.

2. ¿Por qué después del merge en GitHub tu `main` de Ubuntu no tenía el cambio hasta que hiciste `git pull`?

   **Respuesta:** Porque el merge ocurrió en el repositorio de GitHub no en local, por lo tanto mi repositorio main de mi computadora aún no tenía esos cambios hasta que ejecute git pull para poner al corriente los archivos locales con los de GitHub.

3. Abriste un PR y después hiciste otro commit en la misma rama. ¿Qué pasó con el PR?

   **Respuesta:** El nuevo commit se agregó automáticamente al mismo PR porque el PR sigue esa rama. No fue necesario crear otro PR.

4. ¿Por qué en un equipo nadie hace cambios directamente en `main`?

   **Respuesta:** Porque la rama main es la rama principal donde deben incluirse los cambios definitivos para el proyecto de forma legible y sin errores, por lo tanto primero se realizan los cambios en ramas y se revisan mediante pull requests antes de integrarlos.

