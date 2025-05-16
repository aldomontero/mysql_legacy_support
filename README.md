# mysql_legacy_support.php

## Descripción

Este archivo proporciona soporte de compatibilidad para funciones de conexión a bases de datos MySQL utilizadas en código escrito para PHP 5.

Está diseñado para facilitar la ejecución de sistemas heredados en entornos modernos con PHP 8, donde las funciones `mysql_*` han sido eliminadas.

> **Nota:** Este script **no** reemplaza una migración adecuada a `mysqli` o `PDO`, pero permite mantener funcionalidad temporal mientras se actualiza el código.

## Uso previsto

Incluir este archivo en proyectos PHP 8 que aún dependen de funciones de conexión MySQL estilo PHP 5 para evitar errores de compatibilidad.

## Recomendación

Migrar a `mysqli` o `PDO` lo antes posible para garantizar seguridad, mantenimiento y compatibilidad futura.
