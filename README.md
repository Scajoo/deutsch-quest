# Deutsch Quest 🇩🇪

App gamificada (un solo archivo HTML) para aprender alemán a nivel A2–C1, basada en unos apuntes de gramática y construida con ejercicios, repaso espaciado y memoria de fallos. Todo el progreso se guarda en el navegador.

## Cómo usar

Abre **`DeutschQuest.html`** con doble clic (se abre en tu navegador). No necesita instalación ni conexión.

> Consejo: guárdalo siempre en la misma carpeta y márcalo como favorito. El progreso (XP, nivel, racha, fallos, marcadas) se guarda en el `localStorage` del navegador. Desde **⚙️ Progreso** puedes exportar/importar un archivo de respaldo.

## Qué incluye

- **Géneros** (der/die/das) — vocabulario A2–C1, con la regla en cada respuesta (o aviso de que no hay regla / es excepción).
- **Plurales difíciles** — Umlaut, `¨-er`, irregulares, extranjerismos.
- **Genitivo** — incl. masculinos débiles (*des Affen*) con ayuda sobre la *n-Deklination*.
- **Declinación de adjetivos** — con tabla de referencia desplegable.
- **Preposiciones** — escribes la preposición y eliges el caso, con explicación.
- **Verbos irregulares** — Präteritum, Partizip y ejemplo.
- **Gramática** — casos, pasado, pasiva, Konjunktiv II, sintaxis, comparativos, relativos (dessen/deren).

Más de **900 ejercicios** en total. El contenido completo, en tablas legibles, está en [`BASE_DE_DATOS.md`](BASE_DE_DATOS.md).

## Funcionamiento

- **Gamificación**: XP, niveles, racha diaria y logros.
- **Memoria de fallos**: lo que fallas vuelve a salir hasta que lo aciertas dos veces seguidas (con opción de descartarlo).
- **Marcadas**: marca cualquier ítem (📌) para que reaparezca hasta dominarlo.
- **Modo mixto** y modos por tema.

## Estructura

```
DeutschQuest.html   # la app completa (HTML + CSS + JS en un archivo)
BASE_DE_DATOS.md    # todo el contenido en tablas
```

## Tecnología

HTML, CSS y JavaScript puro (sin dependencias ni build). El contenido vive en arrays al principio del `<script>` de `DeutschQuest.html`.
