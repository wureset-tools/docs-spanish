# Inicio

<div align="center">
	<a href="https://wureset.com/" target="_blank" rel="noopener noreferrer">
		<img src="https://hispanic.wureset.com/assets/images/logo.png" alt="logo wureset" height="300" width="300">
	</a>
</div>
<br />

Esta herramienta ha sido desarrollada para uso como herramienta de soporte para las opciones de reparación del sistema. Es posible restablecer los componentes de Windows Update. También es capaz de eliminar archivos temporales, escanear, detectar y reparar las corrupciones de la imagen de Windows, analizar todos los archivos protegidos del sistema y reemplazar los archivos dañados, cambiar los valores inválidos en el registro de Windows, restablecer la configuración de Winsock y más.

La herramienta para restablecer los componentes de Windows Update trabaja a través de línea de comandos, pero necesita de requisitos básicos como un sistema operativo compatible, correr con los privilegios de administrador, etc.

Este documento ha sido creado para describir las secuencias de proceso para el uso correcto de la herramienta de restablecimiento de Windows Update.

> ### Contenidos
>
> [Requisitos](#requisitos) <br />
> [Glosario](#glosario) <br />
> [Referencias](#referencias) <br />
> [Licencia](#licencia)

## Requisitos

Esta herramienta es totalmente compatible con Windows 10 o cualquier versión superior del sistema operativo.

Al ejecutar Reset Windows Update Tool, la herramienta detectará automáticamente la versión o build del sistema operativo, que a su vez determina el nombre y la familia del sistema.

En caso de que el sistema operativo no sea compatible con la herramienta, se mostrará un mensaje de error y se cerrará la herramienta.

Traducción realizada con la versión gratuita del traductor www.DeepL.com/Translator

## Glosario

<dl>
<dt>DISM</dt>
<dd>Deployment Image Servicing and Management es una herramienta de línea de comandos que se utiliza para montar y dar servicio a las imágenes de Windows antes de la implementación.</dd>
<dt>Fix It</dt>
<dd>es un programa de diagnóstico que permite detectar problemas que pueden comprometer el buen funcionamiento de Windows.</dd>
<dt>Registry</dt>
<dd>es una base de datos jerárquica central introducida en Microsoft Windows 95 y Windows NT con el fin de almacenar información necesaria para configurar el sistema para uno o varios usuarios, aplicaciones y dispositivos de hardware.</dd>
<dt>Restore point</dt>
<dd>es una representación de un estado almacenado de los archivos de sistema del equipo.</dd>
<dt>SFC</dt>
<dd>System File Checker o Comprobador de Archivos del Sistema es una utilidad de Windows que permite a los usuarios escanear las corrupciones en los archivos de sistema de Windows y restaurar archivos dañados.</dd>
<dt>Winsock</dt>
<dd>es una biblioteca dinámica de funciones DLL para Windows que se hizo con la finalidad de implementar TCP/IP. Incluye soporte para envío y recepción de paquetes de datos a través de sockets BSD.</dd>
</dl>


## Referencias

¿Cómo puedo restablecer los componentes de Windows Update?: [https://support.microsoft.com/es-es/kb/971058](https://support.microsoft.com/es-es/kb/971058).

Use la herramienta Comprobador de archivos de sistema para reparar los archivos de sistema que faltan o están dañados: [https://support.microsoft.com/es-es/kb/929833](https://support.microsoft.com/es-es/kb/929833).

Corregir errores de Windows Update con las herramientas DISM o System Update Readiness: [https://support.microsoft.com/es-es/kb/947821](https://support.microsoft.com/es-es/kb/947821).


## Licencia

Reset Windows Update Tool está icenciado bajo la licencia de MS-PL - ver [Microsoft Public License](https://opensource.org/licenses/MS-PL) para más detalles.
