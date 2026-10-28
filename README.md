# BI Prepago · Calidad y Motivo de Llamada

Tablero en un solo archivo HTML que reemplaza al Excel *Prepago - Análisis Motivo de Llamada*.

## Uso

1. Abre `BI_Prepago_Motivo_Llamada.html` en el navegador (requiere internet para cargar las librerías).
2. En **Cargar datos**, sube el Excel final actualizado. Se leen sus hojas «EVAS ipsos» (evaluaciones) y «Dota» (padrón de asesores).
   - Alternativa: subir por separado el export de Qualtrics y el padrón.
3. Todas las pestañas se recalculan. Los datos se procesan solo en tu navegador y quedan guardados en él; no se envían a ningún servidor.

## Pestañas

Resumen · Semanal · Ranking asesores · Motivo de llamada · Pauta · FCR · Ofrecimiento · Pareto · Aspectos críticos.
Al hacer clic en un supervisor, asesor, motivo, ítem o en la Nota Calidad se abre su detalle («¿Por qué esta nota?»).

## Reglas tomadas del Excel

- Nota Calidad = 63% Solución + 20% Ofrecimiento + 17% Conexión.
- Semáforo de la Nota: 85/90 en supervisor, asesor y motivo; 80/85 en el resto (editables en la cabecera).

> Los archivos de datos (`.xlsx`, `.csv`) no se suben a este repositorio porque contienen información personal.
