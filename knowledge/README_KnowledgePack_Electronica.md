# ⚡ Knowledge Pack – Ingeniería Industrial (Sector Electrónica)

## 🎯 Propósito
Este paquete provee documentación base para entrenar un **Asistente de Ingeniería Industrial** especializado en plantas de montaje electrónico.  
Los archivos incluidos sirven como **referencia estática** dentro del *Knowledge* del GPT, aportando contexto técnico, estándares y ejemplos reales de mejora continua.

> 💡 Ideal para proyectos de OEE, SMED, 5S, TPM, Kaizen y análisis de rendimiento.

---

## 📂 Estructura del paquete

| Archivo | Tipo | Descripción |
|----------|------|-------------|
| **Manual_OEE.pdf** | PDF | Fórmulas, ejemplos y umbrales de OEE en líneas SMT y test. |
| **Template_OEE.csv** | CSV | Dataset sintético de 3 líneas (A/B/C) para cálculos de OEE. |
| **Procedimiento_SMED.pdf** | PDF | Pasos y mejores prácticas de cambio rápido en líneas electrónicas. |
| **Checklist_5S.pdf** | PDF | Auditoría 5S adaptada a áreas de ensamble, test y oficina técnica. |
| **Diccionario_Metricas_Industriales.md** | Markdown | Glosario técnico con definiciones de OEE, MTTR, MTBF, Yield, Scrap, FPY, etc. |
| **Plantilla_Informe_Industrial.md** | Markdown | Formato estándar para informes ejecutivos y técnicos. |
| **Ejemplos_Acciones_Kaizen.pdf** | PDF | 10 acciones reales clasificadas por esfuerzo e impacto. |

---

## 🧠 Uso en tu GPT personalizado

1. **Subí todos los archivos** al apartado **Knowledge** dentro del GPT Builder.  
2. En las **Instrucciones (Instructions)**, indicá algo como:  
   > “Usá los documentos del Knowledge como referencia técnica al generar informes, definiciones o planes de acción.”  
3. Activá las herramientas necesarias:  
   - **Code Interpreter** → para cálculos y análisis de CSV.  
   - **File Uploads** → para leer datasets de planta.  
   - **Browsing** (opcional) → para búsquedas externas.  
4. Probá con estos prompts iniciales:  
   - “Calculá el OEE del turno A usando el archivo Template_OEE.csv.”  
   - “Generá un informe industrial usando la plantilla estándar.”  
   - “Sugerí 5 acciones Kaizen de alto impacto.”  
   - “Explicá qué significa MTBF según el diccionario de métricas.”  
   - “Auditá el área de test con la checklist 5S.”  

---

## 🧩 Integración con tu flujo de trabajo
Podés mantener este contenido sincronizado en un repo GitHub:

```
knowledge/
 ├── Manual_OEE.pdf
 ├── Template_OEE.csv
 ├── Procedimiento_SMED.pdf
 ├── Checklist_5S.pdf
 ├── Diccionario_Metricas_Industriales.md
 ├── Plantilla_Informe_Industrial.md
 ├── Ejemplos_Acciones_Kaizen.pdf
 └── README_KnowledgePack_Electronica.md
```

> Recomendado: agregar un script simple en tu pipeline de CI/CD o GitHub Action que verifique versiones y consistencia del Knowledge Pack.

---

## 📈 Próximas extensiones sugeridas

- 📘 **Manual TPM.pdf:** mantenimiento autónomo y preventivo.  
- 📗 **Guía de VSM:** mapeo de flujo de valor con ejemplos reales.  
- 📙 **Dataset de tiempos SMED (CSV):** base para entrenar regresiones o comparativas.  
- 📒 **Historial Kaizen.xlsx:** registro de acciones y seguimiento de impacto.

---

## 🔒 Buenas prácticas
- No incluir datos confidenciales (nombres, clientes, series, costos).  
- Usar solo ejemplos genéricos o anonimizados.  
- Actualizar el contenido cada 6–12 meses con métricas y procesos revisados.  

---

### ✍️ Autor
**Lic. Gonzalo de Cos**  
Especialista en QA, automatización y mejora continua.  
📍 AArEII – Revolución IA: Prompt & Context Engineering para Ingenieros  
🗓️ Versión 1.0 – Noviembre 2025

---

> 🧾 *Este Knowledge Pack puede redistribuirse y modificarse libremente bajo licencia CC BY 4.0.*
