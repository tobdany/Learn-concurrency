# 🚀 C++ Systems & Concurrency Lab

Bienvenido a mi laboratorio de experimentación en **C++20**. Este proyecto está dedicado al estudio profundo de la programación de sistemas, con un enfoque especial en el aprovechamiento de **procesadores multi-núcleo** y el desarrollo de software de alta eficiencia.

---

### 🧠 El Enfoque Técnico
Mi objetivo principal es dominar la interacción entre el software y el hardware mediante:
* **Gestión de Hilos:** Implementación avanzada de concurrencia y paralelismo.
* **Modelo de Memoria:** Control preciso del acceso a datos y sincronización.
* **RTOS & Embebidos:** Este repositorio sirve como complemento para mi formación en **Sistemas Operativos de Tiempo Real (RTOS)**, donde el manejo de tareas críticas y la latencia son el pan de cada día.

---

### 🛠️ Herramientas y Conceptos
Para garantizar la integridad y velocidad del sistema, trabajo con:

- **Sincronización:** `std::mutex`, `std::unique_lock`, `std::lock_guard`.
- **Atomicidad:** Operaciones `lock-free` utilizando `std::atomic` para evitar cuellos de botella.
- **Comunicación:** Uso de `Futures`, `Promises` y `Coroutines` para flujos asíncronos.



---

### 🏗️ Gestión del Proyecto (CMake)
Para mantener un estándar de industria, utilizo **CMake** como motor de construcción. Esto me permite:
1.  **Automatización:** Configuración de flags críticos como `-pthread` y `-fcoroutines`.
2.  **Portabilidad:** Estructura organizada con `CMakeLists.txt` y `CMakePresets.json`.
3.  **Escalabilidad:** Gestión eficiente de múltiples ejecutables y dependencias del sistema.




---
*Desarrollado con ❤️ por un entusiasta de los sistemas embebidos.*
