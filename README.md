# DataConm

## Distribución oficial

Este repositorio contiene exclusivamente los paquetes oficiales de instalación y actualización de DataConm.

El código fuente, los archivos internos de desarrollo, las credenciales, las claves empresariales, las bases de datos operativas, los registros técnicos y los respaldos privados no forman parte de este repositorio.

## Descripción

DataConm es un sistema de Administración de Conexión de Datos Empresariales desarrollado por COMPULABT S.A.

Su función consiste en obtener información desde un ERP, transformarla a una estructura controlada y utilizarla en la administración de productos, precios y existencias de una tienda WooCommerce.

El sistema incorpora validaciones, simulaciones, respaldos y controles destinados a reducir errores antes de publicar información en la tienda.

Técnicamente, DataConm también funciona como middleware entre el ERP y WooCommerce, pero el término middleware no constituye la expansión oficial de su nombre.

## Compatibilidad inicial con ERP

La versión inicial de DataConm está configurada para trabajar con Perseo Web y WooCommerce sobre WordPress.

No debe asumirse que esta versión puede conectarse directamente con cualquier ERP, porque cada sistema puede utilizar estructuras, campos, reportes, credenciales y métodos de acceso diferentes.

COMPULABT S.A. podrá estudiar la incorporación de otros ERP mediante colaboración con las empresas interesadas. El análisis puede requerir información como:

* País donde se utiliza el ERP.
* Nombre y versión del sistema.
* Dirección web, cuando corresponda.
* Estructura de directorios del ERP.
* Método de acceso a los datos.
* Credenciales temporales y de alcance limitado, cuando sean necesarias.
* Acceso autorizado al módulo de reportes de inventario o bodega.
* Formato y nombre de los archivos exportados.
* Archivo de ejemplo en formato CSV, TXT o XLSX.
* Descripción de los campos y datos necesarios.
* Sesiones de acceso remoto mediante AnyDesk cuando el ERP sea local y el análisis lo requiera.

La información entregada para este análisis deberá limitarse a los datos técnicos indispensables. La incorporación de un nuevo ERP dependerá de la viabilidad técnica y de la colaboración proporcionada por la empresa solicitante.

Las solicitudes pueden enviarse a:

```text
giosys@compulab.com.ec
```

## Instalación por primera vez

La persona que instala DataConm por primera vez debe descargar:

```text
DataConmInstaller.zip
```

desde la sección **Assets** de la publicación oficial más reciente.

Después deberá:

1. Extraer completamente el contenido del ZIP.
2. Abrir la carpeta extraída.
3. Ejecutar `DataConmInstaller.exe`.
4. Seleccionar **Descargar e instalar**.
5. Seguir el asistente de instalación de Windows.

DataConmInstaller localizará automáticamente la instalación completa vigente, comprobará su integridad y abrirá el instalador oficial.

No será necesario instalar versiones anteriores ni aplicar una cadena de actualizaciones históricas.

Después de completarse correctamente la instalación, DataConmInstaller puede eliminarse. Las versiones posteriores serán administradas por `DataConmUpdater.exe`, incluido dentro de DataConm.

## Advertencia de Microsoft Defender SmartScreen

Windows puede presentar una advertencia de Microsoft Defender SmartScreen porque esta versión gratuita inicial todavía no posee una firma digital comercial y el ejecutable puede tener poca reputación de descargas.

Cuando `DataConmInstaller.zip` haya sido descargado exclusivamente desde el repositorio oficial de COMPULABT S.A., se puede continuar mediante:

```text
Más información → Ejecutar de todas formas
```

Esta advertencia no confirma que el archivo esté infectado. Indica que Windows todavía no reconoce un editor firmado o una reputación suficiente para el ejecutable.

No se recomienda:

* Desactivar Windows Defender.
* Desactivar el antivirus.
* Crear exclusiones permanentes.
* Ejecutar archivos recibidos desde fuentes desconocidas.
* Descargar DataConm desde repositorios o enlaces no oficiales.

La protección del equipo debe permanecer activa y actualizada.

## Verificación de integridad

Cada paquete oficial se publica acompañado de un archivo `.sha256`.

El valor SHA-256 permite comprobar que el archivo descargado corresponde exactamente al generado por COMPULABT S.A. y que no fue modificado durante su almacenamiento o transferencia.

DataConmInstaller y DataConmUpdater realizan automáticamente las comprobaciones internas correspondientes antes de instalar cualquier paquete.

## Actualizaciones

Los equipos que ya tengan DataConm instalado no deben utilizar nuevamente DataConmInstaller.

Las versiones posteriores se administrarán desde:

```text
Mantenimiento → Actualización del sistema
```

El actualizador comprobará internamente:

* Identidad del producto.
* Versión instalada.
* Versión de destino.
* Integridad del paquete.
* SHA-256.
* Compatibilidad.
* Estructura de datos y credenciales.
* Migraciones requeridas.
* Respaldo previo.
* Resultado de la instalación.
* Recuperación de la versión anterior cuando ocurra un error.

Las actualizaciones no deben reemplazar directamente credenciales, bases de datos, informes, registros ni archivos operativos. Cuando una versión necesite modificar su estructura, el cambio deberá realizarse mediante una migración controlada y reversible.

## Versión gratuita 1.x

La serie DataConm 1.x corresponde a una versión inicial gratuita destinada a evaluación, uso real y colaboración.

Esta serie:

* No establece un límite general de tiempo.
* No establece un límite general de volumen de datos.
* Puede recibir correcciones y mejoras dentro de la versión 1.x.
* Puede incorporar funciones experimentales.
* Puede presentar publicidad o información institucional en versiones futuras.
* Se proporciona sin garantía de funcionamiento ininterrumpido.
* Se utiliza bajo responsabilidad de la persona o empresa usuaria.

Las ideas, observaciones y solicitudes recibidas durante esta etapa podrán utilizarse para mejorar DataConm y desarrollar las versiones comerciales previstas a partir de la versión 2.

## Licencia y restricciones

El uso gratuito de la serie 1.x no significa que el código fuente sea abierto ni que el software pase al dominio público.

No se autoriza:

* Aplicar ingeniería inversa.
* Descompilar o desensamblar el software.
* Extraer o reutilizar componentes internos.
* Modificar ejecutables sin autorización.
* Eliminar identificaciones institucionales.
* Redistribuir versiones modificadas.
* Presentar DataConm como un desarrollo propio o de otra empresa.

Se aceptan solicitudes de modificación destinadas a corregir errores, incorporar otros ERP, aumentar funciones, mejorar el desempeño o adaptar procesos empresariales.

Las modificaciones deberán solicitarse a COMPULABT S.A. para su análisis técnico.

## Soporte y colaboración

Las consultas, reportes de errores, solicitudes de modificación y propuestas de nuevos ERP pueden enviarse a:

```text
giosys@compulab.com.ec
```

Cuando ocurra un error, DataConm puede preparar un archivo ZIP de diagnóstico con la información técnica necesaria para su revisión.

El diagnóstico no debe incluir contraseñas, claves secretas ni credenciales legibles.

## Empresa desarrolladora

```text
COMPULABT S.A.
RUC: 1792709202001
Quito - Ecuador
Sitio web: https://compulab.com.ec/
Correo: giosys@compulab.com.ec
WhatsApp: +593 99 807 2050
```

## Fuente oficial

Los paquetes deben descargarse exclusivamente desde:

```text
https://github.com/compulabt/dataconm-distribucion
```

Los archivos automáticos de código fuente que GitHub presenta como `Source code (zip)` y `Source code (tar.gz)` no contienen el código privado de DataConm. Son archivos generados automáticamente por GitHub a partir del contenido público del repositorio.
