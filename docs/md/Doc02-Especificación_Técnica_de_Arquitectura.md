<div align="justify">

# DOCUMENTO 02: ESPECIFICACIÓN TÉCNICA DE ARQUITECTURA

**Responsable:** Yaneth Villegas (Dirección de Vinculación Social) y Héctor Aguila (Arquitectura de Solución)
**ID:** VC-2026-CH-01-DOC02

## 1. Hardware (The Edge)

### Microcontrolador
**Propuesta:** SoC con soporte NB-IoT/LTE-M (ej. Simcom o Quectel).
- **Justificación:** Estos módulos permiten transmisión en bandas de baja frecuencia con alta penetración en concreto ([GSMA NB-IoT](https://www.gsma.com/iot/resources/nb-iot-deployment-guide/)).
- **Camuflaje y seguridad invisible:** El diseño del hardware permite que el dispositivo se integre como accesorio escolar, evitando estigmatización y protegiendo la discreción del niño.
- **Costo-eficiencia:** Selección de componentes estandarizados y ampliamente disponibles, facilitando la escalabilidad, la viabilidad económica y la accesibilidad para políticas públicas.

### Sensores
- **Acelerómetro:** De baja potencia para detección de impactos.
- **Sensor PPG:** Para monitoreo de frecuencia cardíaca (HRV).

### Protección
- **Certificación IP68.**
- **Encapsulado:** Resina epóxica para evitar manipulación o daño por líquidos.

## 2. Software e Inteligencia Artificial

### Algoritmo de Detección
Implementación de modelos de clasificación (**Random Forest**) en la nube para identificar patrones de riesgo físico y accidentes. El uso de IA ética permite alertas inteligentes sin grabar imágenes ni audio, priorizando la privacidad y la seguridad.
> *Patrón de Alerta = Taquicardia Súbita + Movimiento Defensivo.*

---
## Sostenibilidad y Escalabilidad
El diseño prioriza la viabilidad económica, la escalabilidad institucional y la accesibilidad, permitiendo su integración en protocolos de municipios y servicios de protección y educación.

### Seguridad
- **Transporte:** Protocolo TLS 1.3.
- **Almacenamiento:** Encriptación AES-256 para datos almacenados.

---
## Fuentes y Referencias
- GSMA: [NB-IoT Deployment Guide](https://www.gsma.com/iot/resources/nb-iot-deployment-guide/)
- Ver Anexo de Fuentes y Referencias Técnicas
</div>