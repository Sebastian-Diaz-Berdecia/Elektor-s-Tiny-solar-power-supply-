# Elektor's Tiny solar power supply

Este proyecto consta de un pequeño convertidor elevador (boost) basado en el circuito integrado **AP3015** para generar una salida regulada de 3V3 a partir del voltaje de una batería recargable AA(A).

Durante el día un panel solar carga la batería y el circuito esta deshabilitado mientras que durante la noche el circuito se activa y la tensión de la batería es elevada hasta los 3V3 para alimentar una tira LED que puede ser empleada para iluminar un jardín durante las noches. 

Este circuito está basado en el proyecto **"Tiny solar power supply"** de Clemens Valens publicado en la revista Elektor. 

---

<p align="center">
<img width="1246" height="737" alt="image" src="https://github.com/user-attachments/assets/566ed794-a577-47f9-8cbb-c64ce94f9214" />
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
