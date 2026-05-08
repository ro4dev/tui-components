# TUI Components

Colección de componentes reutilizables estilo TUI (Terminal User Interface) en HTML, CSS y JavaScript.

Todos los componentes siguen las especificaciones de diseño en [DESIGN.md](./DESIGN.md).

## Estructura

Cada componente vive en su propia carpeta con dos archivos:
- `index.html` — Componente funcional y reutilizable
- `style.css` — Estilos con variables CSS personalizables

```
tui-components/
├── README.md
├── accordions/
│   ├── index.html
│   └── style.css
├── alerts/
│   ├── index.html
│   └── style.css
└── ...
```

## Uso

1. Copia la carpeta del componente a tu proyecto
2. Incluye el CSS: `<link rel="stylesheet" href="style.css">`
3. Copia el HTML del componente (las partes entre `<!-- componente -->`)
4. El JS usa event delegation con `data-action`, no requiere IDs específicos

## Variables CSS

Todos los componentes usan las mismas variables para consistencia:

```css
:root {
  --canvas: #F5F2EB;
  --surface-soft: #EDEAE3;
  --surface-card: #E5E2DB;
  --surface-dark: #1A1A1A;
  --ink: #111111;
  --body: #2A2A2A;
  --mute: #6B6B6B;
  --stone: #8A8580;
  --ash: #9A9590;
  --accent: #007AFF;
  --warning: #FF9500;
  --danger: #FF3B30;
  --success: #34C759;
  --hairline: #D5D2CB;
  --hairline-strong: #B5B2AB;
  --on-dark: #F5F2EB;
  --rounded-sm: 4px;
  --rounded-full: 9999px;
  --spacing-xs: 4px;
  --spacing-sm: 8px;
  --spacing-md: 12px;
  --spacing-lg: 16px;
  --spacing-xl: 24px;
  --spacing-xxl: 32px;
  --font-mono: 'Berkeley Mono', 'SF Mono', 'Fira Code', monospace;
}
```

## Componentes

| Carpeta | Descripción |
|---------|-------------|
| `accordions` | Acordeones expandibles/colapsables |
| `alerts` | Alertas y notificaciones |
| `avatars` | Avatares de usuario |
| `badges` | Insignias y etiquetas |
| `breadcrumbs` | Navegación de migas de pan |
| `cards` | Tarjetas de contenido |
| `code-blocks` | Bloques de código |
| `copy-button` | Botón de copiar |
| `data-display` | Visualización de datos |
| `dialogs` | Diálogos modales |
| `empty-states` | Estados vacíos |
| `feedback` | Componentes de retroalimentación |
| `forms` | Elementos de formulario |
| `keyboard` | Indicadores de teclado |
| `layout` | Componentes de diseño |
| `media` | Elementos multimedia |
| `navigation` | Navegación |
| `panels` | Paneles |
| `progress` | Barras de progreso |
| `tables` | Tablas de datos |
| `tabs` | Pestañas |
| `toggles` | Interruptores |
| `tooltips` | Tooltips e información flotante |
