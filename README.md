# CopyFolderName

El script copia al portapapeles los nombres de las carpetas dentro de una carpeta seleccionada en el explorador de archivos (funciona para Windows 10 y 11). 
Al hacer clic derecho sobre una carpeta y elegir "Copiar nombres de carpetas" en el menú contextual, se ejecuta un script de PowerShell (CopyFolderNames.ps1) que lista los nombres de los archivos (sin rutas completas) y los une con saltos de línea. 
Este proceso se ejecuta de forma oculta ya que se utiliza un script VBScript (RunHidden.vbs) que llama a PowerShell sin mostrar una ventana de consola. 
El resultado queda en el portapapeles.

FORMA DE INSTALACION

1. Genera una carpeta en C:\ y llamala Scripts
2. Dentro de Scripts, generar otra carpeta y nombrarla CopyFolderName. Debe quedar la sigueinte ruta: C:\Scripts\CopyFolderName
3. Guardar los archivos dentro de dicha ruta
4. Ejecutar AddCopyFolderNames.reg para agregar la funcion al Registro del sistema
5. Para eliminar la funcion ejecutar RemoveCopyFolderNames.reg
