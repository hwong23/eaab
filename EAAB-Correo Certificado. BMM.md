# Correo Certificado. BMM



![Correo Certificado. BMM][embedView]

Requerimientos de control del módulo de Administración de Correo Certificado y las razones misionales (MOT02 y 03) que sostienen la implementación de este módulo que hace parte del SGDEA integral de la EAAB.

> *El Modelo de requerimientos listados en esta vista controlan la completitud y el comportamiento* del módulo de Correo Certificado. Los requerimentos incluidos en este modelo sirven como lista de chequeo frente a lo que el módulo debe tener funcionalmente (completitud funcional) y, en la fase de diseño, estos mismos requerimientos servirán para verificar (controlar) las acciones que realiza el módulo para implementarlos: comportamiento del módulo.

> El modelo de requerimientos de este módulo está alineado con las necesidades misionales de EAAB. Tos los requerimiento del modelo tienen su relación directa con las motivaciones de EAAB. Esto asegura que los esfuerzos que se realizarán en las fases posteriores (diseño e implementación) del SGDEA estén justificadas.

El modelo de requerimientos, que da tamaño al módulo del SGDEA Administración de Correo Certificado y lo valida en cuanto al qué y al cómo, está alienado con las necesidades misionales de la EAAB.


## Modelo de Requerimientos Administración de Correo Certificado


### REQR27. Firmado de correos certificados (Requirement)

**Propiedades**
|ModeloRequisitoEAAB|
|---|
|1.3.74|

Debe permitir integrarse con correo electrónico certificado y firmas digitales, para los radicados de salida digitales.


### REQR23. Garantizar la autenticidad y no repudio de los correo salientes EAAB (Requirement)

**Propiedades**
|ModeloRequisitoEAAB|
|---|
|1.3.75|

El correo certificado, físico o electrónico, puede demostrar la procedencia y vinculación con la entidad emisora EAAB. De esta manera cumple el SGDEA con el principio de no repudio de las respuestas que la entidad emite.

El SGDEA debe garantizar la vinculación del certificado de entrega con el correo electrónico automáticamente de radicado de salida digital.

### REQR20. Evitar la pérdida de correos respuestas de EAAB  (Requirement)

El correo certificado del SGDEA evita la pérdida de las respuestas ocasionadas por correos no recibidos, retrasos de las entregas, las fallas de envío ocasionadas por la infraestructura de la correspondencia, la tecnología y demás causas asociadas con la pérdida.


### REQR24. Seguimiento del envío del correo certificado (Requirement)

Las consultas de los correos certificados permiten conocer el estado de los correos que la Dependencia ha envíado, o de los correos certificados de las otras. El SGDEA aplicará los privilegios que el usuario tenga sobre la consulta.



### REQR26. Consulta web correo emitido por EAAB (Requirement)

**Propiedades**
|ModeloRequisitoEAAB|
|---|
|1.3.61|

Cuando EAAB responda un mensaje oficial, el SGDEA debe enviar al ciudadano la respuesta al correo electrónico registrado. Adicionalmente hay que publicar el mensaje en el portal oficial de la entidad, en el que, superado los niveles de acceso, el ciudadano podrá consultar la respuesta.


### REQR21. Auditoría de  entrada / salida de correos certificados (Requirement)

**Propiedades**
|ModeloRequisitoEAAB|
|---|
|1.6.21|

La solución de correo certificado deben facilitar y evidenciar, cuando sea requerido, la traza digital del correo de forma unívoca y vinculada a EAAB. La traza del correo proveerá información suficiente para demostrar que la respuesta, sea física o electrónica, se encuentra gestionada por el SGDEA.

El SGDEA debe garantizar la vinculación del certificado de entrega con el correo electrónico automáticamente, permitiendo la navegación entre ambos registros.

### REQR22. Garantizar la recepción de los correos certificados enviados EAAB (Requirement)

Envío de mensajes de correo y documentos que aseguren la recepción del destinatario. Si el correo no es recibido a conformidad, el SGDEA debe registrar el retorno del mensaje a la EAAB o a la agencia de envío. Acto seguido, dará aviso al remitente y actualizará el estado del correo en el SGDEA.


### REQR25. Validación Correo-e ciudadadano (Requirement)

**Propiedades**
|ModeloRequisitoEAAB|
|---|
|1.3.33|

El módulo debe permitir la validación del correo electrónico provisto por el ciudadano y así garantizar la existencia del mismo y garantiza la recepción de la respuesta de la EAAB.


### REQR32. Integración con Office 365 (Requirement)

**Propiedades**
|ModeloRequisitoEAAB|
|---|
|2.4.5|

Debe integrar con el correo electrónico Microsoft Office 365 para realizar automáticamente el envío de documentos y/o notificaciones y recepción de documentos a direcciones electrónicas y/o a dispositivos móviles, utilizando protocolos estándares.  


## MOT02. Mejorar el desempeño de las comunicaciones oficiales EAAB (Driver)


Mejorar el desempeño de las comunicaciones oficiales entrantes y salientes de la EAAB y al mismo tiempo las herramientas empleadas para distribuir al interior de la misma las comunicaciones.

El 74% de las dependencias encuestadas emplean CORI como aplicativo de correspondencia, el 13% emplea CORI junto al correo GEM, el 4,3% emplea CORI y Lotus, y 2 de las dependencias encuestadas no reportaron emplear ningún aplicativo. Fuente: Informe Archivístico EAAB versión 4.

En este proceso de aplicación de los controles de la correspondencia se pudo explorar y observar acerca de los medios que emplean los funcionarios para controlar la correspondencia interna que el 5% emplea planillas, el 32% una herramienta tecnológica de las mencionadas anteriormente, el 45% hace uso de bases de datos en hojas elestrónicas (Excel) y el porcentaje restante de dependencias no emplea ningún control. Fuente: Informe Archivístico EAAB versión 4.

## MOT03. Solución única para la gestión documental de la EAAB (Driver)


El uso de una aplicación única para la gestión de la correspondencia de la EAAB no es la constante y por ende intervienen diferentes aplicativos en la administración de las comunicaciones. Por esto, no es claro que la comunicación tenga un consecutivo único e irrepetible que permita hacer seguimiento a su trazabilidad durante su proceso de distribución desde su remitente hasta su destino final. Tampoco es una constante que este proceso esté gestionado por una misma aplicación, razón importante para que estos flujos de radicados de entrada y de salida y de las series conexas a la correspondencia, como los PQR, sean optimizados.

En este proceso de aplicación de los controles de la correspondencia se pudo explorar y observar acerca de los medios que emplean los funcionarios para controlar la correspondencia interna que el 5% emplea planillas, el 32% una herramienta tecnológica de las mencionadas anteriormente, el 45% hace uso de bases de datos en hojas elestrónicas (Excel) y el porcentaje restante de dependencias no emplea ningún control. Fuente: Informe Archivístico EAAB versión 4.

Hace falta de manera urgente la articulación tecnológico y procedimental que garantice que todas las comunicaciones internas y externas están gestionadas de forma unificada y centralizada más allá y potenciar el control y trazabilidad durante todo su ciclo.



[embedView]: EAAB-Correo%20Certificado.%20BMM.png