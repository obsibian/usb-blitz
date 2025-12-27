# USB-Blitz

USB-Blitz es una aplicación gráfica diseñada para grabar imágenes ISO en unidades USB. Ofrece una interfaz renovada y moderna, con soporte mejorado para arrastrar y soltar archivos, facilitando al máximo el proceso de creación de USB booteables.

<img width="682" height="609" alt="usb-bz" src="https://github.com/user-attachments/assets/34d8ca49-ffb9-414c-9cb0-1ac34c15788b" />

---

## 🚀 Características

* Aplicacion diseñada para KDE Plasma 6 (qt).
* Interfaz moderna y fácil de usar.
* Soporte completo para arrastrar y soltar imágenes ISO.
* Detección automática de unidades USB disponibles.
* Progreso detallado del proceso de escritura.
* Verificación mejorada: SHA-256, un método mucho más seguro para garantizar la integridad de tus archivos ISO.

---

## 📦 Instalación

Instala el paquete `.deb` en Debian 13 con:

```bash
sudo dpkg -i usb-blitz.amd64.deb
sudo apt-get install -f
```

---

## 🧰 Requisitos

* Sistema operativo: **Debian 13**.
* Dependencias estándar incluidas en el paquete `.deb`.

---

## 📁 Estructura del proyecto

```
usb-blitz/
├── src/                     # Código fuente
├── debian/                  # Archivos de empaquetado
├── usb-blitz.amd64.deb      # Paquete instalable
└── README.md
```

---

## 🛠 Uso

1. Abre la aplicación USB-Blitz.
2. Arrastra y suelta tu archivo `.iso` sobre la ventana, o selecciónalo manualmente.
3. Elige la unidad USB donde deseas grabar la imagen.
4. Pulsa **Escribir USB** y espera a que finalice el proceso.

---

## 📜 Licencia

Este proyecto está bajo la **GNU General Public License v3.0**.

---

## 🤝 Contribuciones

¡Las contribuciones son bienvenidas! Especialmente necesitamos ayuda con:

* Traducciones a otros idiomas.

---

## 📧 Contacto

Opcional: telegram @geinux
