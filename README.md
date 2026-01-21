# 🐠 Acuario Interactivo en React  
**Versión:** 1.0.0  
**Fecha:** 21/01/2026  

---

## 📘 Introducción

Este proyecto es un **acuario interactivo desarrollado con React**, pensado como ejemplo educativo para aprender conceptos clave de **programación visual, animación básica y manejo de estado** en aplicaciones web modernas.

El acuario simula peces nadando, burbujas subiendo y comida cayendo, todo ello reaccionando a la interacción del usuario de forma dinámica y visualmente atractiva.

---

## 🎯 Objetivos didácticos

- Comprender el uso de **React Hooks** (`useState`, `useEffect`, `useRef`)
- Aprender a simular **movimiento y animación** sin librerías externas
- Entender la **interacción usuario–interfaz** mediante el ratón
- Practicar **pensamiento lógico y matemático** aplicado a gráficos
- Desarrollar interfaces visuales con **componentes reutilizables**

---

## 🧠 Estructura general del componente

El acuario está encapsulado en un único componente principal que gestiona:

- 🐟 Peces
- 🫧 Burbujas
- 🍽️ Comida
- 🖱️ Posición del ratón
- 🧱 Límites del acuario

Cada elemento tiene su propio comportamiento y se actualiza de forma continua.

---

## 🐟 Gestión de los peces

Los peces son entidades animadas que:

- Se mueven de forma autónoma 🌊  
- Huyen del cursor del ratón 🖱️  
- Se acercan a la comida cuando aparece 🍽️  
- Rebotan en los bordes del acuario 🧱  

### Conceptos clave:
- Velocidad en dos ejes (horizontal y vertical)
- Fricción para suavizar el movimiento
- Límites de velocidad para evitar movimientos bruscos
- Orientación automática según la dirección del nado

---

## 🫧 Sistema de burbujas

Las burbujas añaden realismo y profundidad visual:

- Suben constantemente hacia la superficie ⬆️  
- Al salir del acuario, reaparecen desde abajo 🔁  
- Tienen tamaños y velocidades diferentes para variedad visual  

Este sistema es ideal para entender **animaciones cíclicas**.

---

## 🍽️ Mecánica de la comida

El usuario puede alimentar a los peces:

- La comida aparece al hacer clic 👆  
- Cae lentamente hacia el fondo ⬇️  
- Los peces cercanos cambian su rumbo para comerla 🐟  
- Al ser alcanzada, la comida desaparece ❌  

Este comportamiento introduce el concepto de **objetivos dinámicos**.

---

## 🖱️ Interacción con el ratón

El acuario detecta la posición del cursor:

- Los peces huyen si el ratón se acerca 😱  
- Al salir el cursor del acuario, el comportamiento vuelve a la normalidad 😌  

Esto permite aprender cómo **capturar eventos del usuario** y traducirlos en reacciones visuales.

---

## ⏱️ Animación y tiempo

El movimiento se basa en un bucle que:

- Se ejecuta aproximadamente a **60 FPS** 🎞️  
- Actualiza posiciones y estados en pequeños pasos  
- Simula una animación fluida sin usar canvas ni librerías externas  

Ideal para entender **simulación en tiempo real**.

---

## 🎨 Diseño visual

El aspecto gráfico incluye:

- Gradientes para simular agua 🌊  
- Arena, plantas y rocas decorativas 🌱🪨  
- Peces dibujados con gráficos vectoriales 🐠  
- Estilos modernos y sombras para profundidad ✨  

Todo el diseño está pensado para ser **claro, atractivo y educativo**.

---

## 🧩 ¿Para quién es este proyecto?

✅ Estudiantes de React  
✅ Personas que aprenden programación visual  
✅ Docentes que buscan ejemplos interactivos  
✅ Desarrolladores que quieren practicar animación básica  
✅ Curiosos que disfrutan aprendiendo con proyectos creativos  

---

## 🚀 Posibles mejoras futuras

- Añadir más tipos de peces 🐡  
- Incluir sonidos ambientales 🔊  
- Controlar velocidad y cantidad de comida 🎚️  
- Separar el código en componentes más pequeños 🧱  
- Añadir soporte táctil para móviles 📱  

---

## 📌 Conclusión

Este acuario interactivo es un excelente ejemplo de cómo **React puede utilizarse más allá de formularios y listas**, permitiendo crear experiencias visuales, interactivas y educativas de forma clara y divertida.

¡Perfecto para aprender programando! 🧑‍💻🐟🌊  

# Tareas Pendientes:
- [x] Añadir funciones de memoria.
- [] Incluir conversión de binaro a hex.
- [] Añadir pin de usuario.

# Imagen desde una URL
[Microprocesador 6502](https://external-content.duckduckgo.com/iu/?u=https%3A%2F%2Ftse1.mm.bing.net%2Fth%2Fid%2FOIP.eyQ1Q9Sh_KHqBnf83-UuBQHaCs%3Fpid%3DApi&f=1&ipt=772211b9d930dd4112b53b8af3465f04ec3b437728134d7fedad7018de999f17&ipo=images)
