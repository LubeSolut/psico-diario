# 📓 PsicoDiario

Diario de registro psicológico personal — PWA instalable en iPhone desde GitHub Pages.

## Secciones del diario

1. **Emociones Positivas** — qué sentí y qué lo causó + intensidad
2. **Emociones Negativas** — qué sentí y qué lo causó + intensidad
3. **Gestión de la Asertividad** — qué dije/hice vs. cómo debería haberlo manejado
4. **Evaluación de Delegación** — si pude delegar y cómo lo hubiera cambiado
5. **Pensamientos Reiterativos** — pensamientos que se repiten
6. **Auto-cura** — gym, meditación, alimentación, descanso...
7. **Actividad Social** — tiempo con familia, amigos, pareja...
8. **Logros y Cualidades** — reconocer lo bueno de mí mismo
9. **Frases Positivas** — recordatorios personales guardados

## Funcionalidades

- Registro por fecha (se puede rellenar días anteriores)
- Historial navegable con vista de detalle
- Colección de frases positivas
- Estadísticas y racha de días consecutivos
- Exportar todos los registros en texto para compartir con la psicóloga
- Funciona sin internet (PWA con caché)
- Los datos se guardan en el dispositivo (localStorage)

## Instalar en iPhone

### Opción A — GitHub Pages (recomendado)

1. Haz fork de este repositorio en tu GitHub
2. Ve a **Settings → Pages → Source: Deploy from branch → main → / (root)**
3. Espera ~2 minutos a que se publique
4. Abre la URL `https://TU-USUARIO.github.io/psico-diario/` en **Safari** (iPhone)
5. Pulsa el botón **Compartir** (⬆️) → **"Añadir a pantalla de inicio"**
6. La app aparece en tu pantalla como cualquier otra aplicación

### Opción B — Netlify (alternativa)

1. Arrastra la carpeta `psico-diario` a [netlify.com/drop](https://app.netlify.com/drop)
2. Copia la URL que te da y ábrela en Safari del iPhone
3. Añadir a pantalla de inicio igual que en la opción A

## Genera los iconos (solo primera vez)

Abre `generate-icons.html` en un navegador, descarga los dos PNG y colócalos en la carpeta raíz junto a `index.html`.

## Privacidad

Todos los datos se guardan **únicamente en tu dispositivo**. No hay servidor, no hay base de datos en la nube, no se envía nada a ningún sitio. Para hacer copia de seguridad, usa el botón **Exportar**.
