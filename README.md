# Patrimonio v1.2.0 — Memoria y Motor de Decisiones

- Reglas financieras personales editables.
- Memoria local persistente del asesor.
- Conversación conservada entre sesiones.
- Motor de cálculos: reserva mínima, gastos, tasa de ahorro, impacto de compras y proyección de objetivos.
- Modo Decisión con opciones conservadora, equilibrada y flexible.
- Diario local de decisiones.
- Mantiene la clave de datos `patrimonio_nuevo_v1`.

# Patrimonio v1.1.2 — Corrección de conexión IA

- Corrige el lector de eventos SSE del chat: ahora interpreta correctamente los saltos de línea enviados por Cloudflare.
- No cambia saldos, movimientos, subcuentas ni objetivos.
- Mantiene el mismo Worker y la misma URL.

# Patrimonio v1.1.1 — Correcciones de movimientos

- La X de ingresos, gastos y paga cierra correctamente el formulario.
- Los ingresos y gastos pueden registrarse directamente en Disponible o en cualquier subcuenta.
- En una subcuenta se elige además si el dinero pertenece a Revolut o a efectivo.
- El historial y el CSV muestran la subcuenta utilizada.

# Patrimonio v1.1.0 — Asesor IA conectado

- Chat integrado con Cloudflare Workers AI.
- Envía únicamente un resumen financiero al hacer una pregunta.
- Historial reciente local y respuestas en streaming.
- No modifica ni borra los datos guardados.

# Patrimonio v1.0.1 — icono y migración

- Nuevo icono negro y dorado.
- Icono específico para iPhone.
- Recuperación automática de saldos, subcuentas y movimientos de la app anterior cuando la nueva está vacía.

# Patrimonio — nueva base estable v1.0.0
Reconstruida desde cero. Incluye Revolut, efectivo, subcuentas con origen, movimientos, objetivos, biblioteca, asesor local, exportación CSV, copias JSON, modo oscuro y PWA.
