# 🤖 Reconstrucción e Implementación de Trayectorias

Este repositorio contiene la documentación, código fuente y resultados experimentales del proyecto de tesis titulado:

**"Desarrollo y Validación de una Metodología de Navegación Autónoma mediante Visual SLAM para Mapeo y Localización de Obstáculos en Situaciones de Emergencia"**,  
desarrollado en la **Universidad Veracruzana**, dentro de la **Maestría en Ingeniería Aplicada**, en **Boca del Río, Veracruz**.

El objetivo principal de esta investigación es diseñar y validar una metodología de navegación autónoma basada en Visual SLAM, utilizando el algoritmo **ORB-SLAM3** y el dron **DJI Tello**, con el propósito de generar mapas tridimensionales en tiempo real y planificar trayectorias seguras en entornos sin señal GPS.

Este enfoque busca contribuir al desarrollo de herramientas accesibles para operaciones de rescate, exploración autónoma y navegación en entornos desafiantes.

---

### 📌 Información del Proyecto

- **Autor:** Ing. Román Velásquez  
- **Director:** Dr. Héctor Vázquez Leal – [hvazquez@uv.mx](mailto:hvazquez@uv.mx)  
- **Co-Director:** Dr. Roberto Castañeda Sheissa – [rocastaneda@uv.mx](mailto:rocastaneda@uv.mx)  
- **Asesor Externo:** Dr. Gerardo Ulises Díaz Aragón – [guda.diaz.gd@gmail.com](mailto:guda.diaz.gd@gmail.com)  
- **Apoyo:** CONAHCYT – Registro de beca: **1255395**

> 🧠 Este repositorio tiene como finalidad compartir el conocimiento y permitir la replicabilidad de los experimentos, proporcionando acceso abierto a los materiales utilizados. ¡Se alienta a la comunidad a contribuir con mejoras y sugerencias!

---

## 🔹 Evidencias gráficas de reconstrucción e implementación de trayectorias

### 🔸 Objetos
1. [🦅 Monumento Águila de Los Lagos – Xalapa, Veracruz](https://www.youtube.com/watch?v=6EgwM3oM3rA)
2. [🧜‍♀️ Escultura La Sirena – Boca del Río, Veracruz](https://www.youtube.com/watch?v=OLKTQWQKxWs)

### 🔸 Entornos Internos
1. [🧪 Laboratorio de Diseño de Circuitos – INAOE, Puebla](https://www.youtube.com/watch?v=8AfKS5QILlc)
2. [🏛️ Sala de Juntas / Salón de Posgrados – Boca del Río, Veracruz](https://www.youtube.com/watch?v=lwr3lTqrSO4)
3. [💻 Cubículo FIIE – Xalapa, Veracruz](https://www.youtube.com/watch?v=2KpgB2VbseQ)

### 🔸 Entornos Externos
1. [🔭 Observatorio INAOE – Tonantzintla, Puebla](https://www.youtube.com/watch?v=auChu9-rH2E)
2. [🏞️ Entorno Mixto – FIIE, Xalapa, Veracruz](https://www.youtube.com/watch?v=wbwutqgBZl4)

---

## 🔹 Validación con Conjuntos de Datos Estándar

- **EuRoC MAV Dataset**  
  [Descargar](https://projects.asl.ethz.ch/datasets/doku.php?id=kmavvisualinertialdatasets) | [Video de prueba](https://youtu.be/V7T5O8ly9Fk)

- **TUM-VI Dataset**  
  [Descargar](https://cvg.cit.tum.de/data/datasets/visual-inertial-dataset) | [Video de prueba](https://youtu.be/d6zgKbzEUMg)

- **KITTI Odometry Dataset**  
  [Descargar](https://www.cvlibs.net/datasets/kitti/eval_odometry.php) | [Video de prueba](https://youtu.be/9_AHEYWJesE)

---

## 🔹 Teleoperación del Dron DJI Tello

Control del dron con teclado o mando de Xbox One S.  
📄 [Documentación](Operar-Drone-KB-XOs.pdf)  
📄 [Especificaciones del Dron DJI Tello Ryze](Drone-DJI-Tello-Ryze.pdf)

---

## 🔹 Calibración Visual

📄 [Metodología y parámetros del archivo YAML](Calibración-Visual.pdf)  
📹 [Video: Calibración por ROS (Webcam)](https://youtu.be/CwaFwtEkfDs)  
📹 [Video: Calibración por MATLAB (Drone DJI Tello)](https://youtu.be/oaTrxvDIrXQ)

---

## 🔹 Evaluación con el Dron DJI Tello

- [📹 Evaluación monocular en entorno interior](https://youtu.be/itlC6GhlaIY)
- [📹 Evaluación en tiempo real con ROS](https://youtu.be/nL-m96cTEJc)

---

## 🔹 Integración con OMPL

- [📹 Video de implementación de trayectorias](https://youtu.be/nGDqc4TUCUM)
