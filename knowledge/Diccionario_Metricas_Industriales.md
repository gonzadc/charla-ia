# ⚙️ Diccionario de Métricas Industriales – Planta Electrónica

Este glosario define los principales indicadores utilizados en plantas de montaje, test y ensamblado electrónico.  
Debe utilizarse como referencia estándar para interpretación, cálculo y comparación de resultados productivos.

---

## 📊 Indicadores de desempeño

**OEE (Overall Equipment Effectiveness)**  
Mide la eficiencia global de un equipo o línea, combinando:
- **Disponibilidad:** cuánto tiempo estuvo efectivamente produciendo.  
- **Rendimiento:** velocidad de producción respecto al ideal.  
- **Calidad:** proporción de productos buenos sobre el total.  
> Fórmula: OEE = Disponibilidad × Rendimiento × Calidad

**Disponibilidad**  
Porcentaje de tiempo útil frente al tiempo planificado.  
> Ejemplo: 380 min operativos sobre 440 min planificados → 86.4%

**Rendimiento**  
Compara la velocidad real contra la velocidad teórica.  
> Ejemplo: 920 placas × 2 s/placa / 380 min = 84%

**Calidad**  
Porcentaje de piezas que cumplen especificaciones sin retrabajo.  
> Ejemplo: 880 buenas / 920 totales = 95.6%

---

## 🧮 Métricas de mantenimiento

**MTTR (Mean Time To Repair)**  
Tiempo promedio que se tarda en reparar una falla desde que ocurre hasta que se restablece la producción.  
> Ideal: MTTR < 20 minutos en líneas críticas.

**MTBF (Mean Time Between Failures)**  
Tiempo promedio entre una falla y la siguiente. Indica confiabilidad del equipo.  
> Ideal: MTBF > 2000 minutos en máquinas SMT.

**Downtime (tiempo de paro)**  
Tiempo durante el cual un equipo no está disponible para producir. Incluye fallas, setups y microparadas.

---

## 📈 Métricas de calidad

**Yield**  
Porcentaje de unidades buenas respecto al total procesado.  
> Yield = Buenas / Totales

**Scrap**  
Cantidad o porcentaje de unidades defectuosas o fuera de especificación que no pueden recuperarse.  
> Scrap = (Defectuosas / Totales) × 100

**Rework Rate**  
Porcentaje de piezas que necesitan retrabajo para cumplir especificación.

**First Pass Yield (FPY)**  
Porcentaje de unidades que pasan la prueba a la primera, sin retrabajo.  
> FPY = (Buenas sin retrabajo / Totales) × 100

---

## ⚡ Métricas de flujo y capacidad

**Cycle Time (Tiempo de ciclo)**  
Tiempo que demora en fabricarse una unidad desde inicio a fin.  
> Incluye procesamiento y esperas.

**Throughput (Rendimiento de salida)**  
Unidades producidas por unidad de tiempo.  
> Ejemplo: 880 placas / 380 min = 2.3 piezas/min.

**WIP (Work in Progress)**  
Cantidad de unidades en proceso, aún no terminadas.

**Takt Time**  
Ritmo de producción necesario para cumplir la demanda del cliente.  
> Takt = Tiempo disponible / Demanda diaria

---

## 📚 Terminología complementaria

**SMED (Single-Minute Exchange of Die)**  
Metodología para reducir tiempos de setup a menos de 10 minutos.

**5S**  
Sistema de gestión visual para mantener orden, limpieza y disciplina.

**TPM (Total Productive Maintenance)**  
Enfoque de mantenimiento preventivo y autónomo para maximizar disponibilidad.

**Kaizen**  
Mejora continua basada en pequeñas acciones diarias de los equipos.

**Poka-Yoke**  
Mecanismos a prueba de errores que previenen fallas humanas o de montaje.

---

> 📘 *Fuente base: metodología TPM y normas JIS Z8141, adaptado al entorno electrónico (montaje SMT, test y ensamblado final).*

