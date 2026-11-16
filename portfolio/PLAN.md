# Organización del portafolio DigitalSoft RD
Propuesta editorial · 16 de noviembre de 2026

## Diagnóstico
La cuenta conectada es yordyn71. La consulta devuelve dos repositorios públicos accesibles: yordyn71 (perfil, rama main) y holamundo (rama readme-edist). El README del perfil contiene la presentación inicial en inglés y campos sin completar. No se verificó la fecha de su última actualización ni se asume que esta lista incluya repositorios fuera del acceso de la integración.

## Repositorios propuestos y orden
Los nombres siguientes son propuestas; no son repositorios creados ni enlaces activos.

| Orden | Nombre | Visibilidad recomendada | Contenido inicial |
| --- | --- | --- | --- |
| 1 | yordyn71 | Público, existente | README profesional del perfil. |
| 2 | digitalsoft-alquileres | Público, escaparate | Ficha Windows, capturas con datos ficticios y alcance de la edición revisada. |
| 3 | digitalsoft-inventario | Público, escaparate | CRUD de productos y demostración con datos ficticios. |
| 4 | digitalsoft-alquileres-web | Público, escaparate | Alcance local documentado y límites; identificar la versión antes de añadir funciones. |
| 5 | digitalsoft-excel-portafolio | Público, ejemplos nuevos | Casos de ventas y cuentas por cobrar construidos con datos sintéticos. |

Separar el código comercial en repositorios privados, por ejemplo digitalsoft-alquileres-source, digitalsoft-inventario-source y digitalsoft-alquileres-web-source. Crear los repositorios privados solo cuando se haya elegido y revisado la versión que se importará. No cambiar automáticamente la visibilidad del código comercial.

Prioridad: Alquileres permite mostrar el avance comercial reportado; Inventario ofrece un caso técnico acotado; Web necesita reconciliar la documentación v0.2 con la edición posterior antes de presentarse como versión actual. Excel complementa el perfil cuando existan ejemplos publicables.

## Estructura de cada escaparate
- README.md: problema, público objetivo, funciones verificadas, estado y límites.
- docs/ALCANCE.md: versión de referencia y funciones comprobadas.
- docs/DEMO.md: pasos de una demostración reproducible con datos ficticios.
- assets/: capturas reales revisadas, sin nombres, cédulas ni cuentas reales.

Para repositorios privados de código, conservar la estructura real del proyecto. Añadir instrucciones de ejecución, pruebas y un .gitignore adaptado después de inspeccionarlo; no inventar carpetas src o tests que puedan no existir.

## Contenido preparado
Las fichas en borradores/ son textos iniciales para futuros README. No incluyen enlaces a repositorios inexistentes, capturas simuladas, precios, credenciales ni un contacto comercial no confirmado.

Bio propuesta: “Desarrollo software de gestión en DigitalSoft RD | C#, Node.js y bases de datos | Excel y análisis de datos | República Dominicana”.
No se modificó la bio de la cuenta.

Destacados propuestos: Alquileres, Inventario, Alquileres Web y ejemplos Excel, cuando estén publicados. Mantener holamundo como antecedente de aprendizaje, sin destacarlo como producto. No se elimina ni archiva.

## Evidencia y límites
- Perfil: README y repositorios leídos mediante la cuenta GitHub conectada el 16/11/2026.
- Alquileres Windows: confirmación del usuario de funcionamiento mediante instalador en Windows; no se volvió a ejecutar aquí.
- Inventario: avance previo reportado de conexión SQL Server y CRUD de productos; no se inspeccionó ni ejecutó el proyecto en esta revisión.
- Alquileres Web: lectura de README(3).md y PRUEBAS_0_2.md. La documentación describe Node.js, JavaScript y SQLite, ejecución local y 15 pruebas aprobadas en una ejecución histórica. No acredita TypeScript implementado, SaaS público ni pruebas ejecutadas hoy.
- Hay referencias a entregas comerciales posteriores; no se revisaron sus archivos en esta tarea. No atribuirles automáticamente el alcance o las pruebas de v0.2.
- Excel: experiencia previa de trabajo; todavía no hay un ejemplo sintético validado para publicar.

## Secuencia para publicar proyectos
1. Elegir el paquete y versión exactos de cada producto.
2. Revisar el código y documentación de esa versión y ejecutar sus comprobaciones.
3. Crear capturas y una demo con datos ficticios.
4. Publicar la ficha correspondiente y enlazarla desde el perfil.
5. Fijar los proyectos destacados y completar un canal de contacto comercial confirmado.

No subir bases de clientes, claves de activación, respaldos, contraseñas ni los paquetes privados del vendedor. Las fichas de portafolio no conceden una licencia de uso o redistribución del software. La licencia comercial se define por separado.
