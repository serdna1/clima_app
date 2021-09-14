# Aplicación Node de Clima

Usar el comando 'npm init' al bajarse el proyecto, para construir los módulos de Node. Luego, usar 'node index' para correr la app.

Se muestran las coordenadas (latitud y longitud) e información climática (temperatura, temperatura mínima, temperatura máxima y descripción) del lugar seleccionado.
También se puede ver un historial con los últimos 6 lugares consultados.

Además el historial se guarda en un fichero, por lo tanto al reiniciar la app seguirá existiendo.

Para obtener las coordenadas del lugar se hace uso de la API "[Mapbox Geocoding API](https://docs.mapbox.com/api/search/geocoding/)" y para la información climática se usa una API de [OpenWeather](https://openweathermap.org/) que devuelve información climática actual a partir de coordenadas.

<br><br><br>

---
Esta aplicación es parte del siguiente curso:<br>
[Node de cero a experto](https://fernando-herrera.com/#/curso/node-cero-experto)