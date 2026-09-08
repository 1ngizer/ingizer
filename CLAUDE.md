# Contexto del Proyecto — iNGIZER

## Qué es
Asistente financiero IA para pymes colombianas. El flujo es: Landing → Login Bubble → Chat IA → Análisis financiero → Popup diagnóstico (5 pestañas) → Calendly o descarga PDF.

## Stack
- Frontend/BD: Bubble (Google OAuth, UI chat, panel)
- Backend: Make.com (escenario Message_incoming)
- IA: Anthropic Claude Sonnet 5
- Landing: Netlify + Squarespace
- Integraciones: Calendly, Google Workspace

## Prioridades actuales
1. Recargar saldo Tier 1 Anthropic (expiró 12 agosto)
2. Probar Ramas A (startup) y C (crecimiento rápido) en producción
3. Crear enlace condicional a PosBank en diagnóstico (cross-selling)

## Resuelto
- ~~Bloqueo descarga PDF~~ — Resuelto (septiembre 2026)

## Convenciones
- Idioma del código y commits: español para documentación, inglés para código
- El proyecto usa Make.com como orquestador, no código backend tradicional
- Panel de tareas centralizado: https://claude.ai/code/artifact/096d4e8a-4a2b-449b-be95-6597f62dd70f
