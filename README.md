# Ap_mate_financieras
Este repositorio contiene códigos en Python utilizados en la materia de Aplicación a las Matemáticas Financieras. Los scripts incluyen implementaciones para el análisis y valuación de instrumentos financieros, aplicando conceptos como:  

- **Cambio de tasas** (nominales, efectivas, equivalencias entre tasas).  
- **Cálculo de valores futuros y presentes de anualidades**.  
- **Cálculo del precio de bonos y CETES**.  
- **Cálculo de duración modificada (DM) y convexidad**.  
- **Inmunización de instrumentos financieros**.  

Además implementa conceptos fundamentales de la teoría del portafolio, utilizando datos de las siguientes empresas:  

- **BIMBOA.MX**  
- **LIVEPOLC-1.MX**  
- **GCARSOA1.MX**  

Los cálculos incluyen:  

- **Portafolio de mínima varianza**.
- **Coeficiente de Sharpe**.
- **Portafolio de tangencia**.
# Códigos de Aplicación a las Matemáticas Financieras  



## Requisitos  
Para ejecutar estos códigos, es necesario contar con las siguientes librerías en Python:  

```python
import numpy as np
import pandas as pd
import matplotlib.pyplot as plt
from sympy import symbols, diff
import math
from pandas_datareader import data
import yfinance as yf
