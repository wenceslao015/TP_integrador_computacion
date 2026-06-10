# [cite_start]Sistema de Procesamiento de Compras - Supermercado [cite: 11]

[cite_start]Este proyecto implementa un flujo de trabajo basado en **Integración Continua (CI)** utilizando GitHub Actions para validar el procesamiento de datos de compras mediante Corte de Control[cite: 11].

## Estructura del Proyecto
* [cite_start]`main.py`: Lógica principal del negocio (Corte de control y ordenamiento)[cite: 14].
* [cite_start]`test_main.py`: Set de pruebas unitarias automatizadas[cite: 15].
* [cite_start]`.github/workflows/ci.yml`: Pipeline de GitHub Actions[cite: 16].

## Cómo ejecutar las pruebas localmente
```bash
python -m unittest test_main.py