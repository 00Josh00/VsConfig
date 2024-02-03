{
  // =================== CONFIGURACIÓN: Básica de VSCode ===================
  "workbench.startupEditor": "none", // <== No abrir el archivo de bienvenida
  "screencastMode.onlyKeyboardShortcuts": true,
  "breadcrumbs.enabled": false, // <== Nivel de zoom de la pantalla
  "workbench.sideBar.location": "right", // <== Posición de la barra lateral
  "workbench.iconTheme": "material-icon-theme", // <== Tema de iconos
  "workbench.colorTheme": "Min Dark",
  "glassit.alpha": 241,
  "workbench.productIconTheme": "fluent-icons",
  "workbench.tree.indent": 20,
  // =================== CONFIGURACIÓN: JavaScript/Node.js ===================
  "javascript.suggest.autoImports": true,
  "javascript.updateImportsOnFileMove.enabled": "always",
  // =================== CONFIGURACIÓN: React.js ===================
  "emmet.syntaxProfiles": {
    "javascript": "jsx"
  },
  "emmet.includeLanguages": {
    "javascript": "javascriptreact",
    "typescript": "typescriptreact",
    "javascriptreact": "javascriptreact",
    "typescriptreact": "typescriptreact"
  },
  // =================== CONFIGURACIÓN: Archivos y carpetas ===================
  "files.autoSave": "afterDelay", // <== Guardar automáticamente
  "files.associations": {
    ".sequelizerc": "javascript",
    ".stylelintrc": "json",
    "*.tsx": "typescriptreact",
    ".env.*": "dotenv",
    ".prettierrc": "json"
  },
  "files.exclude": {
    "**/CVS": true,
    "**/.DS_Store": true,
    "**/.hg": true,
    "**/.svn": true,
    "**/.git": true,
    "**/node_modules": true,
    "**/__pycache__": true
  },
  // =================== CONFIGURACIÓN: Extensiones ===================
  "extensions.ignoreRecommendations": true, // <== No mostrar recomendaciones de extensiones
  "extensions.autoCheckUpdates": true, // <== Verificar actualizaciones automáticamente
  // =================== CONFIGURACIÓN: TypeScript ===================
  "typescript.tsserver.log": "off",
  "typescript.suggest.autoImports": true,
  "typescript.updateImportsOnFileMove.enabled": "never",
  // =================== CONFIGURACIÓN: Extensión Material Icon Theme ===================
  "material-icon-theme.folders.associations": {
    // ... (lista de asociaciones de carpetas)
  },
  "material-icon-theme.files.associations": {
    // ... (lista de asociaciones de archivos)
  },
  "material-icon-theme.languages.associations": {
    // ... (lista de asociaciones de lenguajes)
  },
  "material-icon-theme.activeIconPack": "nest",
  "material-icon-theme.folders.theme": "specific",
  "material-icon-theme.folders.color": "#6272a4",
  // =================== CONFIGURACIÓN: Editor ===================
  "editor.rulers": [120, 120], // <== Líneas guía
  "editor.fontSize": 16, // <== Tamaño de la fuente
  "editor.tabSize": 2, // <== Tamaño de la tabulación
  "editor.lineHeight": 26, // <== Altura de la línea
  "editor.fontFamily": "Fira Code", // <== Fuente
  "editor.suggestSelection": "first", // <== Seleccionar la primera sugerencia
  "editor.fontLigatures": true, // <== Fuente con ligaduras
  "editor.acceptSuggestionOnCommitCharacter": false, // <== No aceptar sugerencias al escribir
  "editor.accessibilitySupport": "off", // <== Desactivar el soporte de accesibilidad
  "workbench.editor.labelFormat": "short", // <== Formato del nombre del archivo
  "editor.parameterHints.enabled": true, // <== Habilitar sugerencias de parámetros
  "editor.renderLineHighlight": "gutter", // <== Resaltar la línea actual
  "editor.cursorStyle": "line",
  "editor.cursorBlinking": "smooth",
  "editor.stickyScroll.enabled": true,
  "editor.minimap.enabled": false,
  "editor.scrollbar.vertical": "auto",
  "editor.overviewRulerBorder": false,
  "editor.hideCursorInOverviewRuler": true,
  "editor.bracketPairColorization.enabled": true,
  "editor.guides.bracketPairs": "active",
  "editor.wordWrap": "on",

  // =================== CONFIGURACIÓN: Terminal Linux ===================
  "terminal.integrated.fontSize": 16,
  "terminal.integrated.shell.linux": "bash",
  "terminal.integrated.fontFamily": "Fira Code",
  "terminal.integrated.showExitAlert": false,
  "terminal.integrated.env.osx": {
    "FIG_NEW_SESSION": "1"
  },
  // =================== CONFIGURACIÓN: Discord Presence ===================
  "discord.detailsIdling": "👀 Buscando en los archivos...",
  // ... (configuración adicional de Discord Presence)
  // =================== CONFIGURACIÓN: ESLint y Prettier ===================
  "eslint.format.enable": true,
  // ... (configuración adicional de ESLint y Prettier)
  // =================== CONFIGURACIÓN: Explorador de archivos ===================
  "explorer.confirmDelete": false,
  // ... (configuración adicional del explorador de archivos)
  // =================== CONFIGURACIÓN: Git y GitLens ===================
  // ... (configuración de Git y GitLens)
  // =================== CONFIGURACIÓN: Live Share/Server ===================
  "liveshare.featureSet": "insiders",
  // =================== CONFIGURACIÓN: Spell Check ===================
  // ... (configuración de Spell Check)
  // =================== CONFIGURACIÓN: Prisma ===================
  // ... (configuración de Prisma)
  // =================== CONFIGURACIÓN: TabNine ===================
  "tabnine.experimentalAutoImports": true,
  // =================== CONFIGURACIÓN: Seguridad ===================
  "security.workspace.trust.untrustedFiles": "newWindow",
  "editor.matchBrackets": "never",
  "workbench.activityBar.location": "top",
  "window.zoomLevel": -1 // <== Abrir archivos no confiables en una nueva ventana
}
