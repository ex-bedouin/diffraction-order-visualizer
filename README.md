# diffraction-order-visualizer
зачаток физической модели + визуализации дифракционных порядков + ray tracing для щелей/решётки/детектора

Python tool for simulating diffraction orders and ray propagation through a slit/grating structure toward a detector.

## Features
- Diffraction angle calculation for multiple orders
- Geometric filtering by slit aperture
- NA-based angular constraints
- 2D ray-tracing visualization with detector plane

## Installation
```bash
pip install -e .
```

## Quick start
```bash
python examples/normal_incidence.py
python examples/angled_incidence.py
```

## Model assumptions
- 2D geometry
- Scalar diffraction-order angle estimate
- Geometric pass/fail filtering at output slit
