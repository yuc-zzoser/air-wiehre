# Aire · Wiehre

App web móvil en español para estimar la ventilación necesaria para reducir la humedad en habitaciones de Freiburg-Wiehre.

## Uso

Sirve esta carpeta con cualquier servidor web estático y abre `index.html`. No requiere instalación ni compilación. Por ejemplo: `python3 -m http.server 8000`.

Consulta temperatura y humedad exterior con Open-Meteo; permite entrada manual, mediciones interiores por habitación y temporizador de revisión. Los ajustes se guardan en el navegador.

## Modelo y límites

Usa la fórmula de Magnus y un modelo de mezcla con renovaciones por hora supuestas o introducidas por el usuario. El tiempo es orientativo; comprueba el higrómetro tras cerrar y recuperar la temperatura. No garantiza prevenir moho ni sustituye evaluar filtraciones o puentes térmicos.

Datos meteorológicos: https://open-meteo.com/ (modelo para la zona, no sensor en Wiehre Bahnhof).
