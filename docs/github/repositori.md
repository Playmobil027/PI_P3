# Repositori remot

## Passos

1. Crear un repositori nou a GitHub.
2. Enllaçar el repositori local amb el remot.
3. Pujar els canvis.

```bash
git remote add origin https://github.com/usuari/projecte.git
git branch -M main
git push -u origin main
```

## Ordres per a sincronitzar

- `git push`: puja els commits a GitHub.
- `git pull`: baixa els canvis de GitHub.

??? info "Què és origin?"
    És el nom que se li dona normalment al repositori remot.
