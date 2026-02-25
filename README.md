# Conector de artículos por temática con línea de tiempo en tiempo real

Aplicación web en HTML/CSS/JS que:

- Intenta conectarse a Internet usando la API pública de Wikipedia.
- Busca artículos relacionados a un tema base.
- Permite seleccionar rango de años (`desde` / `hasta`).
- Permite seleccionar la cantidad máxima de artículos a mostrar.
- Renderiza la conexión en vivo, agregando resultados progresivamente en la línea de tiempo.
- Incluye un modo de respaldo local si la red del entorno bloquea el acceso externo.

## Ejecutar localmente

```bash
python3 -m http.server 8000
```

Luego abre `http://localhost:8000`.
