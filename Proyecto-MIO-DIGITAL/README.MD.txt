# Taller Integrador — Ingeniería de Software

## Sistema desarrollado

Sistema de recarga digital MIO, el cual permite a los usuarios recargar saldo a su tarjeta física desde una aplicación móvil, así como realizar pagos mediante tarjeta virtual en dispositivos con tecnología NFC.

## Integrantes

* Juan Izquierdo

## Descripción del sistema

El sistema permite a los usuarios registrarse, iniciar sesión, consultar saldo y recargar su tarjeta MIO de forma digital.

La funcionalidad principal del sistema es la recarga de la tarjeta física, la cual se realiza a través de la aplicación y se activa de manera virtual. Como funcionalidad secundaria, el sistema permite el uso de una tarjeta virtual para pagos mediante tecnología NFC.

El proceso incluye la interacción con una pasarela de pago, validación de la transacción y notificación del resultado (éxito o error).

## Decisiones de diseño

* Se definió la recarga de tarjeta física como funcionalidad principal del sistema.
* Se incluyó el uso de tarjeta virtual como funcionalidad secundaria para pagos con NFC.
* Se modeló el sistema separando claramente los roles de usuario, sistema y pasarela de pago.
* Se contemplaron escenarios de éxito y error en todos los diagramas.
* Se mantuvo coherencia entre historias de usuario, casos de uso, diagramas de secuencia, BPMN y mockups.

## Estructura del proyecto

/historias-usuario/
/casos-de-uso/
/secuencia/
/bpmn/
/mockups/
/adicionales/

README.md

## Observaciones

Todos los artefactos desarrollados mantienen coherencia entre sí, garantizando trazabilidad desde las historias de usuario hasta la representación visual del sistema en los mockups.

El proyecto fue construido siguiendo las buenas prácticas de modelado vistas en el curso, asegurando consistencia, claridad y correcta aplicación de las notaciones.
