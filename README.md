# TERAH2O — Gradiente de Velocidad (Floculación)

Consola bilingüe (ES/EN) para calcular y evaluar el **gradiente de velocidad G** del agua
en floculadores y mezcladores, tramo por tramo.

## Qué hace
- **μ, ρ y γ automáticos** según la temperatura del agua.
- **G por cámara** para mezcla rápida (Parshall por resalto hidráulico), hidráulica
  (pérdida de carga) y mecánica (medición eléctrica o diseño Np, con motorreductor).
- **Tiempo de retención T**, **número de Camp (G·T)** y equivalencia intuitiva de G
  (velocidad relativa entre capas a 1 cm).
- **Gráfico de G por cámara** en escala logarítmica.
- **Verificación normativa** con semáforo (CEPIS / RAS 2000 / NTE INEN / AWWA).
- **Banco de datos de plantas** (configuraciones cargables) e **Informe imprimible / PDF**.

## Desplegar en Vercel
Es un sitio **100% estático** — no requiere build.

1. Crea un repositorio nuevo en GitHub y sube estos archivos:
   - `index.html`  (la aplicación)
   - `support.js`  (runtime — **necesario**, va junto a `index.html`)
2. En [vercel.com](https://vercel.com) → **Add New → Project → Import** tu repositorio.
3. Framework Preset: **Other**. Build Command: *(vacío)*. Output Directory: *(raíz)*.
4. **Deploy**. Vercel servirá `index.html` en la raíz.

> El archivo fuente editable es `Gradiente de Velocidad.dc.html`; `index.html` es su copia
> para el despliegue. Si editas la fuente, vuelve a copiarla a `index.html`.
