1. Domina los atajos de teclado e interfaz
Aprender la navegación por teclado elimina la fricción de estar moviendo las manos al ratón constantemente:

Paleta de comandos (Ctrl + Shift + P / Cmd + Shift + P): Es el centro de control. Desde aquí ejecutas cualquier función, ajuste o extensión sin navegar por menús.

Apertura rápida (Ctrl + P / Cmd + P): Escribe el nombre de cualquier archivo para abrirlo al instante sin buscarlo en el árbol de carpetas.

Selección múltiple (Alt + Clic o Ctrl + D / Cmd + D): Permite colocar varios cursores para editar la misma palabra o variable en diferentes líneas al mismo tiempo.

2. Instala extensiones esenciales para tu flujo de trabajo
No satures el editor con decenas de complementos; enfócate en los que verdaderamente optimizan la productividad:

Prettier - Code formatter: Formatea automáticamente el código con un estilo consistente cada vez que guardas (Ctrl + S).

GitLens: Superpone información detallada sobre quién modificó cada línea de código, cuándo y en qué commit, directamente dentro del editor.

Error Lens: Muestra los mensajes de error e advertencias en la misma línea del código en lugar de requerir que pases el cursor sobre la línea afectada.

3. Configura el archivo settings.json para automatizar tareas
Personaliza el comportamiento interno de VS Code agregando reglas que te ahorren tiempo manual. Abre la paleta de comandos, busca Preferences: Open User Settings (JSON) e incluye ajustes clave como:
{
  // Formatea el archivo automáticamente al guardar
  "editor.formatOnSave": true,
  // Limpia espacios en blanco innecesarios al final de las líneas
  "files.trimTrailingWhitespace": true,
  // Activa el ajuste de línea para evitar desplazamiento horizontal
  "editor.wordWrap": "on",
  // Ajusta el tamaño de fuente y la tipografía a tu gusto
  "editor.fontSize": 14
}

DENADA PAPS