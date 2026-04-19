# Dashboard Specification
## Arquitectura de Información — MVP

Two views for two distinct user types. Same data, different hierarchy.

---

### Vista 1: "The Mayor's Cockpit" — B2G (Gobierno / Alcaldías)

**User:** Alcalde or public official. Decision-maker, not a data analyst.

**Primary KPIs (large, prominent):**
- Hectáreas Mapeadas
- Riesgo Mitigado (%)
- Presupuesto Ejecutado
- Familias Beneficiadas

**Central Map:** Municipal view with heat layers.
- Red zone = Risk / Deforestation threat
- Green zone = Opportunity / Regeneration progress

**Primary CTA:** `[ Generar Reporte de Inversión ]`

---

### Vista 2: "The Exporter's Audit" — B2B (Sector Privado / Exportadores)

**User:** Supply chain manager or compliance officer at a coffee export company.

**Primary KPIs:**
- Productores Verificados
- Volumen EUDR Compliant (Sacos)
- Créditos de Carbono Generados

**Data Table:** Filterable lot list.
- Green row = Aprobado / EUDR Compliant
- Red row = Riesgo Deforestación detected

**Primary CTA:** `[ Emitir Certificado QR ]`

---

### Design Principles for Both Views

- Follow the Satellite Precision aesthetic — dark mode, neon data accents.
- KPI numbers use the large display typescale (Inter Black, 48px+).
- Map base: Mapbox Dark Matter style.
- Status indicators: Signal Green (pass) / Alert Orange (attention) / Red (fail).
