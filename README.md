<p align="center">
  <img src="./Solucion-Gnome-Keyring/docs/Banner.png" alt="EntiendeIT Banner" width="100%">
</p>

# 🐧 Fallos Cotidianos en Linux (y cómo domarlos)

¡Bienvenido/a! Si usas Linux en tu día a día, sabes que a veces el sistema se levanta con ganas de complicarte las cosas. Este repositorio es el rincón oficial de **EntiendeIT**, un espacio dedicado a recopilar soluciones claras, bien explicadas y estructuradas para esos pequeños dolores de cabeza diarios.

> [!NOTE]
> **Nuestra filosofía:** Aquí no venimos a copiar y pegar comandos a ciegas. Venimos a entender qué demonios está pasando bajo el capó. ¡Entendemos lo que hacemos!

---

## 🛠️ Fallos Documentados

### 🔑 1. Restablecer GNOME Keyring ("Authentication Required")
* **Problema:** Mensaje emergente continuo al abrir Google Chrome o navegadores basados en Chromium.
* **Causa:** Desincronización por cambio reciente de contraseña o uso de inicio de sesión automático (GDM).
* **Solución:** Uso del gestor gráfico `seahorse` para purgar y resincronizar el depósito de claves con el login del sistema.
* **🔗 Acceso directo:** [Ir a la carpeta de la solución](./Solucion-Gnome-Keyring/)

---

## 🤝 Contribuciones

Si has encontrado un fallo cotidiano en tu distribución Linux y quieres documentar su solución de manera clara y visual para ayudar a la comunidad:

1. 🍴 Haz un **Fork** del repositorio.
2. 📂 Crea una nueva carpeta con el formato `Solucion-[Nombre-Del-Problema]`.
3. ✍️ Añade tu `README.md` explicativo y las guías visuales pertinentes.
4. 🚀 Envía un **Pull Request**.

---
*Desarrollado y mantenido con paciencia por **@EntiendeIT** — 2026.*
