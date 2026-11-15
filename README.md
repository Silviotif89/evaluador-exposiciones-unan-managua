# Evaluador de exposiciones · UNAN Managua

Página estática para registrar trabajos finales por grupo y calificar a cada integrante.

## Uso

1. Crea un grupo y escribe el título del trabajo.
2. Agrega un nombre por línea.
3. Califica a cada persona con cinco criterios de 0 a 100.
4. Revisa el resumen y selecciona **Finalizar grupo**.
5. Descarga el CSV y conserva el respaldo JSON.

El puntaje individual es el promedio simple de:

- Dominio del tema
- Organización y claridad
- Análisis y argumentación
- Evidencias y aplicación
- Comunicación y aporte individual

## Almacenamiento

Los registros se guardan en `localStorage` del navegador del dispositivo que se está usando. No se envían a GitHub ni a un servidor. Para continuar en otro dispositivo, usa el respaldo exportado como copia; los registros no se sincronizan automáticamente entre dispositivos.

## Publicar con GitHub Pages

En el repositorio, abre **Settings → Pages** y selecciona **Deploy from a branch**, rama `main`, carpeta `/ (root)`. El archivo de entrada es `index.html`.

