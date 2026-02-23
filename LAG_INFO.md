# Pokemon Fire Ash - Información sobre Rendimiento

## El problema del Lag

Pokemon Fire Ash es un juego **MUCHO más grande** que otros ports:

| Juego | Tamaño | Archivos |
|-------|--------|---------|
| Pokemon Reborn | 34 MB | ~1,000 archivos |
| **Pokemon Fire Ash** | **660 MB** | **~21,000 archivos** |

Fire Ash es **20 veces más grande** que Reborn, lo que causa tirones en hardware limitado como la R36S.

## Configuraciones disponibles

### mkxp.json (Normal)
Configuración optimizada para equilibrio rendimiento/calidad.

### mkxp-performance.json (Máximo rendimiento)
Configuración agresiva si el normal aún tiene lag.

## Si el lag persiste

El lag es causado por:
1. **Tamaño del juego** - 21,000 archivos deben cargarse
2. **Hardware limitado** - RK3566 no es muy potente
3. **Python/Pokemon Essentials** - Motor muy pesado

**No es un bug del port**, es una limitación del hardware con este juego específico.

## Consejos

- Guarda frecuentemente (el juego puede crashear por falta de RAM)
- No habilites "Auto-run" permanentemente
- Evita áreas con muchos efectos gráficos
