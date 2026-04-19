# Visual System & Components
## Sistema de Diseño Atómico

### 1. Elementos UI (SaaS Dashboard)

| Componente | Spec |
|---|---|
| Tarjetas de Datos | Fondo oscuro, borde sutil, sombra difusa Signal Green al hacer hover |
| Mapas | Estilo base "Dark Matter" (Mapbox/Google), capas de datos en opacidad 60% |
| Botones | Rectangulares, esquinas 2px border-radius, texto UPPERCASE |

---

### 2. Infografía y Data Viz

- Gráficos de líneas finas sobre fondo oscuro.
- "Puntos de ancla" — pequeños círculos en intersecciones de datos.
- Estilo "Blueprint" técnico para explicar metodología (líneas de nivel, grillas).

---

### 3. Layouts Documentales (Reportes y Briefs)

- **Encabezado:** Ficha técnica siempre visible — Fecha, ID de Proyecto, Hash de Transacción.
- **Márgenes:** Amplios (estilo Linear) para transmitir orden y lujo.
- **Separadores:** Líneas divisorias finas (1px, baja opacidad) en lugar de bloques sólidos.

---

### 4. Glassmorphism Oscuro

Tarjetas y paneles flotantes con:
```css
background: rgba(30, 35, 48, 0.8); /* Glass Grey con 80% opacidad */
backdrop-filter: blur(12px);
border: 1px solid rgba(255, 255, 255, 0.06);
```

---

### 5. Reglas de Oro del Diseño

1. **Nunca Negro Puro:** Fondo siempre en rango `#0B0E14` a `#1A1A1A` — nunca `#000000`.
2. **El Dato es Luz:** Los acentos (verde, azul) deben comportarse como luz — neón, no pintura plana.
3. **Espacio Negativo Radical:** El diseño debe "respirar" aunque sea oscuro.
4. **Accesibilidad:** Contraste mínimo WCAG AA (4.5:1) entre texto y fondo.
