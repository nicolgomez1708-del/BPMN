Ejemplo 1 – RF-001.1: Registro de Participantes (Versión en Texto)

Este proceso describe el flujo mediante el cual el Personal Administrativo registra un nuevo participante en el sistema TITAN-ES, verificando previamente la unicidad del documento.

El proceso inicia cuando el Personal Administrativo, habiendo iniciado sesión, accede al módulo de registro de participantes. Desde el carril del sistema, TITAN-ES solicita los datos personales necesarios, tales como nombres, documento y contacto. El Personal Administrativo introduce la información requerida, tras lo cual el sistema valida el formato de los datos y verifica que no exista un participante previamente registrado con el mismo número de documento.

Se ejecuta un gateway exclusivo donde el sistema determina si la validación fue exitosa y si no existe duplicidad. Si la respuesta es afirmativa, el sistema almacena la información del nuevo participante y posteriormente muestra una confirmación del registro exitoso. Si la validación falla o existe duplicidad, el flujo retorna al Personal Administrativo para que corrija o resuelva el inconveniente. El proceso finaliza cuando el sistema deja almacenada la información del participante.

Ejemplo 2 – RF-002.1: Proceso de Cierre Mensual y Generación de Certificados (Versión en Texto)

Este proceso representa el flujo automatizado que se ejecuta al finalizar cada mes para consolidar la información y generar certificados oficiales.

El proceso comienza cuando el Personal Administrativo inicia el cierre mensual, teniendo como precondición que el mes haya finalizado y que los cursos estén completamente calificados. Una vez iniciado, el sistema identifica todos los participantes que aprobaron cursos durante ese mes. Posteriormente, el sistema genera los certificados individuales de alturas para cada participante aprobado, asegurando que estos documentos sean imprimibles.

Después de la generación, el sistema almacena digitalmente cada certificado y lo asocia al participante correspondiente. Una vez finalizado el procesamiento, el sistema notifica al Personal Administrativo que el cierre mensual ha concluido. El proceso termina con la confirmación de que el cierre y la generación de certificados han sido completados (prioridad MUST).

Ejemplo 3 – RF-001.4: Registro y Gestión de Incidentes (Versión en Texto)

Este proceso describe el flujo mediante el cual el Personal Administrativo registra de forma formal un incidente ocurrido en el centro de entrenamiento.

El proceso inicia cuando ocurre un incidente que requiere ser documentado. El Personal Administrativo accede al módulo de registro de incidentes y el sistema solicita información detallada, incluyendo fecha, hora, descripción del evento y personas involucradas. El Personal Administrativo introduce todos los datos requeridos para el registro.

El sistema valida la coherencia de la información ingresada y, una vez confirmada, almacena el registro formal del incidente, incluyendo fecha y hora del evento. El proceso finaliza cuando el sistema confirma que el incidente ha sido registrado y almacenado exitosamente.

Ejemplo 4 – RF-002.4: Impresión de Certificados por Participantes (Versión en Texto)

Este proceso describe el mecanismo de autoservicio mediante el cual un participante accede y puede imprimir su certificado, bajo un acceso altamente restringido.

El proceso inicia cuando el participante, habiendo finalizado y aprobado un curso cuyo certificado ya fue generado, accede a la sección de certificados dentro del portal de autoservicio. El sistema solicita el número de documento como método de autenticación básica basado en identificación. El participante introduce su número de documento y el sistema valida su identidad para luego buscar el certificado asociado.

En un gateway exclusivo, el sistema determina si existe un certificado válido y aprobado. Si la búsqueda es exitosa, el sistema muestra el certificado correspondiente para su previsualización y el participante puede enviarlo a impresión directamente desde la plataforma. Si no se encuentra el certificado o el participante no cumple las condiciones, el sistema muestra un mensaje de error o inexistencia. El proceso finaliza con la visualización o impresión del certificado.