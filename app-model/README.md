# Jivo Mart App-Model — Knowledge Base

Deep per-section study of the `factory.jivo.in` factory app, scoped to the **Jivo Mart (JIVO_MART)** tenant only. Live-verified 2026-06-30.

**Essence:** `factory.jivo.in` is a factory-floor operating system and SAP Business One companion, multi-tenant across Jivo Oil (manufacturer), Jivo Beverages, and Jivo Mart. For **Jivo Mart — the retail/dispatch arm** — it runs as a finished-goods receiving-and-dispatch hub: pre-barcoded cartons arrive from Jivo Oil over an intercompany rail, are held/relayed across 31 warehouses, then scanned onto trucks and gated out against SAP invoices. Gate, vehicle, barcode, dispatch and WMS-read are data-rich; production (MES), maintenance (CMMS), inbound-QC and GRPO-posting are built but largely dormant.

**Start here:**
- [00-OVERVIEW](00-OVERVIEW.md) — whole-app model: factory flow, section map, cross-section data graph, SAP-B1 integration, heavy-vs-idle analysis
- [_route-map](_route-map.md) — UI route tree per section

## Sections
- [Admin](sections/01-admin.md)
- [Dashboards](sections/02-dashboards.md)
- [Dispatch](sections/03-dispatch.md)
- [Gate](sections/04-gate.md)
- [Vehicle Management](sections/05-vehicle-management.md)
- [Quality Control](sections/06-quality-control.md)
- [GRPO](sections/07-grpo.md)
- [Production](sections/08-production.md)
- [Maintenance](sections/09-maintenance.md)
- [Warehouse](sections/10-warehouse.md)
- [WMS](sections/11-wms.md)
- [Barcode](sections/12-barcode.md)
- [Notifications](sections/13-notifications.md)
