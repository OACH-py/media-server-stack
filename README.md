# 📼 Media Server Stack

Un stack **Docker** completo para gestionar y organizar tu contenido multimedia: películas, series, música y descargas, con las siguientes herramientas:

- **qBittorrent**: cliente torrent con interfaz web.
- **Radarr**: gestión y descarga automática de películas.
- **Sonarr**: gestión y descarga automática de series.
- **Prowlarr**: indexador para torrents y usenet.
- **Jellyfin**: servidor multimedia para streaming.
- **Jellyseerr**: interfaz para solicitudes en Jellyfin.
- **Bazarr**: gestión automática de subtítulos.

---

## ⚙️ Requisitos

- **Docker** y **Docker Compose** instalados en tu sistema.
- Usuario con permisos adecuados para ejecutar contenedores.
- Configuración de variables en `.env` para rutas, puertos y usuarios.

---

## 🚀 Instalación

1. **Clona el repositorio:**

   ```bash
   git clone https://github.com/OACH-py/media-server-stack.git
   cd media-server-stack

2. Crea y ajusta el archivo .env con tus rutas y configuraciones personales.


3. Levanta los servicios con Docker Compose:

docker-compose up -d




---

📂 Estructura de carpetas
```
media-server-stack/
├── bazarr/
│   └── config/
├── downloads/
│   └── Descargas-Jellyfin/
├── jellyfin/
│   ├── cache/
│   └── config/
├── jellyseerr/
│   └── config/
├── media/
│   ├── Música/
│   ├── Peliculas/
│   ├── TV/
│   └── Youtube/
├── prowlarr/
│   └── config/
├── qbittorrent/
│   └── config/
├── radarr/
│   └── config/
└── sonarr/
    └── config/

```
---

🔧 Variables en .env

Define rutas, puertos y usuarios en este archivo para mantener la configuración centralizada y portable.


---

📫 Contacto

Para dudas, sugerencias o contribuciones, abre un issue o pull request en el repositorio.


---

¡Disfruta tu media server personalizado! 🎬🎵📺
