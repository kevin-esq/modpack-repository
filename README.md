# Modpack Repository

Este repositorio contiene los manifiestos de modpacks para Mewtropolis Launcher.

## Estructura

- `modpacks/index.json` - Índice global de modpacks
- `modpacks/{modpack-id}/manifest.json` - Manifest de cada modpack
- `modpacks/{modpack-id}/icon.png` - Icono del modpack

## Versionado

- Tags: `v1.0.0`, `v1.1.0`, etc.
- Cada release incluye los iconos como assets
- Los mods se descargan desde R2/CDN (no incluidos en el repo)

## Personalización

Los usuarios pueden hacer fork de este repositorio para mantener sus configuraciones personalizadas.

## Actualizaciones

1. Modificar manifests en `modpacks/`
2. Actualizar `index.json` si es necesario
3. Crear nuevo tag (ej: `v1.1.0`)
4. Crear release con iconos como assets
