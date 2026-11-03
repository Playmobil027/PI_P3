# GitHub Pages

GitHub Pages serveix per a publicar una web estàtica des d'un repositori. Amb MkDocs es fa així:

```bash
mkdocs gh-deploy
```

Aquesta ordre crea la branca `gh-pages` amb la web generada.

## Activar-ho

1. Entrar al repositori i anar a **Settings → Pages**.
2. A *Source* triar **Deploy from a branch**.
3. Seleccionar la branca `gh-pages` i guardar.

L'adreça de la web té aquest format:

```text
https://usuari.github.io/repositori/
```

!!! success "Fet"
    Si tot ha anat bé, la web ja és visible a Internet.
