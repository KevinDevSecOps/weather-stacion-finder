# Weather Stations Finder

Este proyecto permite detectar estaciones meteorológicas cercanas y consultar la meteorología de tu zona utilizando Python 3.

## Objetivos

- Detectar automáticamente estaciones meteorológicas próximas a tu ubicación.
- Obtener información meteorológica relevante y actualizada.
- Ser fácil de usar y de contribuir.

## ¿Por qué Python?

Python cuenta con una gran cantidad de librerías para conectarse con APIs meteorológicas y realizar geolocalización, facilitando la integración y el crecimiento del proyecto.

## Instalación rápida

```bash
git clone https://github.com/KevinDevSecOps/weather-stations-finder.git
cd weather-stations-finder/src
pip install -r requirements.txt
python main.py
```

## Ejemplo de uso

```python
from main import buscar_estaciones_cercanas

# Coordenadas de ejemplo: Madrid, España
lat = 40.4168
lon = -3.7038

estaciones = buscar_estaciones_cercanas(lat, lon)
print(estaciones)
```

## Estructura del proyecto

- `src/` — Código fuente principal.
   - `main.py` — Lógica principal.
   - `requirements.txt` — Dependencias.
- `tests/` — Pruebas automáticas.
- `README.md` — Documentación y guía de inicio.
- `LICENSE` — Licencia del proyecto.

## Ideas para contribuir

- Conectar con APIs abiertas de meteorología (OpenWeatherMap, AEMET, etc.)
- Mejorar la interfaz de línea de comandos.
- Añadir soporte para otras regiones.
- Crear documentación más detallada.

¡Abre un issue si tienes otra idea!

## Licencia

Este proyecto está bajo la licencia MIT.

---

_Echo por [KevinDevSecOps](https://github.com/KevinDevSecOps) con ❤️_
