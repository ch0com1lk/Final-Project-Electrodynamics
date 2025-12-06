# Propagación de Ondas Electromagnéticas en Medios Dieléctricos

**Proyecto Final de Electrodinámica**

## Descripción

Este proyecto estudia la **propagación de ondas electromagnéticas en guías de onda dieléctricas simétricas de tres capas**. Se implementa un análisis teórico y computacional para determinar los modos guiados TE (Transversas Eléctricas) permitidos en una estructura dieléctrica con núcleo (core) y cubierta (cladding).

## Autores

- Valeria López Agustín
- Celso Rojas Pérez
- Mariana Martínez Cupul

## Contenidos

El notebook incluye:

1. **Derivación de la ecuación de onda vectorial** en medios lineales, isotrópicos y homogéneos a partir de las ecuaciones de Maxwell
2. **Validación de ondas planas monocromáticas** como soluciones de la ecuación de onda
3. **Relaciones de polarización TE** (Ey, Hx) en guías de onda
4. **Análisis de configuración** de una guía de onda GaAs/AlGaAs (3 capas)
5. **Condiciones de frontera** en interfaces dieléctricas
6. **Solución numérica** de la ecuación característica transcendental para modos guiados
7. **Visualización** de distribuciones del campo eléctrico para múltiples modos

## Parámetros de la Guía de Onda

- **Material:** GaAs/AlGaAs
- **Índice de refracción (núcleo):** n₂ = 3.6
- **Índice de refracción (cubierta):** n₁ = 3.3
- **Espesor del núcleo:** d = 2.0 μm
- **Longitud de onda:** λ = 0.87 μm
- **Número V:** V ≈ 10.39 (multimodo)

## Modos Encontrados

El análisis identifica **4 modos TE guiados** que se propagan en la estructura, siendo TE₀ el modo fundamental con mayor coeficiente β.

## Requisitos

```python
numpy
matplotlib
scipy.optimize.brentq
```

## Cómo ejecutar

```bash
jupyter notebook FinalProject_Electrodynamics-1.ipynb
```

## Notas

El proyecto implementa búsqueda de raíces para resolver ecuaciones características transcendentales de modos pares (simétricos) e impares (antisimétricos), con cálculos de parámetros derivados como constante de propagación (β) e índice efectivo (neff).
