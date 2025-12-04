# Simulador de factura eléctrica · Electric Bill Simulator

[Ir a Español](#español) · [Go to English](#english)

---

## Español

### 🔗 Acceso
- Sitio en producción: [simuladorluz.netlify.app](https://simuladorluz.netlify.app)

### ✨ Características
- Tema claro/oscuro con persistencia en `localStorage`
- Cálculo para:
  - 1 o 2 periodos de potencia (P1, P2)
  - 1 o 3 periodos de energía (P1, P2, P3)
  - Impuesto eléctrico, IVA, alquiler de contador y bono social
- Interfaz limpia y accesible (uso de `aria-*` y tipografías profesionales)
- Resumen detallado y legible en formato monoespaciado

Enlaces:
- Tipografías: [Inter](https://fonts.google.com/specimen/Inter), [JetBrains Mono](https://fonts.google.com/specimen/JetBrains+Mono)
- `color-mix()` en CSS: [MDN](https://developer.mozilla.org/docs/Web/CSS/color_value/color-mix)

### 📸 Demo
- Abre `index.html` directamente en tu navegador.
- O usa la versión desplegada: [simuladorluz.netlify.app](https://simuladorluz.netlify.app)
- No requiere servidor ni instalación.

### 🚀 Empezar
1. Clona el repositorio:
   ```bash
   git clone https://github.com/<owner>/<repo>.git
   cd <repo>
   ```
2. Abre `index.html`:
   - Doble clic
   - O con un servidor estático:
     ```bash
     npx serve .
     # o
     python -m http.server 8080
     ```
   Enlaces:
   - `serve` (npm): [serve](https://www.npmjs.com/package/serve)
   - Python Simple Server: [docs](https://docs.python.org/3/library/http.server.html)

### 🧮 Uso
- Ajusta los “Parámetros”:
  - Días de facturación
  - Activar 2 periodos de potencia
  - Activar 3 periodos de energía
- Personaliza las “Opciones avanzadas”:
  - Alquiler por día (€)
  - Bono social por día (€)
  - Impuesto eléctrico (%)
  - IVA (%)
- El “Resumen” se actualiza automáticamente al cambiar valores.

### ♿ Accesibilidad
- Botón de tema con `aria-pressed`
- Áreas dinámicas con `aria-live="polite"`
- Colores con buen contraste en ambos temas
- Navegación por teclado en controles

Enlaces:
- WAI-ARIA: [W3C](https://www.w3.org/WAI/standards-guidelines/aria/)
- Guía de contraste: [WCAG 2.1](https://www.w3.org/TR/WCAG21/#contrast-minimum)

### 🛠️ Tecnologías
- HTML + CSS (variables CSS para temas)
- JavaScript vanilla
- Tipografías: Inter y JetBrains Mono

### 🔧 Personalización
- Paleta y radios: editar variables en `:root` y `:root[data-theme="light"]`
- Textos y etiquetas: dentro de `index.html`
- Lógica de cálculo: función `calcular()` en el `<script>`

### 📦 Estructura
```
.
├── index.html   # Aplicación principal
└── README.md    # Este archivo
```

### 🤝 Contribuir
¡Se aceptan PRs!
- Crea una rama descriptiva
- Asegúrate de que la UI se vea bien en ambos temas
- Mantén los nombres de campos coherentes y accesibles

Enlaces:
- Cómo abrir un PR: [GitHub Docs](https://docs.github.com/pull-requests)

### 🐞 Incidencias
- Reporta errores o solicita mejoras en la pestaña Issues del repositorio.

Enlaces:
- GitHub Issues: [Docs](https://docs.github.com/issues)

### 📄 Licencia
MIT. Puedes usarlo y adaptarlo libremente.

Enlaces:
- Licencia MIT: [Open Source Initiative](https://opensource.org/license/mit/)

---

## English

### 🔗 Access
- Production site: [simuladorluz.netlify.app](https://simuladorluz.netlify.app)

### ✨ Features
- Light/Dark theme with persistence in `localStorage`
- Calculation for:
  - 1 or 2 power periods (P1, P2)
  - 1 or 3 energy periods (P1, P2, P3)
  - Electric tax, VAT, meter rental, social bonus
- Clean and accessible UI (uses `aria-*` and professional fonts)
- Detailed, readable summary in monospaced format

Links:
- Fonts: [Inter](https://fonts.google.com/specimen/Inter), [JetBrains Mono](https://fonts.google.com/specimen/JetBrains+Mono)
- `color-mix()` in CSS: [MDN](https://developer.mozilla.org/docs/Web/CSS/color_value/color-mix)

### 📸 Demo
- Open `index.html` directly in your browser.
- Or use the deployed version: [simuladorluz.netlify.app](https://simuladorluz.netlify.app)
- No server or installation required.

### 🚀 Getting Started
1. Clone the repository:
   ```bash
   git clone https://github.com/<owner>/<repo>.git
   cd <repo>
   ```
2. Open `index.html`:
   - Double click
   - Or use a static server:
     ```bash
     npx serve .
     # or
     python -m http.server 8080
     ```
   Links:
   - `serve` (npm): [serve](https://www.npmjs.com/package/serve)
   - Python Simple Server: [docs](https://docs.python.org/3/library/http.server.html)

### 🧮 Usage
- Adjust “Parameters”:
  - Billing days
  - Enable 2 power periods
  - Enable 3 energy periods
- Customize “Advanced options”:
  - Meter rental per day (€)
  - Social bonus per day (€)
  - Electric tax (%)
  - VAT (%)
- The “Summary” updates automatically on change.

### ♿ Accessibility
- Theme button with `aria-pressed`
- Dynamic areas with `aria-live="polite"`
- Good contrast in both themes
- Keyboard-friendly controls

Links:
- WAI-ARIA: [W3C](https://www.w3.org/WAI/standards-guidelines/aria/)
- Contrast guidelines: [WCAG 2.1](https://www.w3.org/TR/WCAG21/#contrast-minimum)

### 🛠️ Tech
- HTML + CSS (CSS variables for theming)
- Vanilla JavaScript
- Fonts: Inter & JetBrains Mono

### 🔧 Customization
- Palette and radii: edit variables in `:root` and `:root[data-theme="light"]`
- Labels and text: inside `index.html`
- Calculation logic: `calcular()` in `<script>`

### 📦 Structure
```
.
├── index.html   # Main app
└── README.md    # This file
```

### 🤝 Contributing
Pull requests are welcome!
- Create a descriptive branch
- Ensure the UI looks good in both themes
- Keep field names consistent and accessible

Links:
- How to open a PR: [GitHub Docs](https://docs.github.com/pull-requests)

### 🐞 Issues
- Report bugs or request features in the repository’s Issues tab.

Links:
- GitHub Issues: [Docs](https://docs.github.com/issues)

### 📄 License
MIT. Free to use and adapt.

Links:
- MIT License: [Open Source Initiative](https://opensource.org/license/mit/)
