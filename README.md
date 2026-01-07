# Conversor de Monedas TK

Este es un proyecto de escritorio simple que convierte una cantidad de bolívares (VES) a diferentes monedas extranjeras. La aplicación obtiene las tasas de cambio más recientes del Banco Central de Venezuela (BCV) a través de web scraping.

## Características

*   Convierte de Bolívares a las principales monedas (Dólar, Euro, etc.).
*   Obtiene las tasas de cambio actualizadas automáticamente.
*   Interfaz gráfica de usuario (GUI) simple y fácil de usar creada con Tkinter.
*   Guarda un historial de las conversiones realizadas.
*   Permite borrar el historial de conversiones.

## ¿Cómo usar?

1.  Asegúrate de tener Python instalado.
2.  Instala las bibliotecas necesarias. Puedes hacerlo ejecutando el siguiente comando:
    ```bash
    pip install requests beautifulsoup4
    ```
3.  Ejecuta el archivo `conversion.py`:
    ```bash
    python conversion.py
    ```
4.  Selecciona una moneda del menú desplegable.
5.  Ingresa la cantidad en bolívares que deseas convertir.
6.  Haz clic en "Consultar precio" para ver el resultado.
7.  Puedes ver el historial de conversiones haciendo clic en el botón "Historial".

## Archivos del Proyecto

*   `conversion.py`: El archivo principal que ejecuta la aplicación y contiene la interfaz gráfica.
*   `wscrap.py`: Módulo encargado de hacer web scraping a la página del BCV para obtener las tasas de cambio.
*   `historial.py`: Gestiona la ventana y la lógica para mostrar el historial de conversiones.
*   `dltFile.py`: Contiene la función para eliminar el archivo de historial.
*   `ico.py`: Gestiona el ícono de la aplicación.
*   `resultados.txt`: Archivo de texto donde se guarda el historial (se crea automáticamente).

## Dependencias

*   [Python](https://www.python.org/)
*   [Tkinter](https://docs.python.org/3/library/tkinter.html) 
*   [requests](https://pypi.org/project/requests/)
*   [Beautiful Soup](https://pypi.org/project/beautifulsoup4/)
