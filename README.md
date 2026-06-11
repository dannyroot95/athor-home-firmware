# Athor Home Firmware

Binarios publicados para actualizacion remota de dispositivos Athor Home.

## Firebase

El dispositivo revisa cada 60 segundos:

```json
{
  "firmware": {
    "update": false,
    "url": "https://raw.githubusercontent.com/dannyroot95/athor-home-firmware/main/firmware/sonoff-1.0.20-remote-no-fs.bin",
    "version": "1.0.20",
    "force": false
  }
}
```

Cuando `update` es `true`, el dispositivo descarga el binario desde `url`.
