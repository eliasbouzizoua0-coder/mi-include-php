# Práctica include PHP

## Funcionamiento del código
`index.php` crea la variable `$titulo` e incluye `encabezado.php` (que usa `$titulo` en el `<title>`), luego muestra el `<h1>` y finalmente incluye `pie.html`. Al usar `include`, los archivos comparten las variables y se juntan en una misma página.

## Observaciones
- Arranca con `docker compose up -d` en `http://localhost:8080` y se para con `docker compose down`.
