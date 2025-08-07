# 420-Legal 🚀🌿  
**Infraestructura legal & operativa para clubes cannábicos y servicios de compliance en México**

[![Build](https://img.shields.io/badge/build-passing-brightgreen)](#) 
[![License](https://img.shields.io/badge/license-MIT-blue)](#) 
[![Made in Sonora](https://img.shields.io/badge/made%20in-Sonora-ff69b4)](#)

> **“Cumplir hoy es más barato que litigar mañana.”**  
> — Notaría 81, Hermosillo

---

## 🧭 Visión exprés
420-Legal concentra en un solo flujo:

1. **Diagnóstico express** de riesgos regulatorios (Ley General de Salud, COFEPRIS, PLD).  
2. **Generación automática** de documentos (acta constitutiva, contrato social, reglamento interno, avisos de privacidad, KYC, AML).  
3. **Pasarela de pago híbrida**:  
   - *Fiat* ➡️ Depósito/transferencia a **Banregio 850896380013 / CLABE 058760000148957666**.  
   - *Crypto* ➡️ Bitso SPEI 710969000016468465 (u otra wallet dinámica con QR).  
4. **Entrega digital** de PDFs firmados / hash-anclados (NOM-151 opcional).  
5. **Booking** de cita notarial + anticipo mínimo MX$ 1,500 garantizado.

Todo auditado, sin fricción, listo para escalar.

---

## ⚖️ Alcance legal & disclaimer
- Este repositorio es **código de referencia**. No constituye asesoría jurídica individual.  
- El uso debe alinearse a la **normativa mexicana vigente**; el equipo recomienda validación con un notario o abogado especializado en cada caso.  
- **Authority & Escasez:** Notaría 81 (Hermosillo) habilita únicamente **10 cupos mensuales** para protocolización prioritaria. Reserve con anticipación.  

---

## 🛠️ Stack principal
| Capa | Tecnología | Función |
|------|------------|---------|
| Frontend | **Famous.ai** / Next.js / Tailwind CSS | Landing, onboarding y UI |
| Backend | **Supabase** (PostgreSQL & Auth) | API, roles, almacenamiento seguro |
| Workflows | **Make** scenarios | Automatización de PDFs + email + Slack alerts |
| Pagos Fiat | **Stripe** / Webhook personalizado | Conversión MXN, conciliación contable |
| Pagos Crypto | **Bitso API** / ethers.js | Wallet dinámica + verificación de fondos |
| Firmas & Hash | **Mifiel** (soon) + SHA-256 | Firma electrónica & seeding NOM-151 |
| Infra | Vercel / Render | CI/CD, autoscaling |

---

## ⚡ Quick Start (dev)

```bash
git clone https://github.com/tu-usuario
