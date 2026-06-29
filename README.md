# mi-primer-pr

Repositorio de práctica para aprender el flujo de trabajo de un Pull Request en GitHub.

## ¿Qué es esto?

Este repositorio sirve para practicar los pasos básicos de la colaboración con Git y GitHub:

1. Crear una rama (`branch`) para tu cambio.
2. Hacer una modificación y guardarla en un `commit`.
3. Subir la rama (`push`) a GitHub.
4. Abrir un **Pull Request** para proponer el cambio.

## Flujo de trabajo

```bash
git checkout -b mi-rama      # crear y cambiar a una rama nueva
git add .                    # preparar los cambios
git commit -m "mi cambio"    # guardar los cambios
git push -u origin mi-rama   # subir la rama a GitHub
gh pr create                 # abrir el Pull Request
```

## Recursos útiles

- [Documentación de GitHub sobre Pull Requests](https://docs.github.com/es/pull-requests)
- [GitHub CLI (`gh`)](https://cli.github.com)
