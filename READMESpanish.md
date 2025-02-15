Objetivo: Descarga de Datos desde APIs Publicas.

Consigna:
Buscar información en APIs públicas (i.e Twitter, NewsAPI, Spotify, Google Apis, etc).
Extraer datos e importarlos a un dataframe realizando una exploración simple. 

Aspectos a incluir:
Notebook donde se detallen todos los pasos seguidos
Formato:  Se debe entregar un jupyter notebook con el nombre “actividad práctica_APIS_+Nombre_ +Apellido.ipynb”.

Pasos a Seguir:
Selección de la API: Elegiremos una API pública para extraer datos. En este ejemplo, utilizaremos la API de NewsAPI para obtener noticias recientes.
Registro y Obtención de la Clave API: Necesitaremos registrarnos en NewsAPI para obtener una clave API.
Instalación de Librerías: Instalaremos las librerías necesarias para hacer solicitudes HTTP y manipular datos.
Extracción de Datos: Haremos una solicitud a la API para obtener datos.
Importación a un DataFrame: Convertiremos los datos obtenidos en un DataFrame de Pandas.
Exploración Simple: Realizaremos una exploración básica de los datos.


Explicación del Código:
Instalación de Librerías: Instalamos requests para hacer solicitudes HTTP y pandas para manipular los datos.
Importación de Librerías: Importamos las librerías necesarias.
Configuración de la API: Definimos la URL de la API y los parámetros necesarios, incluyendo la clave API.
Solicitud a la API: Hacemos una solicitud GET a la API y verificamos si la respuesta es exitosa (código 200).
Importación a un DataFrame: Convertimos los datos obtenidos en un DataFrame de Pandas.
Exploración Simple: Mostramos las primeras filas del DataFrame, información general y estadísticas descriptivas.
Guardar el DataFrame: Opcionalmente, guardamos los datos en un archivo CSV.
