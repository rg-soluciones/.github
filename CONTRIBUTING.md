# Cómo se trabaja en los repos de RG Soluciones

- **Ramas:** `main` es lo publicado; `develop`, lo que va a salir. El trabajo va en una rama
  `tipo/tema` (`fix/…`, `feature/…`, `hotfix/x.y.z`) y entra por PR.
- **Commits y PR en español**, contando qué cambia y por qué.
- **Nada de secretos** en el código: claves, contraseñas, tokens y ficheros `.env` van fuera del
  repo. Un workflow (`secretos.yml`) lo vigila en cada push.
- **Dependencias:** Dependabot abre PRs cada semana; se revisan como cualquier otro cambio.
- Cada repo tiene su `CLAUDE.md` y su `README.md` con lo particular de ese programa.
