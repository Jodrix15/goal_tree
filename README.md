# goal-tree

Mi árbol de metas 2026 → 2030 con estilo de árbol de habilidades de videojuego: ramas Allianz, Finanzas, Vivienda y Pareja, con runas, sinergias entre ramas y escenarios de ahorro.

![HTML5](https://img.shields.io/badge/HTML5-E34F26?style=flat-square&logo=html5&logoColor=white)
![JavaScript](https://img.shields.io/badge/JavaScript-F7DF1E?style=flat-square&logo=javascript&logoColor=black)
![GitHub Pages](https://img.shields.io/badge/GitHub_Pages-222222?style=flat-square&logo=githubpages&logoColor=white)

🌐 **Web:** https://jodrix15.github.io/goal-tree/

## Cómo se usa

1. Haz clic en un nodo para ver su detalle en el panel lateral: foto, runa, descripción, objetivos y requisitos.
2. Pulsa **Marcar como completado** cuando consigas el hito. Se pone dorado y desbloquea los siguientes.
3. Las líneas discontinuas son sinergias: hitos de una rama que ayudan a otra.

## Dónde se guarda el progreso

| Modo | Dónde | Para qué |
|---|---|---|
| Por defecto | Navegador (`localStorage`) | Ver el progreso en un solo dispositivo |
| Con GitHub | `progreso.json` en la rama `datos` | Ver el mismo progreso en cualquier dispositivo |

Para el modo con GitHub, pulsa **Conectar GitHub** y pega un token *fine-grained* con acceso solo a este repo y permiso **Contents** de lectura y escritura. Cada cambio se guarda con un commit en la rama `datos`, separada de `main` para no volver a publicar la web.

## Estructura

| Archivo | Qué contiene |
|---|---|
| `index.html` | Toda la página: estilos, datos del árbol y lógica |
| Rama `datos` | `progreso.json` con los hitos completados |

Los datos del árbol (ramas, hitos, runas y sinergias) están en el `<script>` de `index.html`.

---

🤖 Desarrollado con ayuda de [Claude](https://claude.ai) como asistente de programación.

Fotos: [Unsplash](https://unsplash.com).
