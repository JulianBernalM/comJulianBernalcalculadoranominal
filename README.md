# Calculadora de Nómina Colombiana

Aplicación móvil desarrollada para Android utilizando Jetpack Compose. El proyecto está basado en el modelo simplificado planteado en el taller de septiembre de 2026, por lo que no corresponde a una liquidación laboral oficial.

## Cómo abrir el proyecto en Android Studio
1. Extrae el archivo ZIP y, desde Android Studio, selecciona Open en la carpeta CalculadoraNomina.
2. Espera a que finalice la sincronización de Gradle. Es necesario contar con conexión a Internet para descargar las dependencias requeridas.
3. Elige un emulador de Android y ejecuta la aplicación app.

## Archivos
- 
- `NominaCalculator.kt`: contiene las constantes, las reglas utilizadas y la lógica para realizar los cálculos, independiente de la interfaz gráfica.
- `drawable/rango_*.xml`: contiene tres imágenes vectoriales utilizadas para representar los diferentes rangos.
- `MainActivity.kt`: incluye la interfaz desarrollada con Compose, las validaciones, los campos de entrada y los interruptores reutilizables.
- `strings.xml`: almacena los textos que se muestran en la aplicación.