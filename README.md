# js-esnext 

Ejercicios sobre métodos de arrays introducidos en ES2023, construidos con **Vite + Vanilla JS**.

## 🛠 Tecnologías

![JavaScript](https://img.shields.io/badge/JavaScript-F7DF1E?logo=javascript&logoColor=black)
![Vite](https://img.shields.io/badge/Vite-646CFF?logo=vite&logoColor=white)

## Conceptos cubiertos

### 01 — Arrays modernos

| Archivo | Concepto |
|---------|----------|
| `array-structured-clone.js` | `structuredClone()` — copia de objetos sin referencias compartidas |
| `array-with.js` | `Array.prototype.with()` y `Array.prototype.at()` — reemplazar elementos sin mutar el array original |
| `array-to-methods.js` | `toSpliced()`, `toSorted()`, `toReversed()` — equivalentes inmutables de splice, sort y reverse

## ⚙️ Instalación y uso

```bash
git clone https://github.com/andresmdevco/js-esnext.git
cd js-esnext
npm install
npm run dev
```

Para probar cada ejercicio, descomenta la línea correspondiente en `src/main.js`:

```js
// import '../01-arrays/array-structured-clone'
// import '../01-arrays/array-with'
import '../01-arrays/array-to-methods' // ← ejercicio activo
```

Los resultados se muestran en la consola del navegador con `console.table`.

## Conceptos practicados

- `structuredClone()` para copias sin mutar el original
- `Array.prototype.with()` para reemplazar un elemento por índice de forma inmutable
- `Array.prototype.at()` para acceder a elementos por índice negativo
- `toSpliced()`, `toSorted()` y `toReversed()` — alternativas inmutables a métodos clásicos de arrays
