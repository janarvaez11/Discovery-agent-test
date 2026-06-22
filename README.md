# Discovery-agent-test
A Discovery agent to generate a mvp with AI

# Discovery — liberaciones_obra

Caso de prueba para Discovery Agent: gestión de liberaciones QA/QC, punch list y evidencia documental en proyectos de construcción industrial.

Problema central:
En proyectos de construcción industrial, las liberaciones de calidad, observaciones de cliente, punch list y evidencias documentales se manejan entre Excel, WhatsApp, fotos sueltas y correos, generando retrasos, retrabajo, falta de trazabilidad y bloqueos para facturar o cerrar hitos.


Carpeta sugerida dentro del repositorio:

```text
discoveries/liberaciones_obra/interviews/
discoveries/liberaciones_obra/outputs/
```

Entrevistas incluidas:

- residente_obra.md
- inspector_calidad.md
- coordinador_documental.md
- fiscalizador_cliente.md
- jefe_proyecto.md

Nota: las entrevistas son simuladas y anonimizadas para fines de prueba del agente.

# Problema Inicial 
```text
En las liberaciones de obra, la información está dispersa entre WhatsApp, correos, fotos 
sueltas, Excel, minutas y carpetas. Eso hace que nadie tenga una “foto única” del estado 
real de una liberación: producción cree que terminó, calidad tiene observaciones, 
documental no tiene respaldo completo y el cliente no aprueba. Al final, esto retrasa 
frentes de trabajo, genera retrabajo y afecta la facturación. 
```

# Reflexión. 

# ¿Qué supuesto tuyo sobre el problema cambió al revisar la evidencia real? 
```text
Al inicio pensé que el problema principal era solamente documental, es decir, que faltaba 
ordenar fotos, protocolos y respaldos al final del proyecto. Pero al revisar la evidencia 
entendí que el problema era más profundo: la falta de trazabilidad afecta el trabajo diario 
en campo, la planificación de cuadrillas, la relación con calidad, la aprobación del 
fiscalizador y hasta la facturación. No era solo un problema de “guardar archivos”, sino de 
tener un flujo único y confiable para saber qué está solicitado, observado, corregido y 
liberado. 
```
# ¿Qué fue lo más difícil de cumplir la regla de “cero invención”? 
```text
Lo más difícil fue no completar los vacíos con lo que uno cree saber del negocio. En obra es 
fácil asumir soluciones, causas o necesidades porque uno ya conoce el contexto; por 
ejemplo, pensar que hace falta un dashboard, una firma digital o un modo offline 
completo. Pero la regla de cero invención obliga a separar lo que realmente salió de las 
entrevistas de lo que solo parece lógico. Eso ayuda a que las historias, requisitos e 
hipótesis nazcan de evidencia y no de intuición. 
```
# ¿Para qué te serviría la idea de “gobernanza ejecutable” en tu trabajo? 
```text
Me serviría para convertir reglas de gestión en controles reales dentro del proceso, no solo 
en documentos o procedimientos. Por ejemplo, que un sistema no permita generar un 
MVP si no existen entrevistas suficientes, o que no deje cerrar una liberación si falta 
evidencia, responsable, fecha, aprobación o trazabilidad. En proyectos de SEDEMI, esto 
podría ayudar a asegurar que calidad, documentación, obra y cliente trabajen bajo reglas 
claras y verificables, reduciendo discusiones, retrabajo y decisiones basadas en 
información incompleta.
```