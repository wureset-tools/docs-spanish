# Uso

La herramienta Restablecer Windows Update utiliza funciones de línea de comandos para implementar sus procesos. Es importante tener en cuenta que algunas funciones de recuperación pueden no estar disponibles en todas las versiones de Windows, y la herramienta detectará dichas limitaciones para evitar posibles errores.

Para aplicar las correcciones necesarias, simplemente escriba el número correspondiente a la función deseada y pulse "Intro".

> ### Contenidos
>
> [Ejecutar como administrador](#ejecutar-como-administrador) <br />
> [Línea de comandos](#linea-de-comandos)

## Ejecutar como administrador

**El Control de Cuentas de Usuario** (UAC por sus siglas en inglés) es un recurso obligatorio de control de acceso introducido con los sistemas operativos Windows Vista y Windows Server 2008 de Microsoft, con una versión más relajada también presente en Windows 7, Windows Server 2008 R2, Windows 8, Windows Server 2012 y Windows 10. Su objetivo es mejorar la seguridad de Microsoft Windows al limitar el software de la aplicación a los privilegios de usuario estándar hasta que un administrador autorice un aumento o elevación. De esta manera, solo las aplicaciones confiables por el usuario pueden recibir privilegios administrativos, y se debe evitar que el malware ponga en peligro el sistema operativo. En otras palabras, una cuenta de usuario puede tener privilegios de administrador asignados, pero las aplicaciones que ejecuta el usuario no heredan esos privilegios a menos que se aprueben de antemano o el usuario lo autorice explícitamente.

### Cómo ejecutar un programa como administrador

Para ejecutar un programa como administrador, siga estos pasos:

1. Haga clic en el icono que se utiliza para ejecutar el programa y, a continuación, haga clic en **Ejecutar como administrador**.
2. Cuando se le pida una contraseña de administrador o una confirmación, escriba la contraseña de administrador o haga clic en **continuar**.

Para algunos iconos de programa, la opción **Ejecutar como administrador** no está disponible en el menú contextual. Para estos iconos de programa, siga estos pasos:

1. Haga clic en el icono que se utiliza para ejecutar el programa y, a continuación, haga clic en **Propiedades**. En la pestaña **acceso directo** del cuadro **destino** contiene la ubicación y el nombre del archivo del programa.
2. Abra la carpeta que contiene el archivo de programa.
3. Haga clic en el archivo de programa y, a continuación, haga clic en **Ejecutar como administrador**. Si se le pide una contraseña de administrador o una confirmación, escriba la contraseña o haga clic en **continuar**.

Si debe ejecutar un programa como administrador, es aconsejable configurar el programa para que se ejecute automáticamente como administrador. Para ello, siga estos pasos:

1. Haga clic en el icono que se utiliza para ejecutar el programa y, a continuación, haga clic en **Propiedades**.
2. En la pestaña **compatibilidad**, haga clic para activar la casilla de verificación **ejecutar este programa como administrador** y, a continuación, haga clic en **Aceptar**.

La pestaña **compatibilidad** no está disponible para algunos iconos de programa. Para estos iconos de programa, siga estos pasos:

1. Haga clic en el icono que se utiliza para ejecutar el programa y, a continuación, haga clic en **Propiedades**. En la pestaña **acceso directo** del cuadro **destino** contiene la ubicación y el nombre del archivo del programa.
2. Abra la carpeta que contiene el archivo de programa.
3. Haga clic en el archivo de programa y, a continuación, haga clic en **Propiedades**.
4. En la pestaña **compatibilidad**, haga clic para activar la casilla de verificación **ejecutar este programa como administrador** y, a continuación, haga clic en **Aceptar**.

<div align="center">
	<img src="https://hispanic.wureset.com/assets/images/runas.gif" alt="contextual menu run as an admin">
</div>
<br />

Para más información, ver [referencia](https://support.microsoft.com/es-es/kb/922708)

## Línea de comandos

Reset Windows Update Tool puede userse en línea de comandos de la siguiente manera:

```
$ WURESET [/reset][/search][/clean:{temp|regs|sock}][/sfc][/dism:{scan|check|repair|clean}]
```

Aquí se enumeran entre paréntesis las distintas opciones que se pueden utilizar con la herramienta. Estas opciones incluyen reiniciar la herramienta, buscar actualizaciones, limpiar archivos temporales o valores del registro, ejecutar System File Checker (SFC) y ejecutar DISM para analizar, comprobar, reparar o limpiar la imagen del sistema.

**Lista de parámetros**

<table border="0" cellpadding="4">
	<tr>
		<th>
			Parámetro
		</th>
		<th>
			Descripción
		</th>
		<th>
			Abreviación
		</th>
		<th>
			Ejemplo
		</th>
	</tr>
	<tr>
		<td>
			reset
		</td>
		<td>
			Restablecer los componentes de Windows Update.
		</td>
		<td>
		</td>
		<td>
			/reset <br />
			-reset
		</td>
	</tr>
	<tr>
		<td>
			search
		</td>
		<td>
			Busca actualizaciones.
		</td>
		<td>
		</td>
		<td>
			/search <br />
			-search
		</td>
	</tr>
	<tr>
		<td>
			clean
		</td>
		<td>
			Opciones de limpieza.
		</td>
		<td>
		</td>
		<td>
			/clean:temp <br />
			/clean:regs:temp <br />
			-clean:temp <br />
			-clean:sock
		</td>
	</tr>
	<tr>
		<td>
			sfc
		</td>
		<td>
			Analiza todos los archivos protegidos del sistema.
		</td>
		<td>
		</td>
		<td>
			/sfc <br />
			-sfc
		</td>
	</tr>
	<tr>
		<td>
			dism
		</td>
		<td>
			Opciones DISM.
		</td>
		<td>
		</td>
		<td>
			/dism:scan:repair:clean <br />
			-dism:check:repair
		</td>
	</tr>
	<tr>
		<td>
			help
		</td>
		<td>
			Muestra un mensaje de ayuda.
		</td>
		<td>
			<b>h</b> o <b>?</b>
		</td>
		<td>
			/help <br />
			/h <br />
			/? <br />
			-help <br />
			-h <br />
			-?
		</td>
	</tr>
	<tr>
		<td>
			version
		</td>
		<td>
			Muestra un mensaje de versión.
		</td>
		<td>
			<b>v</b>
		</td>
		<td>
			/version <br />
			/v <br />
			-version <br />
			-v
		</td>
	</tr>
</table>

**Ejemplo de uso:**

<div>
	<img src="https://hispanic.wureset.com/assets/images/commands.gif" alt="example of command line">
</div>
<br />

Para verificar la versión

<div>
	<img src="https://hispanic.wureset.com/assets/images/version.gif" alt="get version with command line">
</div>
<br />
