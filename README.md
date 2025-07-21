# BP SmartBank - Documentación Arquitectónica

Este repositorio contiene la documentación para el desarrollo de una solución de banca digital segura, moderna y conforme con la normativa ecuatoriana vigente. 

## Nombre del sistema: **BP SmartBank**.

---

## 📄 Contenido

### Documento PDF
- `Caso_practico_BP_SmartBank_Arquitectura.pdf`
  - Diagramas del modelo C4 (Contexto, Contenedor, Componente)
  - Justificaciones técnicas y normativas
  - Patrones de diseño utilizados
  - Cumplimiento de normativas ecuatorianas (LOPDP, Habeas Data) e internacionales (ISO/IEC 27001)

### Diagramas en PNG
- `Contexto.drawio.png`
- `Contenedores.drawio.png`
- `Componente-Movimientos.drawio.png`
- `Componente-Transferencias.drawio.png`
- `Componente-DatosCliente.drawio.png`
- `Componente-Auditoria.drawio.png`
- `Componente-Preferencias.drawio.png`
- `Componente-Notificaciones.drawio.png`
- `Componente-Onboarding.drawio.png`

---

## ⚖️ Normativas consideradas

- **Ley Orgánica de Protección de Datos Personales (LOPDP, Ecuador)**
- **ISO/IEC 27001** – Gestión de Seguridad de la Información
- **AWS Well-Architected Framework + Azure Secure Design**
- Principios de consentimiento, minimización, finalidad y trazabilidad

---

## 🧱 Arquitectura adoptada

- Patrón de **Arquitectura Hexagonal** (Ports and Adapters)
- Microservicios desarrollados con **Spring Boot**
- Autenticación segura: **OAuth2 + PKCE**
- Comunicación asíncrona: **SNS/SQS, Azure Service Bus**
- Persistencia: **MySQL, Redis (ElastiCache), DynamoDB, S3**
- Observabilidad: **AWS CloudWatch**, monitoreo distribuido

---

## 📘 Observaciones

- Este repositorio es parte de un **ejercicio** de arquitectura de software.
- No contiene código funcional, únicamente diseño y documentación.

---


