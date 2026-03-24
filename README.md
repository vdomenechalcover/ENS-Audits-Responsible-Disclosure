<div align="center">
  <h1>🛡️ Auditorías ENS y Divulgación Responsable</h1>
  <p><em>Casos de estudio técnicos sobre identificación de vulnerabilidades, Threat Hunting y reporte ético en infraestructuras críticas.</em></p>
</div>

## 📌 Propósito de este repositorio
Este repositorio documenta la metodología técnica aplicada durante auditorías de seguridad a diversas Administraciones Públicas en el marco del **Esquema Nacional de Seguridad (ENS)**. 

El objetivo es demostrar el ciclo completo de una auditoría defensiva: desde el reconocimiento y la explotación controlada, hasta el *Threat Hunting* de intrusiones de terceros y la gestión del incidente bajo protocolos de **Responsible Disclosure**.

> ⚠️ **AVISO DE CONFIDENCIALIDAD (TLP:RED):** Todos los informes, direcciones IP, nombres de dominio y referencias institucionales presentes en este repositorio han sido rigurosamente **anonimizados**. Los datos mostrados son representaciones sanitizadas para cumplir con los estrictos acuerdos de confidencialidad y la ética profesional.

## 📂 Índice de Casos de Estudio

| ID | Vector Principal | Hallazgos Técnicos | Estado de Mitigación |
| :--- | :--- | :--- | :--- |
| **[Caso 1: RCE & Threat Hunting](./Caso_1_RCE_Kinsing/)** | RCE (CVE-2017-5638) en Apache Struts2 | Detección de botnet Kinsing (Criptominería) activa al 111% CPU. Extracción de IoCs. | 🟢 Parcheado tras reporte al DPD. |
| **[Caso 2: WAF Bypass & SQLi](./Caso_2_SQLi_Smuggling/)** | Evasión HTTP Request Smuggling y SQLi | Acceso a BD mediante Time-Based Blind SQLi. Enumeración de directorios y backups expuestos. | 🟢 Mitigado tras reporte al DPD. |
| **[Caso 3: Fuga de Sesiones](./Caso_3_Session_Leakage/)** | Session Leakage & Parameter Pollution | Secuestro de sesiones vía URI (GET) y exposición de la topología interna de la DMZ (HPP). | 🟢 Parcheado tras reporte al DPD. |

---
*Víctor Doménech Alcover - Auditor de Ciberseguridad & Desarrollador Web Asistido por IA*
