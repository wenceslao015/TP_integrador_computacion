# Sistema de Procesamiento de Compras - Supermercado 

Este proyecto implementa un flujo de trabajo basado en **Integración Continua (CI)** utilizando GitHub Actions para validar el procesamiento de datos de compras mediante Corte de Control.

## Estructura del Proyecto
* `main.py`: Lógica principal del negocio (Corte de control y ordenamiento).
* `test_main.py`: Set de pruebas unitarias automatizadas.
* `.github/workflows/ci.yml`: Pipeline de GitHub Actions.

## Cómo ejecutar las pruebas localmente
```bash
python -m unittest test_main.py