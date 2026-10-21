# 🌐 Simulador 3D Interactivo de Climatización y Flujo de Aire en Data Center (HVAC) — SEMANA 9

[![GitHub Pages](https://img.shields.io/badge/Demo%20en%20Vivo-GitHub%20Pages-00e5ff?style=for-the-badge&logo=github)](https://gmph2007.github.io/simulador-climatizacion-datacenter-3d/)
[![Semana](https://img.shields.io/badge/Evaluaci%C3%B3n-Semana%209-fbbf24?style=for-the-badge)](https://gmph2007.github.io/simulador-climatizacion-datacenter-3d/)
[![Norma ASHRAE](https://img.shields.io/badge/Norma-ASHRAE%20TC%209.9%20Clase%20A1-10b981?style=for-the-badge)](https://gmph2007.github.io/simulador-climatizacion-datacenter-3d/)
[![Three.js](https://img.shields.io/badge/Three.js-r128%20WebGL-0284c7?style=for-the-badge&logo=three.js)](https://gmph2007.github.io/simulador-climatizacion-datacenter-3d/)

---

## 📌 Datos de Entrega Académica Oficial

- **Institución:** Instituto de Educación Superior Tecnológico Público "Hermanos Cárcamo" — Paita, Piura
- **Programa Académico:** Arquitectura de Plataformas y Servicios de Tecnologías de la Información
- **Unidad Didáctica:** Diseño de Data Center (DDC)
- **Sesión / Evaluación:** **Semana 09 — Climatización y HVAC en Centros de Datos**
- **Docente:** **Dr. Javier Eduardo Jaramillo Atoche**
- **Estudiante (Autoría):** **Gerson Misael Pintado Huaman**

---

## 🚀 DEMO EN VIVO (Abrir en Navegador)

👉 **Haz clic para interactuar directamente con la maqueta 3D:**  
### **[https://gmph2007.github.io/simulador-climatizacion-datacenter-3d/](https://gmph2007.github.io/simulador-climatizacion-datacenter-3d/)**

*(Compatible con PC, laptop, tablet y smartphone sin necesidad de instalar programas adicionales).*

---

## 🔒 Autoría y Marca de Agua Registrada

Este proyecto cuenta con **marca de agua oficial integrada** tanto en la interfaz interactiva, como en una **placa física 3D conmemorativa** modelada dentro de la propia sala del Data Center, y en el sistema de exportación de capturas de pantalla HD con metadatos del estudiante y docente.

- **Estudiante:** Gerson Misael Pintado Huaman
- **Docente Responsable:** Dr. Javier Eduardo Jaramillo Atoche
- **IESTP "Hermanos Cárcamo" — Paita, Perú**

---

## ❄️ Descripción del Proyecto (Semana 9)

Este simulador 3D interactivo modela el comportamiento aerodinámico y termodinámico del sistema de climatización de un centro de datos moderno de alta densidad bajo el estándar **ASHRAE TC 9.9 Clase A1** y recomendaciones **TIA-942**.

### 🔹 Componentes Modelados:
1. **Unidad CRAC de Precisión N+1 (Liebert / Schneider Electric):**
   - Inyección descendente (*downflow*) de aire frío a **18.0 °C** al plenum del piso técnico.
   - Ventiladores centrífugos EC Inverter con velocidad modulada al 78%.
   - Caudal de 8,500 CFM con monitoreo digital en tiempo real.
2. **Pasillo Frío Confinado (CAC - Cold Aisle Containment):**
   - Encapsulamiento con paneles herméticos y baldosas perforadas (apertura del 25%).
   - Impulsión laminar que alimenta los frentes de los servidores evitando mezclas térmicas.
3. **Pasillos Calientes (HAC - Hot Aisle Containment):**
   - Captación del aire de descarga térmica expulsado por los servidores a **31.5 °C - 33.0 °C**.
4. **Ducto Perimetral de Retorno Superior:**
   - Canalización hermética en chapa galvanizada que conduce el 100% del aire caliente de vuelta a la toma superior del evaporador del CRAC, cerrando el ciclo frigorífico con máxima eficiencia COP y **PUE de 1.35**.

---

## 🎮 Modos y Funcionalidades Interactivas

| Modo / Control | Descripción |
| :--- | :--- |
| **👁️ Realista HD** | Materiales PBR con reflejos especulares, sombras suaves y texturas de servidores 42U con LEDs parpadeantes. |
| **🦴 Rayos X 3D** | Transparencia total CAD/BIM: el piso técnico se vuelve vidrio holográfico revelando los pedestales, bandejas de cables y tuberías inferiores. Racks traslúcidos muestran servidores blade y placas base; el CRAC revela sus serpentines de cobre y turbinas centrífugas. |
| **🌡️ Termografía FLIR** | Paleta infrarroja calórica térmica (Azul 18°C $\rightarrow$ Cian 20°C $\rightarrow$ Naranja 28°C $\rightarrow$ Rojo 35°C). |
| **🟢 Normal N+1** | Operación balanceada de alta eficiencia (PUE 1.35, 18°C impulsión / 31.5°C retorno). |
| **🔴 Falla CRAC** | Simulación de parada de emergencia de CRAC 01 con activación de backup al 100%, alarma acústica y advertencia térmica. |
| **⚠️ Bypass Térmico** | Apertura de puerta exterior que provoca turbulencia y recirculación caliente elevando el PUE a 1.85 crítico. |
| **❄️ Free Cooling** | Modo economizador nocturno con enfriamiento indirecto que reduce en un 42% el consumo de compresores (PUE 1.18). |
| **🚪 Puerta Animada** | Apertura y cierre interactivo de 90° con bisagra real. |
| **🔊 Audio Acústico** | Síntesis acústica mediante Web Audio API con sonido de turbinas EC y zumbido de transformador a 60 Hz. |
| **📸 Captura HD** | Exportación instantánea en alta resolución con marca de agua oficial integrada para informes de entrega. |

---

## 📁 Entregables Incluidos en este Repositorio

- `index.html`: Simulador interactivo 3D optimizado para GitHub Pages con marca de agua oficial.
- `Simulacion_3D_Climatizacion_DataCenter_Pintado.html`: Archivo fuente original de la simulación.
- `Caso_Practico_y_Mapa_Conceptual_Climatizacion_DataCenter_Misael_Pintado.docx`: Documento formal de caso práctico y mapa conceptual en Word.
- `Caso_Practico_y_Mapa_Conceptual_Climatizacion_DataCenter_Misael_Pintado.pdf`: Documento formal de caso práctico y mapa conceptual en PDF.
- `Presentacion_Climatizacion_DataCenter_Misael_Pintado.pptx`: Presentación de 12 diapositivas ejecutivas para exposición en PowerPoint.
- `Presentacion_Climatizacion_DataCenter_Misael_Pintado.pdf`: Diapositivas en formato PDF listo para imprimir o proyectar.
- `assets/`: Librerías locales Three.js r128 y OrbitControls para ejecución 100% offline.

---
© 2026 Gerson Misael Pintado Huaman — IESTP "Hermanos Cárcamo" Paita  
Docente: Dr. Javier Eduardo Jaramillo Atoche
