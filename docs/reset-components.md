# Restablecer componentes

Si experimenta problemas persistentes con Windows Update, puede ser necesario restablecer los componentes de Windows Update a su configuración predeterminada. Esta herramienta está diseñada específicamente para solucionar problemas relacionados con estos componentes.

> ### Contenidos
>
> [Restablecer los Componentes de Windows Update](#restablecer-los-componentes-de-windows-update) <br />
> [El servicio de actualización de Windows no se pudo detener](#el-servicio-de-actualizacion-de-windows-no-se-pudo-detener)

## Restablecer los componentes de Windows Update

Antes de proceder, es importante crear una copia de seguridad del registro por si algo sale mal durante el proceso.

Para restablecer los valores predeterminados de los componentes de Windows Update, seleccione la opción "Restablecer componentes de Windows Update". Esto detendrá los servicios de Windows Update y limpiará los componentes, restaurándolos a sus valores iniciales.

La herramienta comenzará a restablecer los componentes automáticamente, y el proceso debería completarse en unos minutos.

Once completed, it is recommended to install the latest Windows Update Agent from the following link: [https://support.microsoft.com/en-us/kb/949104](https://support.microsoft.com/en-us/kb/949104).

Después de eso, instale el último agente de Windows Update: [https://support.microsoft.com/es-es/kb/949104](https://support.microsoft.com/es-es/kb/949104).

Finalmente, reinicie su PC para guardar los cambios.

## El servicio de actualización de Windows no se pudo detener

Si el Servicio de Windows Update no se detiene, ejecute esta herramienta en modo seguro.

<div align="center">
	<img src="https://hispanic.wureset.com/assets/images/failed.png" alt="failed command">
</div>
<br />

Para acceder al Modo Seguro, puedes entrar en el entorno de recuperación de Windows manteniendo pulsada la tecla Mayús mientras haces clic en Reiniciar. Esto te llevará al menú Opciones avanzadas de inicio, donde puedes seleccionar Modo seguro.

Si sigues experimentando el error, es posible que tu instalación de Windows esté en mal estado y requiera reparación o reinstalación.
