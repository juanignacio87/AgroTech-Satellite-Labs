# Data card — Parcela del caso integrador

## Identidad
- Nombre:Parcela caso integrador
- País / Región: Partido de Pergaminos, Provincia de Buenos Aires, Argentina
- Cultivo: Soja de segunda (Post trigo)
- Superficie aprox. (ha): 100 ha
- AOI (bbox EPSG:4326): [np.float64(-60.723428), np.float64(-33.68732), np.float64(-60.710277), np.float64(-33.676992)]

## Fuente del dato
- Misión: Sentinel-2 (MSI)
- Nivel de procesado: L2A (BOA + máscara SCL)
- Proveedor: STAC público de Element84 (AWS)
- Ventana temporal: 2024-12-03 a 2025-04-25

## Calidad
- Filtro de nubes: <= 30%
- Nº escenas útiles encontradas: 16
- Escena visualizada (fecha): desde 03/12/2024 al 29/04/2025
- Resolución espacial usada: 10 m (B2,B3,B4,B8)

## Dimensiones de calidad (completar 1-2 frases cada una)
- Completitud: Serie de 16 escenas de Sentinel-2 L2A con cobertura de nubes inferior a 30%.
- Exactitud / corrección atmosférica: Se utilizó Sentinel-2 L2A, que ya incluye corrección atmosférica y máscara de nubes.
- Vigencia (recencia de la escena): Las escenas corresponden a datos de la campaña 2024-25 de soja de segunda y permiten observar la evolución del cultivo.
- Consistencia (mismo CRS, mismas bandas): Todas las escenas están en el mismo sistema de coordenadas y contienen las mismas bandas.

## Notas agronómicas esperadas (campaña soja de segunda)
- Siembra: diciembre 2024
- Pico NDVI esperado: marzo 2025
- Cosecha: abril 2025
