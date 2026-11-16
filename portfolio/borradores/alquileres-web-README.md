# DigitalSoft RD — Alquileres Web
Aplicación de gestión de alquileres desde el navegador.

## Versión de referencia
Esta ficha describe exclusivamente la **v0.2 documentada**. No establece que sea la última versión del producto. Antes de publicar, contrastar la ficha con la versión elegida.

## Tecnologías documentadas
Node.js, JavaScript y SQLite. La documentación consultada no acredita una implementación en TypeScript.

## Alcance documentado en v0.2
- Propiedades, inquilinos, contratos, cuotas, cobros y recibos.
- Renovaciones vinculadas al contrato anterior, con validación de solapamientos.
- Movimientos de depósitos, separados de los ingresos por alquiler.
- Adjuntos cifrados con acceso administrativo.
- Respaldos cifrados mediante herramienta de terminal y restauración en una carpeta nueva.

## Entorno y límites
Uso local en 127.0.0.1. No se presenta como SaaS público ni como despliegue listo para Internet.
La edición web no sincroniza datos automáticamente con Windows.
La documentación v0.2 deja pendientes exportaciones PDF/Excel nativas, importación desde Windows y gestión multiempresa.

## Validación documentada
PRUEBAS_0_2.md registra 15 pruebas aprobadas el 7 de noviembre de 2026. Es evidencia histórica, no una ejecución realizada durante la preparación de esta ficha. No equivale a una auditoría de seguridad.

Este escaparate no contiene el código ni ofrece una demo alojada. Las instrucciones de instalación se incorporarán cuando se seleccione un paquete publicable.
