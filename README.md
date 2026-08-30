# QA Project: Urban Grocers - Kit Name Validation

Este proyecto automatiza la validación del campo `name` en el endpoint de creación 
de kits de la aplicación Urban Grocers, cubriendo 9 casos de la lista de comprobación 
(límites de caracteres, caracteres especiales, espacios, tipos de dato, y parámetros ausentes).

## Estructura del proyecto
- `configuration.py` — URLs y rutas del servidor
- `data.py` — cuerpos de las solicitudes
- `sender_stand_request.py` — funciones de envío de solicitudes
- `create_kit_name_kit_test.py` — pruebas automatizadas

## Cómo ejecutar las pruebas

1. Instala las dependencias:
   pip install pytest requests

2. Ejecuta la suite completa:
   pytest create_kit_name_kit_test.py

3. Ejecuta un test específico:
   pytest create_kit_name_kit_test.py::test_1_kit_name_with_1_latter

REALIZODO POR:
Milton Montes Tangarife - Grupo: 79

