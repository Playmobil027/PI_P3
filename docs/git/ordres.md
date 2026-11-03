# Ordres bàsiques

## Crear un repositori

Dins de la carpeta del projecte s'executa:

```bash
git init
```

## Guardar canvis

Per guardar els canvis hi ha dos passos: primer es **preparen** els fitxers i després es fa el **commit**.

```bash
git add .
git commit -m "Primer commit"
```

## Resum

| Ordre | Què fa |
|-------|--------|
| `git status` | Mostra l'estat dels fitxers |
| `git add` | Prepara fitxers per al commit |
| `git commit` | Guarda els canvis |
| `git log` | Mostra l'historial |

!!! warning "Compte"
    `git add .` afegeix **tots** els fitxers. Revisa abans amb `git status`.

!!! danger "Perill"
    L'ordre `git reset --hard` esborra els canvis sense guardar i no es poden recuperar.
