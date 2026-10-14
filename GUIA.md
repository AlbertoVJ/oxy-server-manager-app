# Empezar con Oxy Server Manager

## Solo quiero probar los paneles

1. En Releases, descarga **OxyServerManager-Windows-x64.zip**. No el ZIP automático Source code.
2. Extrae toda la carpeta en Documentos.
3. Abre **1 - Probar demo.vbs**.

Puedes explorar las pestañas. Los botones que iniciarían servidores, importarían paquetes o descargarían componentes están desactivados en la demo. Usa datos ficticios separados de los servidores reales.

## Quiero administrar un servidor

Cierra la demo y abre **OxyServerManager.exe**. Crea una instancia o importa un Server Pack oficial. Revisa versión, Java y memoria antes de continuar. Para jugar necesitas preparar los componentes del servidor, aceptar la EULA de Minecraft y configurar tu conexión. La app no incluye Minecraft ni tu cuenta de juego.

Python y PySide6 están incluidos en el paquete. Conserva la carpeta **_internal** junto al EXE. No requiere instalar Python ni abrir una terminal.

## Si no abre

Comprueba que extrajiste todo el ZIP y que usas Windows 11 x64. Consulta startup-error.log junto al EXE si aparece. La distribución no está firmada digitalmente; no desactives las protecciones de Windows.

## Respaldos y actualizaciones

Los servidores, ajustes y respaldos están en **data** junto al EXE. Conserva esa carpeta al actualizar y respáldala antes de cambiar un mundo o modpack. Los ejemplos están separados en **demo**. No se distribuyen mundos ni credenciales del autor.

Las licencias y avisos de Python, Qt/PySide6, psutil y PyInstaller se incluyen en el ZIP. Las bibliotecas dinámicas de la interfaz están en _internal.
