# iptv — Canales de TV argentina

Lista de canales de televisión argentina en formato M3U para reproductores IPTV. Organizada por región y categoría.

**Fuente:** [iptv-org/iptv](https://github.com/iptv-org/iptv) — todos son streams de señal abierta disponibles públicamente.

## Categorías

| Categoría | Canales |
|---|---|
| Señal abierta | TV Pública, El Trece, Telefe, América TV, El Nueve, NET TV |
| Noticias | TN, C5N, Crónica TV, A24, Canal 26, Canal E, IP Noticias, La Nación+, Multivision Federal, 24/7 |
| Deportes | TyC Sports, DeporTV, Fox Sports, FIFA+ |
| Entretenimiento | Ciudad Magazine, Canal Rural, Argentinísima, Volver, Metro TV, Viajar TV |
| Cine | Cine.Ar, Xtrema Acción, Xtrema Cine Clásico, Xtrema Terror |
| Cultura | Encuentro, El Gourmet, TV Universidad UNLP |
| Infantil | Pakapaka, Xtrema Cartoons |
| Música | MusicTop, Cumbia Mix, Más FM 95.9, Quiero Música en mi Idioma |
| Cuyo | Canal 3 Las Heras, Canal 9 Televida, Canal 34 San Juan, Canal 4 San Juan |
| Buenos Aires | Telemax, Canal 11 de la Costa, Canal 79 Mar del Plata, San Pedro TV |
| Litoral / NEA | Canal 9 Litoral, Misiones Cuatro, Tele Posadas, Chaco TV, Canal 4 y 6 Posadas |
| NOA | Catamarca TV, Canal 7 Salta, Canal 4 y 7 Jujuy, Canal 13 San Luis |
| Patagonia | Canal 7 Neuquén, RTN, Canal 2 Ushuaia, Canal 12 Puerto Madryn |
| Centro | Canal 10 Córdoba, Canal 3 La Pampa, Canal 5 y Telefe Santa Fe, Canal 9 Resistencia |

## Uso

### VLC
`Medios → Abrir archivo de lista de reproducción` y abrís `canales.m3u` directamente, o pegás la URL raw del archivo.

### Desde la terminal
```bash
# VLC
cvlc https://raw.githubusercontent.com/camammoli/iptv/master/canales.m3u

# mpv (un canal directamente)
mpv https://livetrx01.vodgc.net/eltrecetv/index.m3u8
```

### Kodi / TiviMate
Agregar `canales.m3u` como lista de reproducción remota usando la URL raw de GitHub.

## Nota

Los streams son provistos por terceros. Si algún enlace dejó de funcionar, puede que el canal haya cambiado su CDN. Revisá la fuente [iptv-org/iptv](https://github.com/iptv-org/iptv) para URLs actualizadas.
