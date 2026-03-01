# Ser.Es-Esencial - Portafolio Institucional 2026

Plataforma web moderna para presentar los servicios de la Corporación Ser Es-Esencial, con un diseño responsivo y componentes interactivos.

## Estructura del Proyecto

```
web/
├── index.html              # Entrada HTML principal
├── package.json            # Dependencias del proyecto
├── vite.config.js          # Configuración de Vite
├── tailwind.config.js      # Configuración de Tailwind CSS
├── postcss.config.js       # Configuración de PostCSS
├── src/
│   ├── index.jsx          # Punto de entrada React
│   ├── index.css          # Estilos globales
│   └── App.jsx            # Componente principal
└── dist/                  # Build compilado (se genera automáticamente)
```

## Instalación

1. **Instalar dependencias:**
```bash
npm install
```

2. **Ejecutar en desarrollo:**
```bash
npm run dev
```

La aplicación se abrirá automáticamente en `http://localhost:5173`

## Scripts Disponibles

- `npm run dev` - Inicia el servidor de desarrollo
- `npm run build` - Compila la aplicación para producción
- `npm run preview` - Vista previa del build compilado

## Tecnologías Utilizadas

- **React 18** - Librería de UI
- **Vite** - Build tool moderno
- **Tailwind CSS** - Framework de CSS
- **Lucide React** - Iconos SVG
- **React Hooks** - Manejo de estado

## Características

✅ Diseño responsivo (mobile, tablet, desktop)  
✅ Navegación suave con scroll  
✅ Componentes interactivos (acordeones, cartas expandibles)  
✅ Animaciones CSS  
✅ Integración con WhatsApp e Instagram  
✅ SEO optimizado

## Despliegue

Para desplegar a producción:

1. Compilar el proyecto:
```bash
npm run build
```

2. Los archivos compilados estarán en la carpeta `dist/`

3. Subir el contenido de `dist/` a tu servidor web

## Notas

- Asegúrese de que Node.js >= 16 esté instalado
- Para cambios en Tailwind CSS, los estilos se actualizarán automáticamente en desarrollo
- El HTML es generado automáticamente por Vite desde `index.html`
