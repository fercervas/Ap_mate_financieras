# Aplicación-a-las-matemáticas-financieras
Este repositorio contiene los códigos que utilicé en mi curso de Aplicación a las Matemáticas Financieras. Incluye implementación en Python para el cálculo de anualidades, tasas de interés, bonos, inmunización y cálculo de duración modificada y convexidad para instrumentos financieros.
# Códigos de Aplicación a las Matemáticas Financieras  

Este repositorio contiene códigos en Python utilizados en la materia de Aplicación a las Matemáticas Financieras. Los scripts incluyen implementaciones para el análisis y valuación de instrumentos financieros, aplicando conceptos como:  

- **Cambio de tasas** (nominales, efectivas, equivalencias entre tasas).  
- **Cálculo de valores futuros y presentes de anualidades**.  
- **Cálculo del precio de bonos y CETES**.  
- **Cálculo de duración modificada (DM) y convexidad**.  
- **Inmunización de instrumentos financieros**.  

## Requisitos  
Para ejecutar estos códigos, es necesario contar con las siguientes librerías en Python:  

```python
import numpy as np
import pandas as pd
import matplotlib.pyplot as plt
from sympy import symbols, diff
import math
