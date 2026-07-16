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
- Proveedor: STAC público de Copernicus Data Space Element84 (AWS)
- Ventana temporal: 2024-12-03 a 2025-04-25

## Calidad
- Filtro de nubes: <= 30%
- Nº escenas útiles encontradas: 18
- Escena visualizada (fecha): desde 03/12/2024 al 29/04/2025
- Resolución espacial usada: 10 m (B2,B3,B4,B8)

## Dimensiones de calidad (completar 1-2 frases cada una)
- Completitud: Serie de 18 escenas de Sentinel-2 L2A con cobertura de nubes inferior a 30%.
- Exactitud / corrección atmosférica: Se utilizó Sentinel-2 L2A, que ya incluye corrección atmosférica y máscara de nubes.
- Vigencia (recencia de la escena): Las escenas corresponden a datos de la campaña 2024-25 de soja de segunda y permiten observar la evolución del cultivo.
- Consistencia (mismo CRS, mismas bandas): Todas las escenas están en el mismo sistema de coordenadas y contienen las mismas bandas.

## Notas agronómicas esperadas (campaña soja de segunda)
- Siembra: diciembre 2024
- Pico NDVI esperado: marzo 2025
- Cosecha: abril 2025

1. ¿Cuántas escenas Sentinel-2 L2A con < 30 % de nubes hay en la campaña? ¿Cumple el criterio ≥ 30?

Se encontraron 18 escenas Sentinel-2 L2A con cobertura de nubes menor o igual al 30 %. Por lo tanto, la parcela no cumple el criterio de contar 
con al menos 30 escenas útiles. Aun así, la serie permite una primera lectura temporal del cultivo durante la campaña.

2. ¿Qué observas en el RGB? ¿Qué no puedes afirmar todavía?

En las imágenes RGB se distinguen diferencias claras entre sectores del lote y entre lotes vecinos. Se observa una evolución temporal 
compatible con una soja de segunda: tonos más claros al inicio, mayor cobertura verde durante el desarrollo vegetativo y cambios hacia el final de la campaña. 
Sin embargo, solo con RGB no se puede confirmar estrés hídrico, deficiencias nutricionales, enfermedades o problemas de rendimiento. 
Para eso será necesario calcular índices como NDVI, NDRE y NDWI, y luego contrastar con clima y observación de campo.

3. ¿Por qué documentamos una data card antes de hacer ningún análisis?

La data card permite dejar documentado el origen, cobertura, calidad y limitaciones de los datos antes de analizarlos. 
Esto mejora la trazabilidad, evita interpretar resultados sin contexto y permite reproducir el trabajo en los siguientes laboratorios.
