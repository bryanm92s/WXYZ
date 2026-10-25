# CUSTOMIZACIONES.md — WXYZ
> Diferencias respecto a la plantilla (madre: SZ @ 1f845d2).
> Si este archivo está vacío, el repo es idéntico a la madre en código.

| Archivo | Qué cambió | Por qué | Fecha |
|---|---|---|---|
| `package.json` / `package-lock.json` | `name` = `wxyz` | Identidad del repo | 2026-10-15 |
| `logo.png` | Logo propio (LOGO-NAIL) | Icono de pantalla de inicio del negocio | 2026-10-15 |
| `docs/*`, `README.md`, `SETUP.md` | Marca renombrada SZ → WXYZ (formando los valores por defecto del código) | La documentación habla del repo nuevo | 2026-10-15 |
| _(código: sin personalizaciones)_ | | | |

## Reglas
1. Cambio **del cliente** → su repo. Fix **de plantilla** → SZ → portar.
2. No portes archivos enteros si el cliente los personalizó: usa parches.
3. Siempre `npm test` en verde después de portar.

## Historial de sincronización con la madre
- 2026-10-15 · madre @ 3f38967 (sesión del 15/10)
- 2026-10-15 · catálogos nuevos @ 16862a0 · docs onboarding @ dd97a52 · LOGOS @ 12b8a9f
- 2026-10-17 · **feature propia**: «Detalle Gastos» baja sola al abrir
  categoría + título «Gastos por día» (`ea5270e`, `abc06cd`) — después
  **portada a la madre**, así que ya no es divergencia.
- 2026-10-24 · madre @ 1f845d2 (sesiones 21–24/10): botón «📧 Enviar por
  correo», borrado de eventos clasificado + anti-duplicados + `escr`,
  12 paletas AA, capa de conexión con reintentos, «📅 Ir a cita», emoji
  dinámico del Panel, 377 tests.
