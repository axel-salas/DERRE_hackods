
# Metadatos de los datos

## Fuente principal: []
- **URL**: [enlace]
- **Fecha de descarga**: [YYYY-MM-DD]

## Archivos procesados (en `processed/`)

### `indicadores_ods.csv`
- **Descripción**: Indicadores clave para los ODS seleccionados, por entidad federativa y año.
- **Variables**:
  - `año`: entero, rango 2010–2024.
  - `entidad`: string, nombre del estado.
  - `tasa_alfabetizacion`: float, porcentaje de población alfabetizada.
  - `desercion_escolar`: float, porcentaje.
  - `brecha_genero`: float, diferencia porcentual entre hombres y mujeres.
- **Transformaciones aplicadas**:
  - Se eliminaron registros con valores nulos.
  - Se normalizaron los nombres de las entidades.
  - Se agregaron promedios móviles para suavizar tendencias.

## Archivos originales (en `raw/`)

### `educacion_raw.xlsx`
- **Formato**: Excel, hoja "Datos"
- **Observaciones**: Incluye datos desagregados por nivel educativo que no se usaron en el dashboard final. Se conserva por reproducibilidad.

## Notas adicionales
- Todos los archivos procesados están codificados en UTF-8.
- Para más detalles sobre el proceso de limpieza, ver scripts en `scripts/etl.py`.

SEGUIR ESTRUCTURA EN EL COMENTARIO
