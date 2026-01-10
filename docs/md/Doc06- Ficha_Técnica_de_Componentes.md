# DOCUMENTO 06: FICHA TÉCNICA DE COMPONENTES (PROPUESTA MVP)

<div align="justify">


**Impulsores:** Yaneth Villegas y Héctor Aguila

**Objetivo:** Prototipado de hardware costo-eficiente, accesible, de alta penetración de señal y bajo consumo, con diseño camuflado y uso pedagógico.

> **Nota:** Esta selección de componentes es una propuesta teórica.

## 1. Unidad de Procesamiento y Comunicación (El Corazón)

### Módulo NB-IoT / LTE-M
- **Componente:** Ej. SIM7080G o Quectel BG95 ([LCSC](https://www.lcsc.com/)).
- **Por qué:** Diseñados para "Deep Coverage" (sótanos/interiores) y meses de batería ([GSMA NB-IoT](https://www.gsma.com/iot/resources/nb-iot-deployment-guide/)).
- **Camuflaje y seguridad invisible:** El módulo se integra en una pulsera escolar, permitiendo que el dispositivo pase desapercibido y sea aceptado como accesorio educativo.
- **Costo-eficiencia:** Selección de componentes estandarizados y ampliamente disponibles, facilitando la producción en volumen, la viabilidad económica y la accesibilidad para políticas públicas.

### Microcontrolador (MCU)
- **Componente:** ESP32-S3 o nRF52840.
- **Por qué:** Bajo consumo y capacidad para TinyML (IA ligera en el chip).

## 2. Sensores (La Percepción)

### Acelerómetro
- **Componente:** LIS3DH o ADXL345.
- **Función:** Detectar caídas, forcejeos o "jalones" violentos. (Consumo en microamperios).

### Sensor de Ritmo Cardíaco (PPG)
- **Componente:** MAX30102 o similar.
- **Función:** Monitoreo de frecuencia cardíaca para detectar picos de adrenalina.
- **Nota:** Requiere contacto con piel (pulsera/dije).

## 3. Gestión de Energía (La Autonomía)

- **Batería:** Li-Po 150mAh - 300mAh (tipo moneda/ultra-delgada).
- **Cargador:** Pines magnéticos (estilo smartwatch) para sellado IP68.

## 4. Interfaz y Alerta (La Salida)

- **Antena:** FPC integrada al chasis.
- **Micrófono:** MEMS (Activación exclusiva por evento crítico).

> **Nota de Privacidad y Legalidad:** El micrófono NO es para escucha activa. Se propone su activación técnica **solo durante los segundos de la emergencia** (alerta biométrica confirmada) para capturar "ráfagas de audio" que sirvan como evidencia judicial del contexto (gritos, amenazas). Esta funcionalidad debe ser validada legalmente.

## Sostenibilidad y Comparativa Social
El diseño costo-eficiente, camuflado y accesible permite la implementación masiva sin comprometer presupuestos públicos y facilita la aceptación institucional como herramienta pedagógica de seguridad.

---
## Fuentes y Referencias
- LCSC Electronics: [SIM7080G](https://www.lcsc.com/)
- GSMA: [NB-IoT Deployment Guide](https://www.gsma.com/iot/resources/nb-iot-deployment-guide/)
- Alibaba: [Costos de componentes](https://spanish.alibaba.com/)

</div>