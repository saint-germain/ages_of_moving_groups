# Edades (aproximadas) de Grupos Móviles 

Descargue los siguientes archivos:

- https://github.com/saint-germain/ages_of_moving_groups/raw/master/ages_lcc.xlsx
- https://github.com/saint-germain/ages_of_moving_groups/raw/master/ages_bpic.xlsx
- https://github.com/saint-germain/ages_of_moving_groups/raw/master/ages_twhya.xlsx
- https://github.com/saint-germain/ages_of_moving_groups/raw/master/ages_ucl.xlsx
- https://github.com/saint-germain/ages_of_moving_groups/raw/master/ages_sco_cen.xlsx

En estos archivos hay simulaciones de las posibles posiciones pasadas de estrellas en grupos móviles cercanos calculadas con sus posiciones y velocidades actuales obtenidas de [GAIA DR2](https://es.wikipedia.org/wiki/Gaia_(sonda_espacial))

## Pasos para encontrar edades (para cada archivo)

- Abra el archivo en Excel
- Para cada época (en Myr):
  - Calcule la desviación estándar para la posición en cada eje (x,y,z) -> (sigma_x,sigma_y,sigma_z)
  - Calcule la magnitud de la desviación estándar: raiz(sigma_x^2+sigma_y^2+sigma_z^2)
- Encuentre para cuál época ésta desviación es mínima. Ésta es la edad aproximada de ese grupo móvil.

## Para pensar e investigar en su casa

- Calculando el promedio de la posición para cada época sería posible identificar estrellas que están muy lejos del promedio y posiblemente están mal identificadas?
- Cómo cambiarían los resultados si en vez de la desviación estándar se usan otras medidas de la dispersión como Median Absolute Deviation (MAD), cuartiles,...?
- Qué métodos se podrían proponer para tener una idea de la incertidumbre de la estimación de la edad por el método estudiado aquí?
