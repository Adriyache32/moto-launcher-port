# Moto Launcher 3 Port

APK extraído directamente de un dispositivo Motorola (Launcher3QuickStep).

## 📋 Información

| Campo | Valor |
|-------|-------|
| **Paquete** | `com.motorola.launcher3` |
| **Origen** | `/system_ext/priv-app/Launcher3QuickStep/Launcher3QuickStep.apk` |
| **Tamaño** | ~39 MB |
| **Versión** | 26.1.2 |
| **Compatibilidad** | Android 12+ |

## 🚀 Instalación

### Método 1: ADB
```bash
adb install MotoLauncher3.apk
```

### Método 2: Manual
1. Copia el APK al teléfono
2. Ábrelo desde el explorador de archivos
3. Activa "Fuentes desconocidas" si es necesario
4. Instala

### Configurar como launcher predeterminado
- **Ajustes > Aplicaciones > Launcher predeterminado > Moto Launcher**

## ⚠️ Notas importantes

- Es un **launcher de sistema** (`priv-app`), requiere permisos de sistema
- Para reemplazar el launcher por defecto necesitas acceso root o desactivar el launcher original
- Funciona en la mayoría de dispositivos Android 12+
- En algunos dispositivos puede requerir desactivar el launcher de stock primero

## 📁 Contenido del repositorio

```
moto-launcher-port/
├── MotoLauncher3.apk    # El launcher extraído (39MB)
└── README.md            # Este archivo
```

## ⚖️ Disclaimer

Este APK es propiedad de **Motorola Mobility LLC**. Se distribuye únicamente con fines educativos y de investigación. Todos los derechos pertenecen a Motorola. El autor no se hace responsable por el mal uso o daños causados.

## 📜 Licencia

Uso educativo solamente. No redistribuir con fines comerciales.
