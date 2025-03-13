# Control de Horas Chimba Pizza

Una aplicación web para registrar y gestionar las horas de trabajo de los empleados de Chimba Pizza. La aplicación permite registrar entradas y salidas, calcular horas trabajadas y exportar los registros a CSV.

## Características

- ⏱️ Registro de entrada y salida para múltiples empleados
- 📊 Cálculo automático de horas trabajadas
- 💾 Almacenamiento local de registros en el navegador
- 📋 Exportación de datos a formato CSV
- 📱 Diseño responsive para todo tipo de dispositivos
- 📝 Sincronización con Google Sheets para respaldo de datos

## Uso

1. Haz clic en el botón con el nombre del empleado para registrar su entrada.
2. El botón cambiará de color (verde a rojo) para indicar que el empleado está trabajando.
3. Haz clic nuevamente en el botón para registrar la salida.
4. Los registros aparecerán en la sección "Registros de hoy".
5. Utiliza el botón "Descargar CSV" para exportar todos los registros.

## Implementación

Esta aplicación está diseñada para funcionar como una página web estática, almacenando datos localmente en el navegador y sincronizándolos con Google Sheets.

### Requisitos para Google Sheets

Para conectar con Google Sheets:

1. Crea una hoja de cálculo en Google Sheets
2. Configura un script de Google Apps Script para recibir los datos
3. Actualiza la URL del script en el código (`scriptURL` en la función `sendToGoogleSheets`)

## Desarrollo

Para modificar o mejorar la aplicación:

1. Clona este repositorio
2. Modifica el archivo index.html según tus necesidades
3. Prueba los cambios localmente
4. Haz commit y push a GitHub para implementar los cambios

## Licencia

[MIT](https://choosealicense.com/licenses/mit/)

---

Desarrollado para Chimba Pizza © 2025
