# iNGIZER

Asistente financiero IA para pymes colombianas. Diagnóstico inicial automatizado como imán de leads para vender CFO-as-a-service.

## Stack Tecnológico

- **Landing:** Netlify + Squarespace
- **Frontend/BD:** Bubble (Google OAuth, UI chat, panel, base de datos)
- **Backend:** Make.com (escenario Message_incoming)
- **IA:** Anthropic Claude Sonnet 5
- **Integraciones:** Calendly, Google Workspace

## Flujo Principal

Landing → Login Bubble → Chat IA → Análisis financiero → Popup diagnóstico (5 pestañas) → Calendly o PDF

## Estrategia Comercial

- **Target:** Pymes en Colombia
- **Propuesta:** Asistente financiero con diagnóstico inicial automatizado
- **Objetivo:** Usar diagnóstico como imán de leads para vender CFO-as-a-service
- **Cross-selling:** Posicionar PosBank dentro del diagnóstico

## Estado Actual

### Módulos Completados
- Envío de datos de registro (sector, empleados, descripción)
- Corrección de markdown en chat UI
- Verificación Meta resuelta + método de pago
- Email de notificación a clientes
- Años B1/B2 confirmados (2026/2027/2028)
- Orden cronológica de badges corregida
- CTA de descarga PDF desbloqueado
- Botón WhatsApp reubicado

### Tareas en Progreso
- Elegir entre dos CTAs de WhatsApp (ícono vs. botón grande)
- Verificar formato HTML del correo
- Probar Ramas A (startup) y C (crecimiento rápido) en producción
- Crear enlace condicional a PosBank en diagnóstico
- Eliminar 3 agentes huérfanos en Make.com

### Bloqueos Activos
- **Descarga PDF:** Usuario de prueba subió documento personal. Requiere reemplazo manual en OS
- **Facturación:** Saldo Tier 1 Anthropic expiró 12 agosto, pendiente recarga
