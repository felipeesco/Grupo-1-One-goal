# 08 · Validación

## 1. Métodos de testeo Lean UX

| Método | Qué valida | Cómo se aplica | Ventaja | Limitación | ¿Aplica a nuestro prototipo? |
|---|---|---|---|---|---|
| Prueba de usabilidad | Si el usuario logra completar tareas concretas con el producto y dónde se confunde | Le pedimos a una persona que realice tareas reales con el prototipo mientras la observamos y registramos sus comentarios | Muestra errores y dudas reales de uso con pocos participantes | Requiere preparar tareas y un prototipo que funcione | **Sí.** Nuestra página ya permite registrar el apartado, conectar la billetera y pagar |
| Mago de Oz | Si la idea tiene valor antes de construirla, simulando manualmente las funciones que aún no existen | Una persona del equipo opera "detrás de cámaras" y el usuario cree que el sistema funciona solo | Permite probar ideas sin desarrollar la tecnología completa | Exige trabajo manual y no mide el desempeño real del sistema | No. Nuestro prototipo ya funciona con la billetera y el contrato inteligente en red de prueba |
| Test A/B | Cuál de dos versiones de una pantalla o función funciona mejor | Mostramos dos versiones a grupos distintos y comparamos una métrica | Da datos comparables para decidir entre alternativas | Necesita dos versiones y muchos usuarios para ser confiable | No. Tenemos una sola versión y un solo participante |
| Prueba de 5 segundos | Si la primera impresión de una pantalla comunica con claridad su propósito | Mostramos una pantalla durante cinco segundos y preguntamos qué recuerda y entiende el usuario | Es rápida y barata, y sirve para evaluar mensajes y jerarquía visual | Solo evalúa la primera impresión, no el uso completo | Parcial. Serviría para la pantalla de registro, pero no valida el pago |
| Puerta falsa | Si existe interés real en una función antes de construirla | Publicamos un botón o anuncio de una función inexistente y medimos cuántas personas lo usan | Mide interés con poco esfuerzo | No valida si la solución funciona ni si es fácil de usar | No. Ya construimos la función y queremos validar su facilidad de uso, no el interés |

## 2. Método elegido

Elegimos la **prueba de usabilidad moderada y remota**.
Nuestra hipótesis trata de si recibir el pago del apartado resulta fácil y se logra sin ayuda, y esto solo se comprueba observando a una persona usar la página.
El prototipo ya es funcional en red de prueba, así que podemos observar el flujo completo de registro, conexión de la billetera y pago.

## 3. Plan de testeo

| Elemento | Detalle |
|---|---|
| **Hipótesis** | Creemos que el asesor comercial de Abitare podrá recibir el pago del apartado de un inmueble de forma más fácil si usa una página donde el cliente paga con criptomonedas desde su billetera y el pago queda registrado en un contrato inteligente. |
| **Participante** | La dueña del negocio de Abitare Propiedad Raíz, quien realiza las tareas desde el rol de quien recibe y verifica el pago del apartado. |
| **Tarea 1** | Registrar un apartado con los datos del cliente, el inmueble y el valor del apartado. |
| **Tarea 2** | Conectar la billetera (tipo MetaMask) a la página en la red de prueba. |
| **Tarea 3** | Realizar el pago del apartado y comprobar que quedó confirmado y registrado. |
| **Métrica de éxito** | La participante completa las 3 tareas sin ayuda del equipo, en un máximo de 10 minutos en total, y califica la facilidad de uso con 4 o más en una escala de 1 a 5. |
| **Lugar** | Videollamada por Microsoft Teams, con pantalla compartida. |
| **Fecha** | 5 de noviembre de 2026. |
| **Materiales** | Enlace a la página web del prototipo; billetera tipo MetaMask con fondos de prueba en la red de prueba; guion de las tareas; hoja de observación; breve cuestionario final; grabación de la sesión en Teams. |

**Responsables por rol**

| Rol | Responsabilidad |
|---|---|
| Facilitador/a | Explica el objetivo, pide autorización para grabar, entrega las tareas y hace las preguntas finales sin sugerir respuestas. |
| Observador/a | Registra en la hoja de observación errores, dudas, tiempos y si necesitó ayuda. |
| Responsable técnico | Deja listos el prototipo, la billetera y los fondos de prueba, y resuelve fallas de conexión durante la sesión. |
| Responsable de registro y video | Graba la sesión, guarda las notas con las frases textuales y edita el video de resultados. |

## 4. Resultados

### Qué observamos

### Qué dijo el usuario

### Qué vamos a cambiar

Video: [ENLACE]

