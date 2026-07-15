<p align="center">
  <img src="https://img.shields.io/badge/Moto%20Launcher%203-26.1.2-blue?style=for-the-badge&logo=android">
</p>

<p align="center">
  <img src="https://img.shields.io/badge/Android-12%2B-red?style=for-the-badge&logo=android">
  <img src="https://img.shields.io/badge/Motorola-grey?style=for-the-badge&logo=motorola">
  <img src="https://img.shields.io/badge/Tama%C3%B1o-39MB-yellow?style=for-the-badge">
  <img src="https://img.shields.io/badge/license-Propiedad%20Motorola-lightgrey?style=for-the-badge">
</p>

<p align="center">
  <img src="https://img.shields.io/badge/APK-portado-brightgreen?style=for-the-badge">
  <img src="https://img.shields.io/badge/PRs-welcome-ff69b4?style=for-the-badge">
  <img src="https://img.shields.io/github/stars/Adriyache32/moto-launcher-port?style=for-the-badge&logo=github">
</p>

Launcher de Motorola extraído directamente del sistema (Launcher3QuickStep) y portado para uso libre.

## Información

| Campo | Valor |
|-------|-------|
| **Paquete** | `com.motorola.launcher3` |
| **Origen** | `/system_ext/priv-app/Launcher3QuickStep/Launcher3QuickStep.apk` |
| **Tamaño** | ~39 MB |
| **Versión** | 26.1.2 |
| **Compatibilidad** | Android 12+ |

## Instalar

```bash
adb install MotoLauncher3.apk
```

| Método | Comando |
|--------|---------|
| ADB | `adb install MotoLauncher3.apk` |
| Manual | Copiar APK al teléfono e instalar desde el explorador |

## Como usar

1. Instala el APK
2. Ve a **Ajustes > Aplicaciones > Launcher predeterminado**
3. Selecciona **Moto Launcher**
4. Listo

| Acción | Resultado |
|--------|-----------|
| Instalar | Reemplaza el launcher actual |
| Configurar | Ajustes > Launcher predeterminado |
| Desinstalar | `adb uninstall com.motorola.launcher3` |

## Notas

- Es un **launcher de sistema** (`priv-app`), requiere permisos elevados
- En algunos dispositivos necesitas root para reemplazar el launcher de stock
- Funciona en la mayoría de Android 12+

## Disclaimer

Este APK es propiedad de **Motorola Mobility LLC**. Se distribuye únicamente con fines educativos. Todos los derechos pertenecen a Motorola.

Repo: https://github.com/Adriyache32/moto-launcher-port
