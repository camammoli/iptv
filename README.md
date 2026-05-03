# iptv — Canales de TV argentina

Lista de canales de televisión argentina en formato M3U para reproductores IPTV.

## Canales disponibles

| Canal | Archivo |
|---|---|
| Canal Rural | canales.m3u |
| Crónica TV | canales.m3u |
| Deport TV | canales.m3u |
| Canal 9 Televida | canales.m3u |
| Canal 7 Mendoza | canales.m3u |
| Orbit TV | canales.m3u |
| Ciudad Magazine | canales.txt |

Todos son señales de acceso libre disponibles públicamente por internet.

## Uso

### VLC
`Medios → Abrir archivo de red` y pegás la URL del `.m3u8` del canal que querés, o abrís el archivo `canales.m3u` directamente.

### Desde la terminal
```bash
# VLC
cvlc https://cda2.alsolnet.com/elrural/live/playlist.m3u8

# mpv
mpv https://cda2.alsolnet.com/elrural/live/playlist.m3u8
```

### TiviMate / Kodi
Importar `canales.m3u` como lista de reproducción remota o local.

## Nota

Los streams son proporcionados por terceros. Si algún enlace dejó de funcionar, puede que el canal haya cambiado su CDN.
