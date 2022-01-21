Correa
Un script para iniciar un sistema de desarrollo macOS mínimo. Esto no supone que esté haciendo Ruby/Rails/desarrollo web, sino que instala el conjunto mínimo de software que todos los desarrolladores de macOS querrán.

Motivación
Reemplazo de Boxen en GitHub con una mejor herramienta. Esta publicación describe los problemas con Boxen y los requisitos para Strap y otras herramientas utilizadas por GitHub: https://mikemcquaid.com/2016/06/15/replacing-boxen/

Características
Deshabilita Java en Safari (para mayor seguridad)
Habilita la contraseña del protector de pantalla de macOS inmediatamente (para mayor seguridad)
Habilita el firewall de la aplicación macOS (para mayor seguridad)
Agrega un Found this computer?mensaje a la pantalla de inicio de sesión (para la recuperación de la máquina)
Habilita el cifrado de disco completo y guarda la clave de recuperación de FileVault en el escritorio (para mayor seguridad)
Instala las herramientas de línea de comandos de Xcode (para compiladores y herramientas de Unix)
Aceptar la licencia de Xcode (para usar compiladores sin avisos)
Instala Homebrew (para instalar software de línea de comandos)
Instala Homebrew Bundle (para soporte bundlersimilar )Brewfile
Instala los servicios de Homebrew (para administrar los servicios instalados de Homebrew)
Instala Homebrew Cask (para instalar software gráfico)
Instala las últimas actualizaciones de software de macOS (para mayor seguridad)
Instala dotfiles desde el https://github.com/username/dotfilesrepositorio de un usuario. Si existen y son ejecutables: se ejecuta
