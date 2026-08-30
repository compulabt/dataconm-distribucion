# DataConm

## Distribución oficial

Este repositorio contiene exclusivamente los paquetes oficiales de instalación y actualización de DataConm.

El código fuente, los archivos internos de desarrollo, las credenciales, las claves empresariales, las bases de datos operativas, los registros técnicos y los respaldos privados no forman parte de este repositorio.

## Descripción

DataConm es un sistema de integración desarrollado por COMPULABT S.A. para obtener información desde un ERP, transformarla a una estructura controlada y utilizarla en la administración de productos, precios y existencias de una tienda WooCommerce.

El sistema incorpora validaciones, simulaciones y controles destinados a reducir errores antes de publicar información en la tienda.

## Versión disponible

Versión: 1.26.10
Compilación: B0001
Estado: primera versión oficial
Plataforma: Windows
Licencia: versión 1.x de prueba y uso gratuito

La versión más reciente puede encontrarse en la sección Releases de este repositorio.

## Compatibilidad inicial con ERP

El conector ERP incluido en DataConm 1.x ha sido desarrollado y probado inicialmente con Perseo Web.

Esta versión no garantiza compatibilidad directa con Perseo instalado localmente ni con otros sistemas ERP. Los diferentes sistemas pueden utilizar estructuras de bases de datos, nombres de campos, archivos, reportes, mecanismos de autenticación y métodos de extracción distintos.

La selección del ERP determinará en futuras versiones el módulo encargado de interpretar, extraer y convertir la información al formato interno utilizado por DataConm.

## Funciones principales

DataConm incluye actualmente:

* Configuración inicial guiada.
* Conexión protegida con el ERP.
* Conexión protegida con WooCommerce.
* Verificación de permisos de lectura y escritura.
* Administración de categorías.
* Procesamiento de productos nuevos.
* Procesamiento de precios y existencias.
* Centro de Datos.
* Exportación de información.
* Simulación previa a la publicación.
* Publicación controlada en WooCommerce.
* Gestión de imágenes predeterminadas.
* Informes operativos.
* Diagnóstico técnico.
* Reporte asistido de problemas.
* Instalación y desinstalación controladas.
* Componente externo de actualización.

## Flujo general de trabajo

El sistema aplica el siguiente orden operativo:

1. Configuración del ERP.
2. Configuración de WooCommerce.
3. Descarga de la información del ERP.
4. Descarga de la información de WooCommerce.
5. Procesamiento de productos nuevos y existencias.
6. Revisión en el Centro de Datos.
7. Simulación de los cambios.
8. Confirmación del responsable.
9. Publicación en WooCommerce.

El ERP se considera la fuente principal de información. DataConm no debe utilizarse para publicar datos que no hayan sido revisados y simulados previamente.

## Instalación

La instalación debe realizarse utilizando únicamente el paquete publicado en la sección Releases.

Antes de ejecutar el instalador se recomienda:

* Verificar que el archivo corresponda a la versión publicada.
* Confirmar el checksum SHA-256.
* Cerrar cualquier instalación anterior de DataConm.
* Conservar un respaldo independiente de la información operativa.
* Utilizar una cuenta de Windows con permisos para instalar programas.

El instalador se encarga de crear los directorios necesarios, registrar la aplicación y preparar las carpetas operativas.

No debe copiarse manualmente el contenido interno del programa desde una instalación hacia otra.

## Actualizaciones

Las actualizaciones oficiales deberán ser proporcionadas por COMPULABT y procesadas desde:

```text
Mantenimiento → Actualización del sistema
```

El componente de actualización se encargará de:

* Identificar la versión instalada.
* Validar el paquete.
* Comprobar su integridad.
* Crear respaldos.
* Aplicar las migraciones necesarias.
* Registrar cada etapa del proceso.
* Restaurar la instalación anterior cuando se produzca un fallo recuperable.
* Preparar un diagnóstico técnico cuando el proceso no pueda completarse.

Las credenciales, bases de datos, informes, registros y archivos operativos no deberán reemplazarse directamente. Cuando una actualización requiera modificar su estructura, el cambio deberá realizarse mediante una migración controlada, respaldada y verificable.

La comprobación automática de nuevas versiones mediante Internet será incorporada después de completar la configuración oficial del canal de distribución.

## Integración de otros ERP

DataConm ha sido diseñado para incorporar progresivamente nuevos ERP.

Las empresas interesadas podrán solicitar el análisis de otro sistema proporcionando, según corresponda:

* Nombre y versión del ERP.
* País donde se utiliza.
* Dirección web oficial.
* Tipo de instalación: web, servidor o computadora local.
* Método autorizado de acceso.
* Estructura básica de directorios.
* Nombre del archivo generado por el ERP.
* Formato del reporte de inventario.
* Archivo de ejemplo en CSV, TXT o XLSX.
* Descripción de los campos principales.
* Credenciales temporales y limitadas.
* Acceso controlado al módulo de reportes.
* Información técnica adicional necesaria para el estudio.

Cuando el ERP no sea de acceso web, el análisis autorizado podrá realizarse mediante una o varias sesiones remotas utilizando AnyDesk.

Si la empresa solicitante no desea proporcionar acceso directo al ERP, podrá entregar un archivo de ejemplo generado por el sistema y explicar el procedimiento seguido para obtenerlo.

La entrega de información no garantiza automáticamente la integración. COMPULABT S.A. evaluará la viabilidad técnica, la calidad de los datos y el alcance requerido.

Cuando el resultado sea favorable, el ERP podrá incorporarse como una opción seleccionable en futuras versiones de DataConm.

## Reporte de problemas y colaboración

DataConm incorpora una opción de soporte y colaboración para:

* Reportar errores.
* Enviar sugerencias.
* Solicitar mejoras.
* Proponer nuevas funciones.
* Solicitar la integración de otro ERP.
* Preparar información técnica para diagnóstico.

El sistema puede reunir registros técnicos relacionados con un problema y preparar un correo con la información necesaria. Antes del envío deberán revisarse los datos para evitar compartir credenciales, claves o información privada.

Las solicitudes pueden enviarse a:

[giosys@compulab.com.ec](mailto:giosys@compulab.com.ec)

## Licencia de DataConm 1.x

DataConm 1.x se distribuye como una versión inicial de prueba y uso gratuito.

Esta versión funciona como un banco de pruebas abierto a observaciones, reportes de errores y propuestas de mejora. Las experiencias obtenidas podrán contribuir al desarrollo de las versiones comerciales previstas a partir de DataConm 2.

No se establece inicialmente un límite general de procesamiento ni un vencimiento obligatorio para esta versión. Sin embargo, las condiciones particulares podrán variar según la compilación publicada.

El uso de DataConm no autoriza:

* Aplicar ingeniería inversa.
* Descompilar el programa.
* Extraer o reconstruir su código.
* Modificar componentes internos sin autorización.
* Eliminar identificaciones de propiedad.
* Redistribuir versiones alteradas.
* Presentar el software como producto propio.
* Utilizar marcas o elementos gráficos de COMPULABT S.A. sin autorización.

Las solicitudes de corrección, modificación, integración o mejora serán recibidas por los canales oficiales y evaluadas por COMPULABT S.A.

## Responsabilidad

DataConm se proporciona sin garantía de funcionamiento ininterrumpido.

La persona o empresa usuaria es responsable de:

* Revisar la configuración.
* Validar las credenciales.
* Confirmar los datos procesados.
* Ejecutar las simulaciones.
* Revisar los cambios antes de publicarlos.
* Mantener respaldos independientes.
* Proteger el acceso al sistema.
* Verificar las actualizaciones antes de aplicarlas.

COMPULABT S.A. no será responsable por pérdidas de información, interrupciones operativas, publicaciones incorrectas, configuraciones inadecuadas, accesos no autorizados o decisiones tomadas sin revisar los resultados presentados por el sistema.

## Aclaración sobre productos de terceros

Perseo, WooCommerce, WordPress, Windows, AnyDesk y las demás marcas mencionadas pertenecen a sus respectivos propietarios.

DataConm y COMPULABT S.A. no representan, sustituyen ni forman parte de las empresas propietarias de estos productos.

Las referencias se incluyen únicamente para identificar compatibilidad técnica, métodos de integración o herramientas que pueden intervenir durante la configuración y soporte.

## Seguridad

Los paquetes oficiales deben descargarse únicamente desde este repositorio o desde un canal autorizado por COMPULABT S.A.

No deben compartirse públicamente:

* Credenciales del ERP.
* Credenciales de WooCommerce.
* Claves empresariales.
* Contraseñas de paquetes.
* Bases de datos operativas.
* Informes internos.
* Registros que contengan información privada.
* Respaldos de instalaciones.
* Archivos técnicos de clientes.

La comprobación mediante SHA-256 permite verificar la integridad del archivo, pero no sustituye una firma digital. Las futuras versiones podrán incorporar mecanismos adicionales de firma y verificación de procedencia.

## Empresa desarrolladora

COMPULABT S.A.
RUC: 1792709202001
Quito, Ecuador
WhatsApp: +593 99 807 2050
Correo: [giosys@compulab.com.ec](mailto:giosys@compulab.com.ec)
Sitio web: https://compulab.com.ec/

Logo y marcas utilizados con autorización de COMPULABT S.A.
