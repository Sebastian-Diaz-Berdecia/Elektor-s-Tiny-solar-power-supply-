# Elektor's Tiny solar power supply

Este proyecto es una fuente de alimentación programable para protoboard basada en los reguladores lineales **LM7805** y el **LM317** con dos salidas independientes que se pueden programar para sumistrar dos tensiones, 5V o 3.3V.

Su factor de forma y conectores permiten acoplarla con facilidad a la protoboard a través de sus rieles de alimentación superior e inferior.
La fuente hace uso de dos conectores que se pueden ajustar para que cada salida suministre ya sea una tensión de 5V o de 3.3V de forma independiente para cada salida. 

---

<p align="center">
<img width="1031" height="833" alt="image" src="https://github.com/user-attachments/assets/391c4162-da77-49c6-89fd-02bc1536976d" />
</p>

---

## 🔑 Caracteristicas principales

- **Reguladores lineales LM7805 y LM317**
  - Alta reparabilidad.
  - Diseño simple fácil de entender para aficionados.
  - Tensión limpia sin ruido de conmutación (en contraste a una fuente o regulador conmutado).
- **Factor de forma**
  - Ocupa poco espacio y facil de conectar.
  - Compatible con varios tipos de protoboards.
  - Plug and play (es una alternativa sencilla a una fuente de laboratorio convencional).
- **Alimentación**
  - Se alimenta por medio de un adaptador de 9V a 12V a través de una entrada barrel jack.

---

## 📐 Factor de forma

- Tamaño compatible con la mayoria de protoboards.
- Conexión rapida y directa con los rieles de alimentación de la protoboard. 

---

## 🛠 Aplicaciones

- Microntroladores.  
- Sistemas embebidos.  
- Circuitos de proposito general de 5V o 3.3V.  
- Prototipado y pruebas.
- Alternativa a una fuente de laboratorio convencional.

---

## 📄 Documentación 

- [LM7805](https://rocelec.widen.net/view/pdf/hl53fsrf43/FAIR-S-A0000088116-1.pdf?t.download=true&u=5oefqw)  
- [LM317](https://www.ti.com/lit/ds/symlink/lm317.pdf)  

---

## 🚀 Estado

- ✅ Diseño esquematico.  
- ✅ PCB layout (2-layer).  
- 🔜 Fabricación (pendiente).
- 🔜 Prototipado y pruebas (pendiente).

---

## 📷 Preview

*(Add photos, renderings, or thermal plots here when available.)*

- *Esquematico:*
<p align="center">
<img width="1256" height="842" alt="image" src="https://github.com/user-attachments/assets/edffd73b-e9d2-481d-81b5-602c0c91d43d" />
</p>

- *Layout a 2 capas:*
<p align="center">
<img width="806" height="516" alt="PCB" src="https://github.com/user-attachments/assets/73d5af8d-23a9-4cd6-a8db-8e6396d123ac" />
</p>

*(La idea general es empezar por este layout y esquematico para poco a poco ir intruduciendo mejoras y caracteristicas mas avanzadas asi como tambien mejores capacidades)*

---

## 📜 Ideas para futuras mejoras: (Borrador)
- Usar la configuración programable del LM317 con un NE555 o un ATtyny para controlar la tensión de salida empleando pulsadores. 
- Usar el regulador lineal de bajo ruido LT3045
- Transistor de paso externo o en configuración de boost de corriente para suministrar más corriente a la salida.
- Medicion de corriente y voltaje (Pantalla LCD).
- Agregar indicadores para señalizar la tensión de salida en uso.
- Evaluar si mantener las salidas independientes o unificarlas.
- Para esta versión en particular (v0.1) reemplazar los conectores por jumpers para PCB (como en los programadores de las BIOS).

---
