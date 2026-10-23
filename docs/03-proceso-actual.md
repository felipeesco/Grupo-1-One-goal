Proceso actual <br>
1. BPMN de práctica <br>
![BPMN de práctica](BPMN_PRACTICA#3.png) <br>
Declaración de IA: <br>
[herramienta y versión] – [dd/mm/aaaa] – prompt registrado en docs/11-uso-ia.md <br>
<br>
2. El proceso elegido <br>
Nombre del proceso: Cobro del apartado de un inmueble en Abitare, desde que el cliente decide separarlo hasta que el asesor confirma que el pago llegó. <br>
Carriles (responsables): Cliente y Asesor comercial. <br>
Fuente (contacto, cargo y fecha): Asesor comercial de Abitare, familiar de la dueña de la inmobiliaria – [19/10/26]<br>
<br>
3. Pasos del proceso <br>
# | Paso (verbo + objeto) | Responsable |<br>
1 | [Decidir separar el inmueble] | [cliente] |<br>
2 | [Hacer la transferencia bancaria del apartado] | [cliente] |<br>
3 | [Enviar el comprobante por WhatsApp] | [cliente] |<br>
Decisión: [¿El pago llegó?]Sí: [Tarea si Sí]. Confirmar el apartado al cliente.No:Pedir de nuevo el comprobante. [Tarea si No]. <br>
<br>
4. Diagrama BPMN <br>
![BPMN proceso actual](../assets/bpmn-actual.png) <br>
Archivo editable: [bpmn-actual.bpmn](../assets/bpmn-actual.bpmn) <br>
<br>
5. Puntos críticos <br>
PC | Qué pasa (se demora, se repite o se pierde) | Evidencia (dato o frase del contacto, con fecha) |<br>
PC1 | [Se demora:] | [el asesor revisa a mano cada comprobante que llega por WhatsApp y la reserva queda en espera. <br>
PC2 | [Se repite:] | [como el inmueble no queda bloqueado mientras se verifica el pago, se puede ofrecer a dos clientes.] |<br>
<br>
6. Uso de IA <br>
| Herramienta y versión | Fecha | Prompt |
|---|---|---|
| Claude Opus 5.5 (Anthropic) | 23/10/2026 | "Actúa como analista de procesos. A partir de esta descripción del proceso de Abitare (cobro del apartado con transferencia bancaria y comprobante por WhatsApp), genera un diagrama BPMN 2.0 con carriles por responsable, eventos de inicio y fin, tareas y compuertas. Entrega el resultado en XML BPMN para importarlo en bpmn.io." |
