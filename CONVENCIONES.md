# Convenciones del equipo — Donaton EP2

## Ramas (Git Flow simplificado)

- `main` → entrega final, protegida. Solo merge desde develop con PR aprobado
- `develop` → integración del equipo
- `feature/<nombre>` → nueva funcionalidad
- `bugfix/<nombre>` → corrección de errores

## Formato de commits (Conventional Commits)

feat: agrega endpoint POST /donaciones
fix: corrige validación de JWT en gateway
docs: actualiza README de ms-auth
test: agrega prueba unitaria de DonacionFactory
refactor: extrae lógica a DonacionFactory

## Pull Requests

- Todo merge a develop requiere PR
- El PR debe ser revisado por al menos 1 integrante distinto al autor
- No hacer push directo a main

## Integrantes

- Sebastián Robles (serobless) — Frontend + Gateway
- Carlos Miranda — ms-donaciones
- Benjamín Aedo — ms-auth + BFF
