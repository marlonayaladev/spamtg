# 📨 Spamtg Bot

Bot en Python cuyo objetivo es enviar mensajes automáticos (spam) en Telegram utilizando la librería `telethon`.

---

## 🚀 Tecnologías

- Python 3.x  
- [Telethon](https://pypi.org/project/Telethon/)  
- `requirements.txt` para instalación de dependencias

---

## 📂 Estructura del proyecto

├── bot.py # Script principal que ejecuta el envío de mensajes
├── requirements.txt # Librerías necesarias (ej: telethon)
├── bot_spammer.session # Archivo de sesión generado por Telethon
└── bot_spammer.session-journal

---

## ⚙️ Instalación y uso

1. **Clona el repositorio**  
   ```bash
   git clone https://github.com/marlonayaladev/spamtg.git
   cd spamtg

   pip install -r requirements.txt

   python bot.py
