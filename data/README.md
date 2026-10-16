# Datos

## Muestra incluida

`data/sample/` contiene 20 imágenes de ejemplo: 10 de `Negative` (sin grieta) y 10 de `Positive` (con grieta). Se han seleccionado del conjunto [Concrete Crack Images for Classification, versión 2](https://data.mendeley.com/datasets/5y9wdsg2zt/2), creado por Çağlar Fırat Özgenel. Los archivos se mantienen sin modificar. Consulta [`sample/README.md`](sample/README.md) para la atribución, licencia y referencias bibliográficas.

## Conjunto completo para reproducir el entrenamiento

El conjunto completo tiene 40.000 imágenes, distribuidas en 20.000 por clase. No se incluye en este repositorio. Para ejecutar el notebook con el conjunto completo, coloca una copia obtenida de la fuente en esta ruta:

    data/cemento_dataset/
    ├── Negative/
    └── Positive/

Git excluye `data/cemento_dataset/` para evitar subir accidentalmente la copia completa. La muestra de `data/sample/` sí se versiona.
