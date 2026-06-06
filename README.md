# velxio-test — Entorno ESP32-C3 en GitHub Codespaces

Repositorio preconfigurado para programar el **ESP32-C3 con Arduino** directamente desde [GitHub Codespaces](https://github.com/features/codespaces), usando la imagen Docker del proyecto [Velxio](https://github.com/davidmonterocrespo24/velxio).

---

## 🚀 Inicio rápido

1. Haz clic en el botón **Code → Codespaces → Create codespace on main**.
2. Espera a que el contenedor arranque (la primera vez descarga la imagen de Velxio, tardará ~2 min).
3. El navegador abrirá automáticamente la interfaz web de Velxio en el puerto **80**.
4. Selecciona la placa **ESP32-C3** en la interfaz y empieza a escribir tu sketch de Arduino.

---

## 🛠️ ¿Qué incluye el entorno?

| Componente | Versión |
|---|---|
| ESP-IDF | 4.4.7 |
| Arduino-ESP32 core | 2.0.17 |
| arduino-cli | última estable |
| QEMU ESP32-C3 (RISC-V) | incluido en imagen Velxio |
| Python | 3.12 |

---

## 🔌 Puertos reenviados

| Puerto | Descripción |
|---|---|
| `80` | IDE web de Velxio (escribe, compila y simula código Arduino) |

---

## 📂 Estructura del repositorio

```
.devcontainer/
  devcontainer.json   # Configuración de Codespaces
  docker-compose.yml  # Servicio Velxio con la imagen Docker oficial
```

---

## 📖 Recursos

- [Velxio — proyecto original](https://github.com/davidmonterocrespo24/velxio)
- [Documentación de GitHub Codespaces](https://docs.github.com/en/codespaces)
- [ESP32-C3 Datasheet (Espressif)](https://www.espressif.com/en/products/socs/esp32-c3)