# vx-dga-x-matatacode

Paquete Debian para Vitalinux que proporciona un acceso directo a Matata Studio VinceBot.

## Descripción

Este paquete instala un lanzador que permite acceder fácilmente a la plataforma web Matata Studio VinceBot desde el escritorio Vitalinux. También configura las reglas udev necesarias para que VinceBot sea reconocido correctamente por el sistema.

## Características

- Acceso directo en el menú de aplicaciones
- Categoría: Escuela40
- Abre Matata Studio VinceBot en Chromium
- Reglas udev para VinceBot
- Icono personalizado de MatataCode

## Requisitos

- Chromium o Chromium-browser instalado
- Conexión a Internet para acceder a la plataforma
- Permiso root para instalar reglas udev

## Compilación del paquete

Para compilar el paquete desde las fuentes:

```bash
cd MatataCode
dpkg-buildpackage -us -uc
```

## Información del Paquete

- **Nombre**: vx-dga-x-matatacode
- **Versión**: 1.0-1
- **Arquitectura**: all
- **Mantenedor**: Vitalinux Admin <admin@vitalinux.org>
- **Licencia**: GPL-3.0+

## Archivos incluidos

- `/usr/share/applications/vx-matatacode.desktop` - Lanzador de la aplicación
- `/etc/udev/rules.d/99-vincebot.rules` - Reglas udev para VinceBot
